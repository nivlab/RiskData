## Hello! 
The data in this repository accompanies our paper, [*On the convergent validity of risk sensitivity measures*](https://psyarxiv.com/qdhx4). A brief dataset description is provided below. The detailed data acquisition protocol is available in the paper. 

If you use these data in your own work, please consider including the following citation: 

> Radulescu, A., Holmes, K., & Niv, Y. (2020). On the convergent validity of risk sensitivity measures. Retrieved from psyarxiv.com/qdhx4

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

> Niv, Y., Edlund, J. A., Dayan, P., & O'Doherty, J. P. (2012). Neural prediction errors reveal a risk-sensitive reinforcement-learning process in the human brain. Journal of Neuroscience, 32(2), 551-562.

> Arkadir, D., Radulescu, A., Raymond, D., Lubarr, N., Bressman, S. B., Mazzoni, P., & Niv, Y. (2016). DYT1 dystonia increases risk taking in humans. elife, 5, e14155.

### Holt & Laury task

This task assesses risk sensitivity from description. Participants made a series of 10 choices between two gambles, A and B, for which the relative expected value of each gamble gradually changes. Gamble A is considered the “safe" gamble, as its variance is generally lower than that of Gamble B. The number of times a participant chooses Gamble A over Gamble B (i.e., the number of “safe", low-risk choices) can be used as a continuous measure of risk sensitivity ranging from highly risk loving (0-1 safe choices) to highly risk averse (9-10 safe choices). 

| Variable    | Description                                                     				|
|-------------|---------------------------------------------------------------------------------|
| subj        | De-identified participant identifier                            				|
| response    | Chosen gamble (Gamble A/Gamble B)                                        		|
| rt          | Response time in miliseconds  													|
| version     | Study version (4/5). Version were run 6 months apart with identical protocols.  |


Representative citation:

> Holt, C. A., & Laury, S. K. (2002). Risk aversion and incentive effects. American economic review, 92(5), 1644-1655.

### DOSPERT questionnaire 

This questionnaire assesses risk sensitivity from self-report. For each of 30 behaviors, participants rate the expected benefits of engaging in each behavior, the perceived risk associated with each behavior, and the likelihood of engaging in each behavior (aka risk-taking). All responses are recorded on a scale from 1-7 (ranging from "none" to "extremely"). The 30 behavior descriptions were presented serially, each of them once for assessing benefits, once for assessing perceived risk, and once for assessing risk-taking. This yielded 90 unique questionnaire items (first 30 for perceived benefits, middle 30 for perceived risk, last 30 for risk-taking). The 31st and 62nd responses are recorded for screen advancement and should be excluded from the analysis. The original DOSPERT instrument and scoring instructions are provided in the repository.

| Variable    | Description                                                     				|
|-------------|---------------------------------------------------------------------------------|
| subj        | De-identified participant identifier                            				|
| response    | Response to item                                       							|
| rt          | Response time in miliseconds  													|
| version     | Study version (4/5). Version were run 6 months apart with identical protocols.  |

Representative citation: 

> Blais, A. R., & Weber, E. U. (2006). A domain-specific risk-taking (DOSPERT) scale for adult populations. Judgment and Decision making, 1(1).

### BIS-BAS questionnaire 

This questionnaire assesses behavioral activation and inhibition from self-report. For each of 24 statements, participants rate their agreement with the statement. All responses are recorded on a scale from 1-4 (ranging from "very true for me" to "very false for me"). The items and scoring instructions can be found at [this](https://local.psy.miami.edu/people/faculty/ccarver/availbale-self-report-instruments/bisbas-scales/) link.

| Variable    | Description                                                     				|
|-------------|---------------------------------------------------------------------------------|
| subj        | De-identified participant identifier                            				|
| response    | Response to item                                       							|
| rt          | Response time in miliseconds  													|
| version     | Study version (4/5). Version were run 6 months apart with identical protocols.  |

Representative citation:

> Carver, C. S., & White, T. L. (1994). Behavioral inhibition, behavioral activation, and affective responses to impending reward and punishment: the BIS/BAS scales. Journal of personality and social psychology, 67(2), 319.


