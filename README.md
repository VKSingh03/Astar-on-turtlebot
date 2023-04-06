# ENPM 661 Project 3 Phase 2

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

- [`phase2map1.py`](phase2map1.py) - Contains the implementation of Astar algorithm to solve the path planning problem.
  + The program will run a A* algorithm for path planning and create a video. This video will be saved after execution as Astar01.avi.
  + Once the program runs  completetly it will show  a image output of optimum path.
  + Press enter once the image is shown this will complete the video recording
  + The program will ask the user to give the inputs for start and goal and check wheter it is valid.
  + Selecting Robot Clearance values and Object Clearance values above 5 will make the right most area on the map inaccessible. 

- [`Astar_turtlebot.py`](Astar-turtlebot.py) - Contains the implementation of Astar algorithm to solve the path planning problem.
  + The program will run a A* algorithm for path planning and create a video of the entire node generation. This video will be saved after execution as Astar02.avi.
  + Once the program runs  completetly it will show  a image output of optimum path.
  + Press enter once the image is shown this will complete the video recording
  + The program will ask the user to give the inputs for start and goal and check wheter it is valid.


Note: The output videos in both cases is created as .avi which is converted to .mp4 using another software.

  To test any other initial state and goal state, provide the states to --InitState and --GoalState parameter while running the code (x y theta). 

  The canvas size is 600\*200 for the map in Astar_turtlebot.py
  The canvas size is 600\*250 for the map in phase2map1.py
  The inputs of initial and goal nodes should be given in Cartetsian Coordinates, and Step size between 1 to 10. 

## How to Run the Program:

To run the program, open the command prompt/terminal and navigate to the directory where the above source code files are located. To run **phase2pam1.py**, type the following command: 

>Test case 1:
    
    python3 phase2map1.py --InitState 30 30 45 --GoalState 550 125 0

Enter the values for Robot Clearance, Object Clearance, Step Size, Left wheel RPM (RPM1), and Right wheel RPM (RPM2) when prompted by the code.  

Output Video: https://youtu.be/aVWabf8XAkY

>Test case 2:
    
    python3 phase2map1.py --InitState 30 30 45 --GoalState 120 125 0


To run **AStar_turtlebot.py**, open the command prompt/terminal and navigate to the directory where the source code files are located. Then, type the following command: 

>Test Case 1: 

    python3 Astar_turtlebot.py --InitState 0 0 0 --GoalState 4.8 -0.5 0

Enter the values for Robot Clearance, Object Clearance, Left wheel RPM (RPM1), and Right wheel RPM (RPM2) when prompted by the code.  

>Values chosen for each parameter for Test Case 1:  
+ Enter Robot Clearance: 20
+ Enter Object Clearance: 5
+ Enter RPM1 (Left wheel RPM): 10
+ Enter RPM2 (Right wheel RPM): 15

Output Video: https://youtu.be/pela1_hRaCk

>Test Case 2: 
    
    python3 Astar_turtlebot.py --InitState 0 0 0 --GoalState 5.2 0.8 0


Note: 

ROS Link: https://youtu.be/8U9iF_QIr0E

## Github Link
[Repository](https://github.com/VKSingh03/Astar-on-turtlebot.git)

## Video Output
[Output Video for map1](Astar01.mp4)




