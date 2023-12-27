# About me

# Past Projects

## Cart Pole System Controller Design/Analyses

**Goal:** Create a simulation of a cart pole system to then design, test, and evaluate different controllers and state estimation techniques.

**Skills:** Control Systems, Linear Quadtratic Regulator, Kalman Filtering, Simulation, MATLAB

**Summary:** Created a simulation in MATLAB to accurately represent the systems nonlinar dynamics with injected process/sensor noise. Implemented a Kalman filter as a method of state estimation to then be used as a controller input. Created 2 Linear Quadtratic Regulators and a 2-stage PD controller capable of performing set-point control for this system. Ran a Monte-Carlo style simulation to evaluate and validate the 3 controllers. Project completed individualy as a final project submission for RBE 502 - Robot Control at WPI.

**Link:** [Cart-Pole Repository](https://github.com/pjcrann219/Cart-Pole)

## Lunar Lander DQN
**Goal:** Train a Deep Q Net to control OpenA gym's LunarLander envirnment.

**Skills:** Python, Reinforcement Learning, Deep-Q-Net, PyTorch

**Summary:** Used a fully conected, 3 layer neural net to approximate action values. Incorporated action-replay for more efficient and stable training. Obtained a policy capable of controlling the lander in a satisfactory manner. Completed individual as my final project for RBE 595-ST Reinforcement Learning at WPI.

**Link:** [LunarLander DQN Repository](https://github.com/pjcrann219/LunarLander-DQN)

## Ball Balancing Platform

**Goal:**  Develop a system capable of balancing a ball on a tilting platform. 

**Skills:** C++, Microcontrollers, Sensors/Motors, Python, OpenCV, Image Processing, PID Control

### Version 1

**Summary:** As part of my Mechatronics course at UMass Amherst, and in collaboration with 2 other students, wwe built a rapid prototype using a 4-wire resistive touch screen, arduino, servo motors, and 3D printed/ scrap parts. Implemented PD control to control the servo angles and successfully controlled the ball. Despite successfully balancing the ball, time and cost limitations left much room for improvement in terms of structural integrity, control stability, and sensor reliability.

**Link:** [BallBalanceV1 Repository](https://github.com/pjcrann219/BallBalanceV1)

### Version 2

**Summary:** As a personal project, I iterated the above work and developed an improved system. Replaced touch screen with an overhead webcam, redesigned 3D printed joints, and moved processing off microcontroller (due to image processing needs).

**Link:** [BallBalanceV2 Repository](https://github.com/pjcrann219/BallBalanceV2)
