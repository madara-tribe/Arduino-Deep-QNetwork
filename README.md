# A Arduino  Movement Patterns Learning based on Reinforcement Learning


## Overvier

Hardware(Arduino Uno) of Movement Patterns Learning related Robotics Reinforcement Learning Development

1.I Use Arduino as alternative hardware Uno isetead of real Robotic hardware. My aim was for devlopment of robotics project and develop almost same mecahnism to use that robotic project. 
The robotics project is to develop robots leaning Movement Patterns based on Reinforcement Learning. I participateed the robotics project and develop Movement Patterns Learning system with alternative Hardware(Arduino Uno)



2.The main algorithm for this development is Deep Q-Network(DQN). 
Arduino learned <b>Movement Patterns (Down => Push pump => Up</b>). Afetr Arduino can Push pump action, it get reward just like below.

<img src="https://user-images.githubusercontent.com/48679574/85190320-3fc61f80-b2f2-11ea-86a3-c4db8dbe44a9.jpg" width="450px"><img src="https://user-images.githubusercontent.com/48679574/85190307-1c9b7000-b2f2-11ea-9459-0f632e795d81.jpg" width="450px">




3.Eplisode training cycle almost followed DQN mechanism. I improved mainly value action frunction. 
While leaning Movement Patterns, DQN episode training cycle and value action curve is just like below:

<img src="https://user-images.githubusercontent.com/48679574/85190464-b0ba0700-b2f3-11ea-9a03-141dc373add2.jpg" width="450px"><img src="https://user-images.githubusercontent.com/48679574/85190474-c62f3100-b2f3-11ea-85ba-c5439e0a11ff.png" width="450px">


4.Through 50 episode, num of success become more than 16 in each step.

