# Simple Python OCR

A simple pythonic OCR engine using opencv and numpy.
### Essential Concepts

#### Segmentation

In order for OCR to be performed on a image, several steps must be 
performed on the source image. Segmentation is the process of 
identifying the regions of the image that represent characters. 

This project uses rectangles to model segments. 

#### Supervised learning with a classification problem

The [classification problem][] consists in identifying to which class a 
observation belongs to (i.e.: which particular character is contained 
in a segment).

[Supervised learning][] is a way of "teaching" a machine. Basically, an 
algorithm is *trained* through *examples* (i.e.: this particular 
segment contains the character `f`). After training, the machine 
should be able to apply its acquired knowledge to new data.

The [k-NN algorithm], used in this project, is one of the simplest  
classification algorithm.

#### Grounding

Creating a example image with already classified characters, for 
training purposes.
See [ground truth][].

[classification problem]: https://en.wikipedia.org/wiki/Statistical_classification
[Supervised learning]: https://en.wikipedia.org/wiki/Supervised_learning
[k-NN algorithm]: https://en.wikipedia.org/wiki/K-nearest_neighbors_classification
[ground truth]: https://en.wikipedia.org/wiki/Ground_truth


