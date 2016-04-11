---
layout: page
title: Research
permalink: /research/
---

________

Jacobsson, Ludwig, & Malec, Jacek, & Klas Nilsson. (2016, June). *Modularization of skill ontologies for industrial robots.* To be presented at 47th International Symposium on Robotics ISR 2016: Robotics in the era of digitalisation. Munich, Germany. 

________



Jacobsson, Ludwig. [_A Module-Based Skill Ontology for Industrial Robots_](http://lup.lub.lu.se/student-papers/record/8245197) *Master Thesis* 2015.

### Popular science summary - Reusable skills for industrial robots

**_snapfit_ and _peg-in-hole_, the future of robot programming. Developing a model for 
reusable skills used to instruct industrial robots in manufacturing tasks. Robot skills will enable the app­store like skill libraries of the future.**


To drive the development and integration of industrial robots in manufacturing tasks new approaches to robot programming are needed. The current state of robot programming involves trajectory planning and low level instructions for grippers and tools. This results in long development processes and is highly dependent on the expertise of the developer. To remedy this limitation reusable robot skills are introduced. A skill describes a _know how_, or capability, of a robot. Each skill is designed to be reusable over different types of industrial robots. By combining these skills the robot can be instructed to solve complex tasks. For example, the task of assembling a table can be achieved by combining the imagined skills, _drill_ and _peg-in-hole_. This can now be achieved by a user not well versed in the area of robot programming. Perhaps even a computer can reason on the needs of the task and the outcome of each skill and instruct the robot without the need of human interaction. In order to enable this usage of skills for robot instruction each skill need to be packaged and stored with rich structured descriptions and in a way that enables a plug­and­play like behaviour.  

We have developed a data model for representing and storing these skills. The model was implemented as an ontology. A ontology is a representation of the entities in a domain of knowledge using classes, attributes and relationships. To achieve machine readable knowledge descriptions we use an ontology to describe the intrinsic concepts of a skill. Each skill is essentially a motion control instruction for the robot along with a structured description of important aspects of the skill. To achieve sufficient packaging and storage our model represents these intrinsic concept describing the skill. Our data model consists of a class hierarchy and class relations describing the skill aspects. Reuse, management and extensions on the current model are enabled by organizing the skill knowledge into smaller knowledge domains using separate ontologies. By isolating the knowledge specific to each skill, skills are treated as reusable items and can be applied in a plug­and­play like manner.

Our work shows that the use and reuse of skills is in the near future. 
The pluggable feature of the skills inspire us to imagine a future _skill library_ where the users can download and upload skills to accommodate for their needs and solve the tasks in front of them.
