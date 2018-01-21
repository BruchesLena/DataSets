# [Experiments Descriptions](https://github.com/BruchesLena/DataSets/wiki/)

# DataSets

## Gradient values
### [DataSet for gradient values](https://raw.githubusercontent.com/BruchesLena/DataSets/master/gradientValues.txt)
Size: 100 pairs

Task: for a given pair of words one should determine what word is closer to the maximum value (e.g. *fast* is closer to **max** and *slow* is closer to **min**).

Anntotation: each pair is annotated in the following way:

  `fast 1, slow 0`
  
 where *1* and *0* are for maximum and minimum respectively.
 
 ### [DataSet for gradient values (quantitative)](https://raw.githubusercontent.com/BruchesLena/DataSets/master/gradientValuesQuantity.txt)
 Conatains only andjectives which are used for quantity.
 
 Size: 38 pairs
 
 
 ## Question frames
 ### [Question beginnings](https://raw.githubusercontent.com/BruchesLena/DataSets/master/questBeginnings.txt)
 File contains 91 question beginnings for English, sorted in alphabetic order.
 ### [Question frames]()
 *later*
 
 ## Attributes
 There are some data sets for the task of determining whether the given adjective is an attribute for a noun or not (e.g. *fast* is an attribute for *speed* but not for *weight*).
 ### [Nouns and their attributes](https://raw.githubusercontent.com/BruchesLena/DataSets/master/nounToAdjAntonyms.txt)
Created via WordNet in NLTK. Contains about 700 groups.

Organized in the following way:

`Noun : its attributes`

Example:

`sureness:incertain, certain, sure, uncertain, unsure`

### [Attributes and their nouns](https://raw.githubusercontent.com/BruchesLena/DataSets/master/AdjToNouns.txt)
Inverted set from the previous one. Countains about 860 groups.

Organized in the following way:

`Adjective: nouns which it belongs to`

Example:

`long:duration, length`

### [Data set for this task](https://raw.githubusercontent.com/BruchesLena/DataSets/master/testSet.txt)

Contains 200 samples, 3-5 candidates in each sample.

Organized in the following way:

`Adjective:Right noun:set of noun candidates`

Example:

`deep:depth:orient,fervor,depth,likelihood`
