# lab06-proceduralFace

Let's practice parameterization! We'll be starting with an oh-so-beautiful gingerbread man face that looks like this:
![image](https://github.com/user-attachments/assets/4707eb0a-b25e-4eda-84e3-3bb336981781)

## Setup
Start by forking [this shadertoy](https://www.shadertoy.com/view/XftyR8)

## Task 1

<img width="300" alt="Screenshot 2024-10-30 at 12 31 44 PM" src="https://github.com/user-attachments/assets/bf4daf82-b194-4eeb-b251-4e515d3c6d67">
<img width="300" alt="Screenshot 2024-10-30 at 12 31 56 PM" src="https://github.com/user-attachments/assets/82f2e77f-3d27-49b8-894b-60a7a069af7e">
<img width="300" alt="Screenshot 2024-10-30 at 12 32 03 PM" src="https://github.com/user-attachments/assets/e0e01e59-b02f-4d47-9b81-aaf791dccb73">

[Link to shadertoy](https://www.shadertoy.com/view/MccyR4)

In the faceSDF function, add a new float parameter called SUPRISE a value between 0 and 1. Copying the way EYE_SEPARATION is used, modify the face such that the gingerbread face looks more or less surprised based on the value of SURPRISE. SURPRISE = 0 should be not very surprised, and SUPRISE = 1.0 should look very surprised. Note that the face shouldn't look broken for any value in that range!
Changing this parameter should change at least 3 geometic attributes of the face and more than one facial feature (just eyebrows are NOT SUFFICIENT).

![image](https://github.com/user-attachments/assets/76d63b1b-f3af-456a-8031-8b8da0abe125)

## Task 3 - EVIL!!!

<img width="300" alt="Screenshot 2024-10-30 at 3 38 16 PM" src="https://github.com/user-attachments/assets/d2c0c8b4-7118-40da-aeca-77fe9197f3d5">
<img width="300" alt="Screenshot 2024-10-30 at 3 38 21 PM" src="https://github.com/user-attachments/assets/063f45a5-66ea-4f7c-a1c5-84b838f89fb3">
<img width="300" alt="Screenshot 2024-10-30 at 3 38 30 PM" src="https://github.com/user-attachments/assets/f353cabb-6ffe-4997-87d5-816831177903">

[Link to shadertoy](https://www.shadertoy.com/view/lfccz4)

Your own parameter! Create a new attribute of your choice that maps to a procedural face characteristic in the domain of [0,1]. It SHOULD NOT be a literal attribute, eg. eye-separation or mouth size, but instead a more qualitative, subjective quality that you tie to specific geometic parameters using your design sense. Have fun!
 
## Submission
- Create a pull request to this repository
- In the README, include the names of both your team members
- In the README, create a link to your shader toy solutions
- Make sure your shadertoy is set to UNLISTED or PUBLIC (so we can see them!)

