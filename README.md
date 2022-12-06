# Coding-one_Ziyi-Yu_22014089
This is the final assignment for Ziyi Yu(22014089).

Project Description


<img width="1425" alt="截屏2022-12-06 01 45 43" src="https://user-images.githubusercontent.com/119879045/205788460-b4c77cf8-4e64-4641-b2c1-7a554d9c8d64.png">


Project Name: CyberFaith

INTRODUCTION
This is a real-time interactive code project that controls the animation of 3D images through Mimetic risk on the MIMIC platform. You will need to obtain your microphone permissions when opening this file. To better experience the work, turn the sound outside and adjust it to a medium volume (you will hear some ambient noise and the sound you are making after computer processing).
![1](https://user-images.githubusercontent.com/119879045/205789241-a0d77640-d4f0-4c49-b371-6d6c451b9f15.png)
           Some pictures of Buddha statues.

![木鱼2](https://user-images.githubusercontent.com/119879045/205790378-689074f2-dacc-41f0-adf6-18327a83643c.png)
           Some pictures of the "wooden fish" used by monks in Buddhist culture.


INSPIRATION
The concept for the project comes from an app called Electronic Muyu, which has recently become popular among young people in China. As a typical religious article, Muyu expresses Buddhist culture to a certain extent. Nowadays, some young people, when facing heavy pressure, will tap the screen of mobile phone, ipad, iwatch and other electronic devices to simulate the action of tapping the real wooden fish. Their behavior can be seen as the cyberization of religion.


I used 3D spheres to simulate the shape of Buddhist beads and added some textures and materials with religious significance to them. I tried to control the animation effect of 3D graphics through the ambient noise and human speaking voice collected by the microphone.


PART ONE
Obtain microphone permission. This part of the code through the analysis of the computer microphone collected environmental noise and human voice, to output data. I define a global variable of Window.variable and get the value of the data update. The sound collection system is controlled by a button, and when the PLAY button is pressed, the sound begins to interact with the 3D image, and the button says STOP. When the STOP button is pressed, the sound stops interacting with the 3D image. The 3D scene remains in its current position.


PART TWO
This part of the code mainly sets up a 3D scene and draws 3 large spheres and 9 small spheres. These spheres are placed in different positions and rotate at different angles and directions. When the microphone is not on, the nine small spheres are arranged in a matrix state. When the microphone is turned on, the values of the 9 small spheres are controlled by the global variable Window.variable, and the animation and dynamic visual effect are like a string of Buddhist beads.


THE ANALYSIS
In this project, I mainly used the sound and 3D knowledge involved in this semester's courses. In the process of creation, I also made some attempts on shader, but unfortunately, I did not finish the final effect. In the animation design, due to the use of fewer models so that the picture does not look very full. This project only uses some of the simplest codes. In the following study, I hope to continue to explore the use of matrix in 3D environment, reference and use of 3D models and other knowledge.

