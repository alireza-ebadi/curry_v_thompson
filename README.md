# curry_v_thompson
 
## This project compares the shooting performance of Stephen Curry and Klay Thompson in 2018-19 season. It is based on the master code devloped in [this repository](https://github.com/alireza-ebadi/nba_player_shooting_comparison). It is intended to detect areas in which a good player such as Klay Thompson can work on to reach to an elite level of a player such as Stephen Curry. 

Here are the observations: 
Both players have a similar overal shooting performncae. 

![Sample](Curry_vs_Thompson_all.png?raw=true)


**Available Files:**
1. [nba_player_shooting_comparison.ipynb](nba_player_shooting_comparison.ipynb): 
  -The notebook is segregated into 3 chapters:
    1. import modules and libraries and set parameters
    2. define functions to draw a 2D NBA courts
    3. find player ID and team ID of the players requested by the user
    4. get shot chart details of the basketball players (all shot attempts during regular season)
    5. compare the 3 point shots beyond the arc
    6. compare the corner 3 point shots
    7. compare the 2 point shots inside the paint
    8. compare the 2 point shos outside the paint 
      
  
8. [environment.yml](environment.yml) and [requirements.txt](requirements.txt):
  -The environment files necessary to recreate the python environment (python 3.6)
    
**DISCLAIMER**
1. The shots are limited to those attempted in the half court
