# About me
[Linkedin](https://www.linkedin.com/in/paulcrann) | pcrann@gmail.com

Current Masters Student at Worcester Polytechnic Institute in Robotics Engineering

# Highlighted Work

## Traffic Sign Classification Using Convolutional Neural Networks

**Goal:** Develop a convolutional neural network (CNN) to classify traffic signs in unmapped environments to ensure autonomous vehicles obey road rules.

**Skills:** Convolutional Neural Networks, Deep Learning, Image Classification, Data Augmentation, Python, PyTorch

**Summary:** Utilized the road sign imagess from the GRSTB dataset to classify traffic signs into five classes: stop signs, caution signs, crosswalk signs, traffic lights, and speed limit signs. Constructed a CNN with three convolutional layers, each followed by max pooling, batch normalization, ReLU activation, and dropout to prevent overfitting. The model also included two fully connected layers for final classification. Implemented the model using PyTorch and optimized it with Adam optimizer and cross-entropy loss. Trained the model achieving over 90% accuracy on the testing data. Project completed as part of a self-directed group study on deep learning for autonomous systems.

![Diagram2](https://github.com/user-attachments/assets/b73fdedc-ba06-4599-a534-eb248afd9251)


**Link:** [Traffic Sign Classification Repo](https://github.com/pjcrann219/CS-539-RoadSignDetection)

## Cart Pole System Controller Design/Analyses

**Goal:** Create a simulation of a cart pole system to then design, test, and evaluate different controllers and state estimation techniques on.

**Skills:** Control Systems, Linear Quadtratic Regulator, Kalman Filtering, Simulation, MATLAB

**Summary:** Created a simulation in MATLAB to accurately represent the systems nonlinar dynamics with injected process/sensor noise. Implemented a Kalman filter as a method of state estimation to then be used as a controller input. Created 2 Linear Quadtratic Regulators and a 2-stage PD controller capable of performing set-point control for this system. Ran a Monte-Carlo style simulation to evaluate and validate the 3 controllers. Project completed individualy as a final project submission for RBE 502 - Robot Control at WPI.

| Gif  | Plots |
| ------------- | ------------- |
| ![lqr1 copy](https://github.com/pjcrann219/pjcrann219/assets/48891310/daba171a-2ad1-4b34-8bcd-a04863d1b555)  | ![lqr1](https://github.com/pjcrann219/pjcrann219/assets/48891310/8dfb2fd5-0ac2-42c1-91bf-7f801509ae92)  |

**Link:** [Cart-Pole Repository](https://github.com/pjcrann219/Cart-Pole)

## Lunar Lander DQN
**Goal:** Train a Deep Q Net to control OpenA gym's LunarLander envirnment.

**Skills:** Python, Reinforcement Learning, Deep-Q-Net, PyTorch

**Summary:** Used a fully conected, 3 layer neural net to approximate action values. Incorporated action-replay for more efficient and stable training. Obtained a policy capable of controlling the lander in a satisfactory manner. Completed individual as my final project for RBE 595-ST Reinforcement Learning at WPI.

![finalTrial](https://github.com/pjcrann219/pjcrann219/assets/48891310/65164a6e-6fe8-4aea-81d6-153b0e85ed9a)


**Link:** [LunarLander DQN Repository](https://github.com/pjcrann219/LunarLander-DQN)

## Ball Balancing Platform

**Goal:**  Develop a system capable of balancing a ball on a tilting platform. 

**Skills:** C++, Microcontrollers, Sensors/Motors, Python, OpenCV, Image Processing, PID Control

### Version 1

**Summary:** As part of my Mechatronics course at UMass Amherst, and in collaboration with 2 other students, we built a rapid prototype using a 4-wire resistive touch screen, arduino, servo motors, and 3D printed/ scrap parts. Implemented PD control to control the servo angles and successfully controlled the ball. Despite successfully balancing the ball, time and cost limitations left much room for improvement in terms of structural integrity, control stability, and sensor reliability.

https://github.com/pjcrann219/pjcrann219/assets/48891310/75159b9a-b943-4fad-bec0-3a0534a2d430

**Link:** [BallBalanceV1 Repository](https://github.com/pjcrann219/BallBalanceV1)

### Version 2

**Summary:** As a personal project, I iterated the above work and developed an improved system. Replaced touch screen with an overhead webcam, redesigned 3D printed joints, and moved processing off microcontroller (due to image processing needs).


https://github.com/pjcrann219/pjcrann219/assets/48891310/7d82b208-4fb9-4f6a-ad38-f7d463fbe65f


**Link:** [BallBalanceV2 Repository](https://github.com/pjcrann219/BallBalanceV2)
