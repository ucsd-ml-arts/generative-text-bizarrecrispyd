
# Project 1 Generative Text - Magic Spice for Love Letter

Yudi Wang, yuw043@ucsd.edu

<img src="https://github.com/ucsd-ml-arts/generative-text-bizarrecrispyd/blob/master/word%20cloud.png" width="400">

（Above is the Word Cloud generated according to word frequencies in the dataset）

## Abstract

Love letter is a traditional but still popular way to impress our lovers; yet write an successful one is hard. What's the key elements that makes the unique love letter in the world? In what way it impress people? In this project, RNN is adopted to generate brand new love letter according to the sample love letter collected via internet. In the dataset, there are also  some poetic sentences, famous love letter in the history and also short stories, which try to make the result more authentic. 


After tuning the model, several romantic pieces are generated. They are mixed with really love letters to consist a questionnaire. I invite several friends to make judgement and give comments. From the result we can conclude that people whose native language is not English cannot pick the right fake one. 


## Model/Data


- trained models - RNN 
- training data - 【love_total.txt】
  - short sample love letter mixed with some poetic sentences, famous love letter in the history and also short stories, which is collected by myself via internet
- result - 【Love, true or fake? - Questionnaire.pdf】


## Code

Related code for generating this project:
- loveletter.ipynb - training & generating code

## Results and Analysis
The correct answer of the questionnaire should be: 1 A, 2 D, 3 A ,4 D, 5 B

The correct rate of my friends: *PH: 20%, LZZ: 80%, ZTT: 0%, LZY: 40%*, which varies a lot. According to their comment, I get two conclusions:

1.The biggest difference among the fake and true should be the inner logic. 
Algorithm can learn words, grammer and even mimic the poem-like strcture, but it cannot provide a reasonable writing logic. Some sentences has no relationship with the previous sentences. Even for the poems, you cannot feel the logic and also the emotion is not continuous in these paragraph.

2.Non-native speaker cannot tell the subtle differences in the questionnaire
For those who don't use English as their daily language, that is, foreigners just like me. We cannot tell these small weired points directly and thus our judgement are made according to other baseline, which are shown as below:

 - too many sentences begins with "I"
 - struture are simple and no complex words
 - grammar mistakes or wrong words
 - discontinuous logic between sentences
 



## Further Step

Using bigger dataset and further tuning the parameters should made the result better.
