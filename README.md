# UFSC-projects
Projects i've done by myself/with team at college

This was a project created in arduino to control the height of and adjustable table by variating the motor shaft, by serial communication with a computational vision.
So the user register in database and set his/her height. then, by computer vision, the user will be automatically recognized and the table will adjust to its height, 
thus maintaining ergonomics in the work area. This works for each new registered user who is going to make use of the automatic adjustment workbench.

By knwing the screw turns ratio and the steps of the stepper motors that we've been using, it could be easily created a relation between rotation and height variation,
and that's how the arduino algorithm controls the stepper motors and consequently the height of the table.
