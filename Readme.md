# Project 1. Kaggle-enviremoent to rps competition

## Table of Contents  
* [1. Project Description](#project-description)
* [2. Competition сonditions](#Competition-сonditions)
* [3. Brief Information About the Data](#brief-information-about-the-data)  
* [4. Results](#results)  
* [5. Conclusions](#conclusions)  

### Project Description    
Run several agents to play RPS using kaggle_environments package

:arrow_up:[Back to Table of Contents](#table-of-contents)

### Competition сonditions 
14 agents are competing in the game of RPS:
- RockAgent
- PaperAgent
- ScissorsAgent
- CopyAgent
- ReactionAgent
- TransitionAgent
- CounterAgent
- CircularAgent
- RandomAgent
- BiasedAgent
- FrequencyAgent
- LogisticAgent
- LinearAgent
- AdaptiveAgent


:arrow_up:[Back to Table of Contents](#table-of-contents)

### Results  
|                 |   RockAgent |   PaperAgent |   ScissorsAgent |   CopyAgent |   ReactionAgent |   TransitionAgent |   CounterAgent |   CircularAgent |   RandomAgent |   BiasedAgent |   FrequencyAgent |   LogisticAgent |   LinearAgent |   AdaptiveAgent |
|:----------------|------------:|-------------:|----------------:|------------:|----------------:|------------------:|---------------:|----------------:|--------------:|--------------:|-----------------:|----------------:|--------------:|----------------:|
| RockAgent       |         nan |           99 |             -99 |           0 |              99 |                 0 |             98 |               0 |             0 |             0 |               98 |              98 |            98 |             -72 |
| PaperAgent      |         -99 |          nan |              99 |           0 |              98 |                26 |             99 |               0 |             0 |           -30 |                0 |              99 |            98 |             -76 |
| ScissorsAgent   |          99 |          -99 |             nan |           0 |              97 |                35 |             99 |               0 |             0 |            27 |              -98 |              97 |            98 |             -81 |
| CopyAgent       |           0 |            0 |               0 |         nan |             -99 |                 0 |             50 |              99 |             0 |             0 |                0 |              50 |           -99 |               0 |
| ReactionAgent   |         -99 |          -98 |             -97 |          99 |             nan |                 0 |              0 |               0 |             0 |             0 |              -81 |               0 |             0 |               0 |
| TransitionAgent |           0 |          -26 |             -35 |           0 |               0 |               nan |              0 |               0 |             0 |             0 |                0 |               0 |             0 |             -20 |
| CounterAgent    |         -98 |          -99 |             -99 |         -50 |               0 |                 0 |            nan |               0 |             0 |             0 |              -49 |               0 |             0 |              22 |
| CircularAgent   |           0 |            0 |               0 |         -99 |               0 |                 0 |              0 |             nan |             0 |             0 |              -33 |               0 |             0 |              77 |
| RandomAgent     |           0 |            0 |               0 |           0 |               0 |                 0 |              0 |               0 |           nan |             0 |                0 |               0 |             0 |               0 |
| BiasedAgent     |           0 |           30 |             -27 |           0 |               0 |                 0 |              0 |               0 |             0 |           nan |                0 |               0 |             0 |               0 |
| FrequencyAgent  |         -98 |            0 |              98 |           0 |              81 |                 0 |             49 |              33 |             0 |             0 |              nan |              57 |            49 |             -77 |
| LogisticAgent   |         -98 |          -99 |             -97 |         -50 |               0 |                 0 |              0 |               0 |             0 |             0 |              -57 |             nan |             0 |               0 |
| LinearAgent     |         -98 |          -98 |             -98 |          99 |               0 |                 0 |              0 |               0 |             0 |             0 |              -49 |               0 |           nan |             -26 |
| AdaptiveAgent   |          72 |           76 |              81 |           0 |               0 |                20 |            -22 |             -77 |             0 |             0 |               77 |               0 |            26 |             nan |

:arrow_up:[Back to Table of Contents](#table-of-contents)

### Conclusions  
The CounterAgent produced unexpected results, delivering a winning value based on the opponent's previous action.

Regression models also performed well, as they were trained on the opponent's previous moves and identified correlations with the current value.

:arrow_up:[Back to Table of Contents](#table-of-contents)

If you find the information in this project interesting or useful, I would greatly appreciate it if you could star the repository and profile ⭐️⭐️⭐️.
