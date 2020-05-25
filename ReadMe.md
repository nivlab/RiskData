## Hello! 
The data in this repository accompanies our paper [*On the convergent validity of risk sensitivity measures*](https://google.com/). A detailed dataset description is provided below. 

Datasets
--------

### Reinforcement learning task. 
This task asseses risk sensitivity from experience. Participants made repeated choices between stimuli associated with different reward probabilities. Trialtype 2 marks "risk trials", in which participants made a choice between options of the same expected value, but differing in variance. 

| Variable    | Description                                                     				|
|-------------|---------------------------------------------------------------------------------|
| subj        | De-identified participant identifier                            				|
| trial       | Unique trial identifier                                         				|
| trialtype   | Trialtype, defined by stimulus pair (1-9)                       				|
| side        | Side of screen associated with response (Left/Right)         					|
| response    | Chosen stimulus   																|
| outcome     | Outcome of choice in cents (0/2/4)                       						|
| rt          | Response time in miliseconds  													|
| version     | Study version (4-5). Version were run 6 months apart with identical protocols.  |

### Holt & Laury task. 

This task assesses risk sensitivity from experience. Participants made a series of 10 choices between two gambles, A and B, for which the relative expected value of each gamble gradually changes. Gamble A is considered the “safe" gamble, as its variance is generally lower than that of Gamble B. The number of times the participant chooses Gamble A over Gamble B (i.e., the number of “safe", low-risk choices) can be used as a continuous measure of risk sensitivity ranging from highly risk loving (0-1 safe choices) to highly risk averse (9-10 safe choices (Holt & Laury 2002). Participants with inconsistent switch points, or participants who chose Gamble B on the 1st trial and then switched back to Gamble A, were excluded from the dataset.


| Variable    | Description                                                     				|
|-------------|---------------------------------------------------------------------------------|
| subj        | De-identified participant identifier                            				|
| response    | Chosen gamble (Gamble A/Gamble B)                                        		|
| rt          | Response time in miliseconds  													|
| version     | Study version (4-5). Version were run 6 months apart with identical protocols.  |


### DOSPERT questionnaire. 



### BIS-BAS questionnaire. 