---
layout: single
title: "Teaching robot programming to 4th Grade"
date: 2018-01-15
tags: phd teaching
header:
  teaser: /assets/img/ASTEP_Thymio_2018_Ambulance.png
---

On Tuesday and Wednesday morning for six weeks, I am teaching in primary school, through the agreement [ASTEP, La main à la pâte](https://www.fondation-lamap.org/fr/astep) (_The hands-on_). This was as part of my teacher training.  

I teach daily to three years post-baccalaureate students (21 years old) at the Polytech Annecy-Chambéry engineering school. Meeting 4th-6th Grade students was refreshing. This is a recap of my intervention.  

### Introduction: ethical and societal discussion

This first session had the dual objective of presenting the program and discovering the Thymio robot.  

In the first part, a presentation on the interactive whiteboard in the form of questions asked of the students made it possible to define what programming is and what a robot is. This part was one of the most amazing for me since we quickly raised issues such as artificial intelligence and the role of robots in our society. It would be very interesting to organize a debate on this subject to deepen.  

The second part allowed the students to manipulate and discover the robot in small groups of 3-4 students. The robot has simple programs accessible by touch keys, which made it possible to operate it without programming.  


### Sessions plan
- Introduction to my research.
- Have you ever seen a robot? Where? What was he doing?
- Video of industrial robots I use
- Moving to the computer room to manipulate the robots
- Solving [INRIA IniRobot](https://dm1r.inria.fr/) missions: What is this thing?, Colors and behaviors, If... then ..., And if we programmed?, Sensors and sensing, Human and Robot
- Teamwork: get a mission card and team solve it
- Final session: 10x expert programmer: memories and timers

### Blockly vs Thymio VPL
I chose to perform the very first sessions with the _Blockly_ language. This better represents the formalism of indented programming languages, that programmers must master and that some students already know.  
Subsequently, the more visual _Thymio VPL_ software allows programs to be produced more advanced functionalities (memories, finite state machine, timers).  
Nevertheless, the notion of memory then becomes completely detached from the notion of mathematical variables.  
The evaluation of the two software allowed me to note an ease of handling of _Thymio VPL_ slightly superior to Blockly.
Finally, working on timers and memories is not achievable at the 4th Grade level with Blockly.

### Outcomes: programmed robots

At the end of the sessions, the students completed all the IniRobot missions and at least four "advanced" missions from the Challenge Pack.
The success of these missions is each time materialized by the interactions of the real robot. The students worked in small groups throughout the sessions, helping each other to solve the problems.
Through the issue of missions, the students understood the investigative approach to solving a problem: reflection in order to propose a solution and experimental validation.
The last session allowed us to present the notion of memory and variable as well as the notion of timers. We made the link with the notions of speed, distance and time. We did not plan to address these advanced concepts in the initial plan, but as the students quickly mastered the basics, we were able to go further.

For my part, as an apprentice teacher, I learned to work with a different audience with the help of expert teachers. The primary school offers tailor-made education, adapted to each child. This experience taught me new teaching methods, including being able to adapt to each student.
I had in memory, until now only the point of view of a schoolboy and this experience brought me another on the school which is, I think, essential for any teacher, even any parent of 'Student. Elementary school is a key place in schooling and I am happy to have met passionate teachers.  

{% include figure image_path="/assets/img/ASTEP_Thymio_2018_Ambulance.png" alt="Thymio is an ambulance" caption="Thymio is an ambulance: simulation of a program carried out by a group of students, line tracking and timed color change." %}

### Technical feasibility of robot programming in primary school

When using a new tool, a first set-up session is mandatory. Once
the proven material and most of the technical subtleties raised, we worked in serene conditions.  

This barrier from the first session is a difficulty for all
teachers. This is the main limit to the use of new
tools, including IT tools, which evolve regularly. This is
why the ASTEP aggrement, with Master and PhD students as teachers, is a real opportunity to setup and test new educational tools, like robots.  

_The material is in my [ASTEP_Thymio_2018 repository](https://github.com/a1rb4Ck/ASTEP_Thymio_2018])._

# References

- [ASTEP, La main à la pâte](https://www.fondation-lamap.org/fr/astep) (_The hands-on_)
- [INRIA IniRobot](https://dm1r.inria.fr/)  
- [Google Blockly](https://developers.google.com/blockly)  
- [Thymio VPL](https://www.thymio.org/program/vpl/)  
- Post from the University Grenobles Alpes [blog ASTEP Université Grenoble Alpes](https://doctorat.univ-grenoble-alpes.fr/fr/pendant-la-these/la-formation-durant-la-these/parcours-labels/ateliers-projets-du-label-res/ateliers-astep-/programmer-des-robots-thymio-754129.htm?RH=GUCEDFR_PROJ) (in french)  
