# ENPM 661

## A* ALGORITHM with Differential Drive constraints

### Student Names
- Shantanu Parab
- Vineet Singh

### Directory ID & UID
- sparab - 119347539
- vsingh03 - 119123614

## Libraries used are: 
>numpy, argparse, timeit, queue, OpenCV, math 

## Source Code Files
- [`Astar_turtlebot.py`](Astar-turtlebot.py) - Contains the implementation of Astar algorithm to solve the path planning problem.
  + The program will run a A* algorithm for path planning and create a video. This video will be saved after execution as Astar02.avi.
  + Once the program runs  completetly it will show  a image output of optimum path.
  + Press enter once the image is shown this will complete the video recording
  + The program will ask the user to give the inputs for start and goal and check wheter it is valid.

  

- [`phase2map1.py`](phase2map1.py) - Contains the implementation of Astar algorithm to solve the path planning problem.
  + The program will run a A* algorithm for path planning and create a video. This video will be saved after execution as Astar01.avi.
  + Once the program runs  completetly it will show  a image output of optimum path.
  + Press enter once the image is shown this will complete the video recording
  + The program will ask the user to give the inputs for start and goal and check wheter it is valid.

Note: The output video is created as Astar01.avi which is converted to mp4 using another software.

  To test any other initial state and goal state, provide the states to --InitState and --GoalState parameter while running the code (x y theta). 

  The canvas size is 600\*200 for the map in Astar_turtlebot.py
  The canvas size is 600\*250 for the map in phase2map1.py
  The inputs of initial and goal nodes should be given in Cartetsian Coordinates, and Step size between 1 to 10. 

## How to Run the Program:

To run the program, open the command prompt/terminal and navigate to the directory where the source code files are located. Then, type the following command: 

    python3 phase2map1.py --InitState 30 30 45 --GoalState 120 125 0

Enter the values for Robot Clearance, Object Clearance, Step Size, Left wheel RPM (RPM1), and Right wheel RPM (RPM2) when prompted by the code.  

>Test case 2:
    python3 Astar_turtlebot.py --InitState 30 30 45 --GoalState 550 125 0


To run the AStar_turtlebot.py, open the command prompt/terminal and navigate to the directory where the source code files are located. Then, type the following command: 

    python3 Astar_turtlebot.py --InitState 30 30 45 --GoalState 200 125 0

Enter the values for Robot Clearance, Object Clearance, Step Size, Left wheel RPM (RPM1), and Right wheel RPM (RPM2) when prompted by the code.  

>Test case 2: 
    python3 Astar_turtlebot.py --InitState 30 30 45 --GoalState 550 125 0




## Github Link
[Repository](https://github.com/VKSingh03/Astar-on-turtlebot.git)

## Video Output
[Output Video for map1](Astar01.mp4)
[Output Path for map2](Output_differnetial.png)




