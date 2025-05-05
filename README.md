![Screenshot 2025-05-05 143817](https://github.com/user-attachments/assets/662bfb68-6e87-4795-8dfa-ca710161dba2)# Lab-Ex.-No---7-Execute-a-program-for-Straight-line-and-Circular-interpolation-in-Doosan-Industrial-cobot
## Aim : To Execute a program for Straight-line and Circular interpolation in Doosan Industrial Cobot using DRL studio.

## Components Required:

*Doosan Industrial Collaborative Robot

*DRL (Doosan Robotics Language) Studio Software

### Theory 
INTERPOLATION

Interpolation, which is necessary for any type of programming, consists of generating data points between given coordinate axis positions. Within the Machine Control Unit (MCU), a device called an interpolator causes the drives to move simultaneously from the start to the end of the command. The interpolator is either an electronic hardware device for a NC system, or a software program for a CNC system. An interpolator provides two functions:

It calculates individual axis velocities to drive the tool along the programmed path at the given feed rate.

It generates thousands of intermediate coordinate points along the programmed path between the start point and the end point of the cut.

During positioning, all programmed axes move simultaneously at the specified feed rates until each axis has reached its destination. All drives start together, but without an interpolator individual destinations are reached successively according to the path traveled. However, an interpolator coordinates these axis motions in such a way that the programmed path is constantly maintained from the beginning to the end of the movement.

Linear and circular interpolation are most commonly used in CNC programming applications:

Linear interpolation is used for straight-line machining between two points.

Circular interpolation is used for circles and arcs.

Helical interpolation, used for threads and helical forms, is available on many CNC machines.

Parabolic and cubic interpolation are used by industries that manufacture parts having complex shape such as aerospace parts, and...

## Procedure:

Manipulate the end effector as per the given configuration. Movement Should Initiate in P1 and progress till the end point. Travel path should be in sequence as stated below.
output

![Screenshot 2025-05-05 143735](https://github.com/user-attachments/assets/8e59e5f8-27c3-4ebe-833f-644b42b42376)


![Screenshot 2025-05-05 143746](https://github.com/user-attachments/assets/4231b4d7-b9c5-4998-ac63-32062d940789)


![Screenshot 2025-05-05 143753](https://github.com/user-attachments/assets/348c1809-7b09-49ba-a8e4-cd7edb1bff39)


![Screenshot 2025-05-05 143802](https://github.com/user-attachments/assets/4182b54d-1604-4596-9834-3706c7836f5d)


![Screenshot 2025-05-05 143809](https://github.com/user-attachments/assets/ba3c9275-0664-43b8-851f-291c22b0941d)




Linear Interpolation


![Screenshot 2025-05-05 143817](https://github.com/user-attachments/assets/9067a527-60e9-47d1-8a9f-d873c7c22704)




Circular Interpolation



![Screenshot 2025-05-05 143824](https://github.com/user-attachments/assets/7e77ce31-befb-42a2-9603-fb245ff5e683)




### Results 

A program for Straight-line and Circular interpolation in Doosan Industrial Cobot using DRL studio has been executed successfully.



 
