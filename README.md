# Name: Christine Kneer

[Shadertoy Link](https://www.shadertoy.com/view/4c3cRN)

## Task 1: SURPRISE

|![normal](https://github.com/user-attachments/assets/36779073-6483-42f3-bfb2-b1ac9e5b6443)|![0.5](https://github.com/user-attachments/assets/00e61483-fa7d-4f14-9e09-ef38fc4860dd)|![1.0](https://github.com/user-attachments/assets/fcbc7b62-0567-4282-9961-861dc707fb13)|
|:--:|:--:|:--:|
|*SURPRISE = 0*|*SURPRISE = 0.5*|*SURPRISE = 1.0*|


## Task 2: SADNESS

|![normal](https://github.com/user-attachments/assets/36779073-6483-42f3-bfb2-b1ac9e5b6443)|![0.5](https://github.com/user-attachments/assets/46430b53-f8fe-4c52-8abb-1104d6fff6b0)|![1.0](https://github.com/user-attachments/assets/ad890568-ef74-46d7-af5c-9c1e83de8fbe)|
|:--:|:--:|:--:|
|*SADNESS = 0*|*SADNESS = 0.5*|*SADNESS = 1.0*|

## Task 3: MADNESS

|![normal](https://github.com/user-attachments/assets/36779073-6483-42f3-bfb2-b1ac9e5b6443)|![0.5](https://github.com/user-attachments/assets/d2b680b8-d95b-40e4-a0e3-11326c5df64e)|![1.0](https://github.com/user-attachments/assets/8fdeb0a8-6494-4825-9361-df395501d15d)|
|:--:|:--:|:--:|
|*MADNESS = 0*|*MADNESS = 0.5*|*MADNESS = 1.0*|

## BONUS IMAGE
|![bonus](https://github.com/user-attachments/assets/d5f4d478-6035-4ab4-b791-2481c1e4ca7f)|
|:--:|
|*SURPRISE = 1, SADNESS = 1, MADNESS = 1*|

# lab06-proceduralFace

Let's practice parameterization! We'll be starting with an oh-so-beautiful gingerbread man face that looks like this:
![image](https://github.com/user-attachments/assets/4707eb0a-b25e-4eda-84e3-3bb336981781)

## Setup
Start by forking [this shadertoy](https://www.shadertoy.com/view/XftyR8)

## Task 1
In the faceSDF function, add a new float parameter called SUPRISE a value between 0 and 1. Copying the way EYE_SEPARATION is used, modify the face such that the gingerbread face looks more or less surprised based on the value of SURPRISE. SURPRISE = 0 should be not very surprised, and SUPRISE = 1.0 should look very surprised. Note that the face shouldn't look broken for any value in that range!
Changing this parameter should change at least 3 geometic attributes of the face and more than one facial feature (just eyebrows are NOT SUFFICIENT).

![image](https://github.com/user-attachments/assets/76d63b1b-f3af-456a-8031-8b8da0abe125)

## Task 2
In the faceSDF function, create a new float parameter called SADNESS. Follow the same guidelines as outlined in Task 1.

## Task 3
Your own parameter! Create a new attribute of your choice that maps to a procedural face characteristic in the domain of [0,1]. It SHOULD NOT be a literal attribute, eg. eye-separation or mouth size, but instead a more qualitative, subjective quality that you tie to specific geometic parameters using your design sense. Have fun!
 
## Submission
- Create a pull request to this repository
- In the README, include the names of both your team members
- In the README, create a link to your shader toy solutions
- Make sure your shadertoy is set to UNLISTED or PUBLIC (so we can see them!)

