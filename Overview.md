# MANSEDS Lunar Rover 2017

## The Project

In the academic year 2016/17, students from the University of Manchester worked on a project ran by UKSEDS to design and build a lunar rover. The objectives being to produce a preliminary design report, followed by a critical design report which was then defended in an interview with system engineers at Thales Alenia. Finally, upon being passed at each of these stages, the project was given funding to build the designed rover and take it to a competition at RAL Space.

## The Competition

The competition was composed of three stages. The first, to direct the rover from the top of a crater to its bottom, collect 500g of ice samples and to return to the starting position. Secondly, to be put through a one-dimensional equivalent of the vibration tests that real extraterrestial rovers are subject to during their development. Finally to repeat the first stage as best as possible given any damage incurred during the vibration testing.

## The Design

The rover design had several key systems; a robotic arm, robotic scoop, remote control via a web interface, multiple on-board cameras, and inertial & proximity sensors, and a per-wheel motor solution. The robotic arm consisting of three segments and multiple servos giving it many degrees of freedom - its control intended via joysticks and inverse kinematics. The control system was intended to function via commands being staged in the web interface, before being submitted to an executor service on the rover which would sequentially enact these commands via a series of backend scripts that control specific PWM and GPIO channels. The cameras and other sensors on board would provide feedback to a human controller as well as provide automated actions such as halting the rover upon detecting obstacles. The choice of wheels and individual motor control was intended to ensure the best traction possible given the lunar surface is (almost) all regolith - and so roughly equivalent to arid off-road conditions on Earth.

## The Build

Not all of the design was realised in the final build before the competition, however none of these actually led to insurmountable conditions for the rover. The systems missed being the robotic scoop and a finalised web inteface. The biggest failings were due to missing two of the four motors of a certain torque (the two missing motors being replaced with lower torque alternatives) and inadequate wiring. The wiring constraining arm motion and being of insufficient gauge to easily carry the current required for the motors and servos.

## The Future

The current work completed has yielded a working rover, and has allowed those involved to develop their skills tremendously. It is hoped any teams who encounter this repository may benefit from our experience, though the most direct intention is to use this documentation in conjuction with continued support from MANSEDS to give future undergraduates at UoM a chance to develop their skills in electronics, programming, systems design and mechanical engineering.

Plenty can yet be done to make this rover even better, and a very concrete analysis is provided in this repository exploring the biggest weak points in the final 2017 design of the rover. We hope anyone who does undertake a similar project may avoid such mistakes in light of our experience.
