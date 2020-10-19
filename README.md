# Lima Districts Analysis

## Business Problem

Currently, there are processes that, to be valid or authenticated, have to be handwritten. Most of these manuscripts can only be recognized by a human being or by very few applications, so the need to process information of this nature is merely existent. That is why it is important to work with a program that allows the manuscripts to be processed and interpreted by a machine in order to obtain a substantial saving of resources in terms of money and time.

## Data Source

The data was extracted normalized bitmaps of handwritten digits from a preprinted form. From a total of 43 people, 30 contributed to the training set and different 13 to the test set. 32x32 bitmaps are divided into nonoverlapping blocks of 4x4 and the number of on pixels are counted in each block. This generates an input matrix of 8x8 where each element is an integer in the range 0..16. This reduces dimensionality and gives invariance to small distortions. 

Attribute Information:

All input attributes are integers in the range 0..16.
The last attribute is the class code 0..9

[Source](https://archive.ics.uci.edu/ml/datasets/optical+recognition+of+handwritten+digits)