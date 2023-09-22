# Controlling behavior in animals and robots
This repository contains multiple resources related to the final project of the course "Controlling behavior in animals and robots" (taught by Professor P. Ramdya), attended in the Spring semester of 2023 at EPFL. The project has been done in cooperation with Alaa Aboud and Flore Munier-Jolain.

The final project consisted in implementing three different controllers (CPG-based, rule-based, and hybrid) to control the locomotion of a virtual fly. The fly simulation was based on the MuJoCo physics engine, and the biomechanical model allowing to simulate Drosophila melanogaster’s behavior is called NeuroMechFly (Victor Lobato-Rios et al., Neuromechfly, a neuromechanical model of adult drosophila melanogaster. Nature Methods, 05 2022). In the picture below, an artistic representation of Drosophila melanogaster (source: DataBase Center for Life Science (DBCLS), CC BY 4.0, via Wikimedia Commons) is shown.
![Drosophila melanogaster](/Images/Fruitfly.png)

The controllers implemented are based on very different approaches, leading to different walking behaviours that have been analysed and described in the report.

The following resources are present in the repository:
- [CPG submission folder](/SUBMISSION_CPG/), containing all the files (videos showing the walking behaviour of the virtual fly, and notebooks with the proposed approach) related to the CPG-based controller;
- [Hybrid submission folder](/SUBMISSION_HYBRID/), containing all the files (videos showing the walking behaviour of the virtual fly, and notebooks with the proposed approach) related to the hybrid controller (trained considering Reinforcement Learning);
- [Rule-based submission folder](/SUBMISSION_RULE_BASED/), containing all the files (videos showing the walking behaviour of the virtual fly, and notebooks with the proposed approach) related to the rule-based controller;
- Final presentation slides in [PDF format](/COBAR_final_presentation.pdf) and in [PPTX format](/COBAR_final_presentation.pptx), introducing the strategies we followed to create our controllers, and the results reached on different terrains;
- [Project report](/COBAR_MiniProject_Report.pdf), presenting in detail the controllers and the results reached.