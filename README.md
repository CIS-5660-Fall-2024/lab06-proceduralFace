# lab06-proceduralFace

name: Crystal Jin

link: https://www.shadertoy.com/view/4ctcRN

Task1: Suprise

<img width="613" alt="fdb67ede1fc4cbd42e0a00ddd8d5df5" src="https://github.com/user-attachments/assets/74b8fbe8-cd4a-4f5e-ad91-53bfe48f5101">

Task2: Sleepy

<img width="563" alt="7d9d5eb5afba439a80c03a81304537e" src="https://github.com/user-attachments/assets/e97175a0-2745-4b6b-b170-dc84bc7db6fb">

Task3: Madness

<img width="608" alt="c1dc40384ef05de5c5e47cce9a35b5b" src="https://github.com/user-attachments/assets/b08e0eb8-2773-4882-8572-198697e50d31">


Let's practice parameterization! We'll be starting with an oh-so-beautiful gingerbread man face that looks like this:
![image](https://github.com/user-attachments/assets/4707eb0a-b25e-4eda-84e3-3bb336981781)

## Setup
Start by forking [this shadertoy](https://www.shadertoy.com/view/XftyR8)

## Task 1
In the faceSDF function, add a new float parameter called SUPRISE a value between 0 and 1. Copying the way EYE_SEPARATION is used, modify the face such that the gingerbread face looks more or less surprised based on the value of SURPRISE. SURPRISE = 0 should be not very surprised, and SUPRISE = 1.0 should look very surprised. Note that the face shouldn't look broken for any value in that range!
Changing this parameter should change at least 3 geometic attributes of the face and more than one facial feature (just eyebrows are NOT SUFFICIENT).

![image](https://github.com/user-attachments/assets/76d63b1b-f3af-456a-8031-8b8da0abe125)

## Task 2
Your own parameter! Create a new attribute of your choice that maps to a procedural face characteristic in the domain of [0,1]. It SHOULD NOT be a literal attribute, eg. eye-separation or mouth size, but instead a more qualitative, subjective quality that you tie to specific geometic parameters using your design sense. Have fun!

## Extra Credit
In the faceSDF function, create a new float parameter called SADNESS. Follow the same guidelines as outlined in Task 1.
 
## Submission
- Create a pull request to this repository
- In the README, include the names of both your team members
- In the README, create a link to your shader toy solutions
- Make sure your shadertoy is set to UNLISTED or PUBLIC (so we can see them!)

