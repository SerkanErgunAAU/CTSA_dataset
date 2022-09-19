# CTSA_dataset

This dataset contains the results of all grasp experiments and 3D files of all test object used.

## Grasp experiments
Contains the capacitive map for each grasp experiment after touching and firmly gripping. Each experiment has its unique ID and states if the task succeeded or failed. In case of failure, the last state of the robot (touching, gripping, lifting, moving) will be stated.
The folder Tables containes a latex style table of the overview of all experiments of one object - using the same style as in the paper.

## Test objects

The folder Test objects contains *.stl or *.obj files of all test objects.
The following test objects were taken from the EGAD training set [1].

our naming	naming in [1]
Amber		G10_3.obj
Beryl		M25_2.obj
Diamond     J14_2.obj
Emerald	B09_2.obj

Objects Cube, Cuboid, Cylinder, Coral

Sources:
[1] D. Morrison, P. Corke, and J. Leitner, “Egad! an evolved grasping anal-
ysis dataset for diversity and reproducibility in robotic manipulation,”
IEEE Robotics and Automation Letters, vol. 5, no. 3, pp. 4368–4375,
2020