## Hello! 
The data in this repository accompanies our paper, [*On the convergent validity of risk sensitivity measures*](https://google.com/). A brief dataset description is provided below. The detailed data acquisition protocol is available in the paper. 

If you use these data in your own work, please consider including the following citation: 



Datasets
--------

### Reinforcement learning task

This task asseses risk sensitivity from experience. Participants made repeated choices between stimuli associated with different reward probabilities. Trialtype 2 marks "risk trials", in which participants made a choice between options of the same expected value, but differing in variance. The proportion of times a participant chooses the safe option in these trials can be used as a continous measure of risk sensitivity. 

| Variable    | Description                                                     				|
|-------------|---------------------------------------------------------------------------------|
| subj        | De-identified participant identifier                            				|
| trial       | Unique trial identifier                                         				|
| trialtype   | Trialtype, defined by stimulus pair (1-9)                       				|
| side        | Side of screen associated with response (Left/Right)         					|
| response    | Chosen stimulus   																|
| outcome     | Outcome of choice in cents (0/2/4)                       						|
| rt          | Response time in miliseconds  													|
| version     | Study version (4/5). Version were run 6 months apart with identical protocols.  |

Representative citations: 

> @article{niv2012neural,
  title={Neural prediction errors reveal a risk-sensitive reinforcement-learning process in the human brain},
  author={Niv, Yael and Edlund, Jeffrey A and Dayan, Peter and O'Doherty, John P},
  journal={Journal of Neuroscience},
  volume={32},
  number={2},
  pages={551--562},
  year={2012},
  publisher={Soc Neuroscience}
}

@article{arkadir2016dyt1,
  title={DYT1 dystonia increases risk taking in humans},
  author={Arkadir, David and Radulescu, Angela and Raymond, Deborah and Lubarr, Naomi and Bressman, Susan B and Mazzoni, Pietro and Niv, Yael},
  journal={elife},
  volume={5},
  pages={e14155},
  year={2016},
  publisher={eLife Sciences Publications Limited}
}

### Holt & Laury task

This task assesses risk sensitivity from description. Participants made a series of 10 choices between two gambles, A and B, for which the relative expected value of each gamble gradually changes. Gamble A is considered the “safe" gamble, as its variance is generally lower than that of Gamble B. The number of times a participant chooses Gamble A over Gamble B (i.e., the number of “safe", low-risk choices) can be used as a continuous measure of risk sensitivity ranging from highly risk loving (0-1 safe choices) to highly risk averse (9-10 safe choices) 

| Variable    | Description                                                     				|
|-------------|---------------------------------------------------------------------------------|
| subj        | De-identified participant identifier                            				|
| response    | Chosen gamble (Gamble A/Gamble B)                                        		|
| rt          | Response time in miliseconds  													|
| version     | Study version (4/5). Version were run 6 months apart with identical protocols.  |


Representative citation:

@article{holt2002risk,
  title={Risk aversion and incentive effects},
  author={Holt, Charles A and Laury, Susan K},
  journal={American economic review},
  volume={92},
  number={5},
  pages={1644--1655},
  year={2002}
}

### DOSPERT questionnaire 

This questionnaire assesses risk sensitivity from self-report. For each of 30 behaviors, participants rate the expected benefits of engaging in each behavior, the perceived risk associated with each behavior, and the likelihood of engaging in each behavior (aka risk-taking). All responses are recorded on a scale from 1-7 (ranging from "none" to "extremely"). The 30 behavior descriptions were presented serially, each of them once for assessing benefits, once for assessing perceived risk, and once for assessing risk-taking. This yielded 90 unique questionnaire items (first 30 for perceived benefits, middle 30 for perceived risk, last 30 for risk-taking). The 31st and 62nd responses are recorded for screen advancement and should be excluded from the analysis. The original DOSPERT instrument and scoring instructions are provided in the repository.

| Variable    | Description                                                     				|
|-------------|---------------------------------------------------------------------------------|
| subj        | De-identified participant identifier                            				|
| response    | Response to item                                       							|
| rt          | Response time in miliseconds  													|
| version     | Study version (4/5). Version were run 6 months apart with identical protocols.  |

Representative citation: 

@article{blais2006domain,
  title={A domain-specific risk-taking (DOSPERT) scale for adult populations},
  author={Blais, Ann-Ren{\'e}e and Weber, Elke U},
  journal={Judgment and Decision making},
  volume={1},
  number={1},
  year={2006}
}

### BIS-BAS questionnaire 

This questionnaire assesses behavioral activation and inhibition from self-report. For each of 24 statements, participants rate their agreement with the statement. All responses are recorded on a scale from 1-4 (ranging from "very true for me" to "very false for me"). The items and scoring instructions can be found at [this](https://local.psy.miami.edu/people/faculty/ccarver/availbale-self-report-instruments/bisbas-scales/) link.  

| Variable    | Description                                                     				|
|-------------|---------------------------------------------------------------------------------|
| subj        | De-identified participant identifier                            				|
| response    | Response to item                                       							|
| rt          | Response time in miliseconds  													|
| version     | Study version (4/5). Version were run 6 months apart with identical protocols.  |

Representative citation:

@article{carver1994behavioral,
  title={Behavioral inhibition, behavioral activation, and affective responses to impending reward and punishment: the BIS/BAS scales.},
  author={Carver, Charles S and White, Teri L},
  journal={Journal of personality and social psychology},
  volume={67},
  number={2},
  pages={319},
  year={1994},
  publisher={American Psychological Association}
}


