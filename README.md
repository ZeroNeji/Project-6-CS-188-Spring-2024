# Project-6-CS-188-Spring-2024

This project comes from cs 188 Spring 2024 UCS Berkeley. In this project, we work on the 7 questions from the project. The four files that were edited to solve those questions are valueIterationAgents.py, qlearningAgents.py, analysis.py, and model.py. This project runs on python.

# Commands
These are some of the commands that you can use in this project.
To check whether the questions in the project were passed. You can run python `autograder.py -q q[questionnumber]` .As an example, `python autograder.py -q q1` runs the autograder for question 1. This command can run the autograder for all questions: `python autograder.py` .\
The following command can be used to run the valueIterationAgent:  
 <list>
+ `python gridworld.py -a value -i 100 -k 10`
+ `python gridworld.py -g DiscountGrid -a value --discount [YOUR_DISCOUNT] --noise [YOUR_NOISE] --livingReward [YOUR_LIVING_REWARD]`
  + You can change the discount, noise, and livingreward to see how changes in these variables affect the valueIterationAgent.
 

 <list>
The Q-Learning commads are:<br/> 

   
   - `python gridworld.py -a q -k 100`
   - `python gridworld.py -a q -k 100 --noise 0.0 -e 0.1`
     - By changing e, you can change the episolon value.
   - `python crawler.py`
     - This runs the crawler. It has it's own GUI to try out different values for its variables.
   - `python pacman.py -p PacmanQAgent -x 2000 -n 2010 -l smallGrid`
     - This command trains the pacman agent in a small grid maze for 2000 episodes. If you want to see the agent while it's training, you can use `python pacman.py -p PacmanQAgent -n 10 -l smallGrid -a numTraining=10`


The Approximate Q-Learning commands are listed below. These all train the pacman agent in mazes.\
<list>
 + `python pacman.py -p ApproximateQAgent -x 2000 -n 2010 -l smallGrid` 
 + `python pacman.py -p ApproximateQAgent -a extractor=SimpleExtractor -x 50 -n 60 -l mediumGrid`
 + `python pacman.py -p ApproximateQAgent -a extractor=SimpleExtractor -x 50 -n 60 -l mediumClassic`
<list>

For Deep Q-Learning, you can only see it by checking q7 with the autograder.\

We spent time working through all 7 questions. We managed to get the first 6 by ourselves. While we did try to solve q7 on our own, we couldn't solve it ourselves in time. To show case the demo for it, we got code online, as allowed based on the instructions. The code from model.py comes from [Minjun Kim](https://github.com/nninjun/2024-Spring-CS188). It can be found in the project 6 folder.
