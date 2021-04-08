# SRC robot (Self driving RC Car)
## Fully hand-made metal mobile robot
As [Self Driving robot Engineer] I made fully hand-made metal Self Driving RC car.

![SRC-B1 hw overview](https://user-images.githubusercontent.com/32663016/114103450-1ec3cf00-9904-11eb-9560-2d96f6660764.png)

Configuration!
- Main Controller: Latte panda(Window or Ubuntu), Raspberry pi
- Sub Contoller: Arduino > motor, light, LED dot matrix control
- IMU (AHRS): Heading direction check
- Lidar: Emergency stop, collision avoidance
- Camera: Lane detection, Machine Learning (Object detection)
- Speaker: Connection beep, Alarm, Music(wav)
- Light: 12 LED for light / mode check, night driving test

## Theory
- Steering: pure pursuit and PID control
- GNSS: RTK fixed or float mode setting (RTCM message) using NTRIP client
- Waypoint: Using GPX route editor, easy to make and modify waypoint for driving
- Model: I'm testing DQN logic to apply driving algorism 

## Type

![SRC-BC](https://user-images.githubusercontent.com/32663016/114103638-73ffe080-9904-11eb-9f0f-82286d8f09cf.png)