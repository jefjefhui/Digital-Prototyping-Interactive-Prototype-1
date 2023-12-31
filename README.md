# Digital-Prototyping-Interactive-Prototype-1

Background information of the projects(Problem space): Most of us have experienced long distance driving, and we know long distance driving can drain your energy easily. The longer you drive, the more fatigue you can feel. Fatigue driving can affect a driver's concentration, which can lead to traffic accidents easily. Fatigue driving is a big issue for everyone, and we need to treat it seriously.To resolve this problem, developing a driver alert system is needed. The driver alert system needs to collect some input data. Afterwards, the system needs to process the input data and provide corresponding feedback to the driver. The system needs to analyze the data precisely, and provide the most suitable feedback that fits the driver’s current condition. The details of the feedback mechanisms are explained within the statement of delivery document. By having the driver alert system, drivers can stay awake and focus on the road when they drive, so that they can keep themself safe.

Introduction of the Interactive prototype projects: The background information above briefly explains the problem we want to solve and the potential solution. In the interactive prototype projects, the goal is not building the actual product and deploying the system to the public. The focus of the interactive prototype projects are treating the problem and the  solution mentioned above as the concept, and I need to explore the challenge/aspect within the concept afterwards. 
After the challenge/aspect is defined, the interactive prototype project will enter its second stage, which is the prototype development.
The prototype development has two parts, which are the hardware and the software. For the hardware, I used the Adafruit Circuit Playground as the physical component, which is used for the physical interaction between the system and the users. For the software, I used Unity to develop the software prototype. The hardware component will communicate with the software prototype constantly. The digital prototype is specifically designed for the challenge/aspect that we defined in the previous stage. Once the digital prototype development is completed, the testing session will begin.
The final stage is the testing session. In the testing session, I will explain the concept to my testers. Afterwards, they will perform some operations with the digital prototype. I will conduct various evaluations throughout the testing session, for instance observations and interviews. These evaluations can give me useful insights on the challenges/aspects that I defined in the earlier stage, so that I will have a clear direction in my future developments. 

The interactive prototype project has three digital prototypes. Each of these prototypes is corresponding to a specific challenge/aspect on the problem space we mentioned earlier.

The coding folder contains the Arduino codes and the Unity codes.

The statement of delivery contains the documentation of the digital prototype and the testing session information.

The ReadMe.md provides background information and explains the flows of the interactive prototype. In addition, it will have a detailed explanation on the target challenge/aspect, and its digital prototype.


Prototype 1

In prototype 1, the research idea is “Does progressive feedback mechanism perform better than the single feedback mechanism in the driver alert system concept?” Progressive feedback system means the severity of the feedback has positive correlation with the fatigue level of the driver. If the driver’s fatigue level is low, the severity of the feedback will be low. Otherwise, the severity of the feedback will be high. Single feedback mechanism means there is only one level of feedback and it applies to all scenarios. 
I developed a car simulation game to find out the answer for this research aspect. In the car simulation game, the player needs to use the keyboard to control the vehicle, and drive the vehicle from the starting point to the ending point. There are a lot of obstacles between the starting point and the ending point, the driver needs to avoid hitting those obstacles. If the player hits the obstacles, there will be sound feedback. Every subsequent collision will result in higher volume of the sound feedback. If the hitting time reaches the maximum point, the game will end. Hitting time is the determinant of the feedback severity, which demonstrates how the progressive feedback system looks like.
This interactive prototype will be tested during the testing session. Testers will play the game. Afterwards, evaluations will be performed. After the evaluation, I realized most testers prefer progressive feedback system, since they believe increasing the intensity gradually can differentiate the difference between different feedbacks and it provides a better user experience as well. For further development, I can modify the progressive feedback system and make it more precise, for instance, adding more levels in the progressive feedback system.The useful insights from the evaluation can be used to resolve the research idea.


![img(1)](https://github.com/jefjefhui/Digital-Prototyping-Interactive-Prototype-1/assets/73283123/5c63345a-4cf2-4cf7-b1d4-e0811bda67be)

The image above is the setting of the prototype. I used 3D objects in Unity to create the setting.The 3D objects include plane, cube, and cylinder.

![img(2)](https://github.com/jefjefhui/Digital-Prototyping-Interactive-Prototype-1/assets/73283123/f5ee9abd-dc4d-4e17-8c51-38d301a26913)

The image above is the completed prototype. As it shows, the car is at the yellow area, which is the starting line. The car needs to get to the red area without hitting any 3D obstacles in the setting.


![img(3)](https://github.com/jefjefhui/Digital-Prototyping-Interactive-Prototype-1/assets/73283123/730ff0b1-da8d-4d56-9d2a-2c266c9649c5)

The image above shows what you can see after pressing the start button. I adjusted the coordinate of the main camera, which gives tester a first-person point of view when driving the car. I believe this will give a better angle to testers when they test my prototype.


![img(4)](https://github.com/jefjefhui/Digital-Prototyping-Interactive-Prototype-1/assets/73283123/f4999fe5-c036-45cf-8e87-d99482b84309)

The image above is a diagram which shows the interaction between the testers and the prototype. This diagram shows how feedbacks change when hitting times change. This diagram shows how the progressive feedback system works in the simulation.


Detailed information of prototype 1,background information , testing session, and key takeaways can be found in the statement of delivery.

The following link shows the prototype 1 video, which demonstrates how interactive prototype 1 works: https://www.youtube.com/watch?v=ESvUNyNtF3w



