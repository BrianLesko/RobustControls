This folder contains projects related to cyclical or repetitive control by Brian Lesko

First Project Added 12/5/22 regarding a repetitive control design learned during study at The Ohio State University in Robust Controls 8352. Written in MATLAB

Previous work:
The Qube servo plant used in this demonstrstion has been studied previously. During this previous work, time and frequency responses have been documented when implementing a variety of controller design methods. First, D-stability, margin bounds, and mixed sensitivity were used to achieve a multi-objective design by producing a controller parameter space. Next, analytical methods were used to produce a lead-lag and then PID controller - where the same procedures were repeated for numerous increases in the plant time constant.
Controls Background:
Repetitive Control is a method to reduce input to output tracking error within a control system that has a periodic refrence or disturbance input with a known period. Repetitive controller use a time delay, which increases difficulty in predicting stability - here, regeneration spectrum <1 is used as a stability condition. A low pass
filter is used to turn off repetitive control at frequencies higher than its bandwidth. Repetitive control has been used for trajectory control of robot arms, cold rolling machining, control of hard disk drives, motor speed control, among many other uses.