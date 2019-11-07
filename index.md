![]({{site.url}}/assets/img/teaser.PNG)

We are seeing a growing need of dexterity in robotic manipulation beyond grasping. Such dexterity is usually motivated by a creative use of contacts, where these contacts can come from robot hands, arms, or any objects and fixtures in the environment. An intelligent robot can manipulate an object or its own body by exploiting the geometric and force constraints offered through contacts. Such skillful use of contact interactions could  be crucial for realizing dexterous, reactive and robust robotic manipulation as well as mobile legged locomotion (self-manipulation).

While highly desired, such contact-rich manipulation comes with its own challenges -- from noisy sensors to computationally demanding planning and control frameworks. While the recent research has proposed efficient algorithms and solutions for dexterous and robust manipulation, the industrial applications are seldom seen. This workshop aims to address and hopefully bridge this gap by inviting leading researchers from academia to discuss the recent advances in the field and industry experts to share their experiences and needs from the contact-rich robotic manipulation in industry. We hope this workshop can encourage discussions about possible transfers between the academic results and industrial applications.

## When and where
* Nov. 8th, 9am ~ 5:30pm
* Room: LG-R20

## Topics of interest
- Non-prehensile Manipulation
- Manipulation through External Contacts
- In-hand Manipulation
- Multi-modal Manipulation Planning
- Grasp planning, Motion planning, and Task Planning for Manipulators
- Model/Policy Learning for Manipulation through Contacts
- Whole-body Manipulation
- Locomotion/Self-manipulation considering Contacts and Gravitational Constraints

## Open Talk Session
The workshop has several open talk sessions. The application is open to both academia and industry. Everyone can apply for a talk to share their work on related fields. The talk should be around 5 min plus Q&A.

**How to apply**

Please send an email to <a href = "mailto: manipulation.workshop@gmail.com">manipulation.workshop@gmail.com</a> with title *Application for open talk*.
Please include the following information in your email:
- Title and abstract of your talk;
- Brief self-introduction. (< 100 words)

Please apply early, as the positions are limited.

**Important dates**

First round of applications ends at October 6th.

For the remaining slots, we will assign them in a first-come, first serve manner. Applications will receive the decisions within five days. All applications must be received before October 25th.

<font color="red"> (Oct.12) The open talk slots are full. The application is now closed. </font>


## Invited Speakers
(All in alphabetical order)
<div align="center">
    <span style="font-weight:bold;font-size:20px">Research Talks (30min each)</span>
</div>

**Reeve Zheng Hao Chong**, Nanyang Technological University, [website](https://reeve333.wixsite.com/reeve-zhchong)

**Kensuke Harada**, Osaka University, [website](http://www.hlab.sys.es.osaka-u.ac.jp/people/harada/)


**Maximo Roa**, DLR German Aerospace Center, [website](https://rmc.dlr.de/rm/en/staff/maximo.roa/)

**Alberto Rodriguez**, Massachusetts Institute of Technology, [website](http://meche.mit.edu/people/faculty/ALBERTOR@MIT.EDU)


<div align="center">
    <span style="font-weight:bold;font-size:20px">Industry Talks (20min each)</span>
</div>

**Miao Li**, Wuhan University/Cobot Technology Co., [website](https://miaoli.github.io/)

**Huan Liu**, MUJIN Inc., [website](https://www.mujin.co.jp/en/)

**Tao Wang**, Dorabot Inc., [website](https://dorabot.com/)

**Peter Kuan-Ting Yu**, XYZ Robotics Inc., [website](https://www.xyzrobotics.ai/)

**Ruobing Yu**, AI Data Innovations, [website](https://www.aidatainnovations.com/)

<div align="center">
    <span style="font-weight:bold;font-size:20px">Open Talks (10min each)</span>
</div>

**Neel Doshi**, MCube Lab, MIT

**Felix von Drigalski**, OMRON SINIC X Corporation

**Werner Friedl**, German Aerospace Center Institute for Robotics and Mechatronics

**Mincheul Kang**, KAIST at Daejeon, Korea

**Jelizaveta Konstantinova**, Ocado Technology

**Andrew Melnik**, CITEC, Bielefeld University

**Fan Shi**, JSK Lab, the Univ. of Tokyo

**Maria Bauza Villalonga**, MCube Lab, MIT

## Program (Tentative)
(Mouse over the title to see abstracts.)

Time | Speaker | Details
------------ | ------------- | -------------
<font color="grey">9:00-9:15</font> | <font color="grey">Opening</font> |
9:15-9:45 | **Alberto Rodriguez**, MIT, USA | <span title="Can we ever certify that a planned grasp will work? The common approach to grasping is to plan an arrangement of contacts on the surface of an object. Experimental evidence shows an intuitive but also paradoxical observation: On one hand, most grasps do not work as expected since, due to uncertainty, fingers do not deliver exactly the planned arrangement of contacts; on the other hand, many planned grasps still end up working and produce a stable hold of the object. These natural passive dynamics work within all grasping algorithms, often to their benefit, sometimes adversarially. In this project we study the possibility to synthesize grasps for which the fingers have no other option than fall into the right grasp. Understanding the nature of robustness in grasping is essential for automatic grasping solutions to become a reality." style="text-decoration: underline">Certified Grasping</span>
9:45-10:05 | **Peter Yu**, XYZ Robotics Inc., USA | <span title="XYZ Robotics is committed to transforming industrial automation using AI robotics and mechanical intelligence. One of XYZ's primary focuses is piece-picking: moving individual items from one container to another. This labor-intensive process is a vital part of any supply chain. Although the task is easy for human workers, traditional industrial robots fail to navigate the full range of diverse item sizes, weights, and textures, not to mention their random arrangements. XYZ provides turnkey solutions that overcome these challenges with high speed and reliability. These solutions are powered by XYZ’s powerful vision system, which does not require prior training on target items. Furthermore, XYZ’s custom end-of-arm tooling (EOAT) design increases speed and robustness while amplifying the variety of items that can be handled." style="text-decoration: underline">Vision and Tooling for Robotic Manipulation</span>
10:05-10:25 | **Ruobing Yu**, AI Data Innovations, USA | <span title="Different goals and different metrics of success (e.g,. publication vs revenue) – Goal: how do we define common goal and metrics for success; Creation of a supportive environment between academia and industry; Solution metrics ( cost, complexity, robustness, availability, scalability, modularity etc. ); Standardization (safety, benchmark, datasets. etc); Maybe: survey results on above criteria from industry; Blueprint for success" style="text-decoration: underline">"Decade" Problem for bridging academia to industry</span>
10:25-10:45 | Open Talk Session I | <span title="We present a differential dynamic programming algorithm for planning and closed-loop execution of manipulation primitives with frictional contact switches. Planning and control of these primitives is challenging as they are hybrid, under-actuated, and stochastic. Our approach addresses this by planning a trajectory over a finite horizon, considering a small number of contact switches, and generating a stabilizing controller. We evaluate our framework in a simulation study for two primitives: hybrid planar pushing and pivoting. We can plan pose-to-pose trajectories from most configurations with only a few hybrid switches (1 to 2) and in reasonable time (1 to 5 s). We further demonstrate that the controller stabilizes these hybrid trajectories on a real pushing system." style="text-decoration: underline"> Neel Doshi, Hybrid Differential Dynamic Programming for Planar Manipulation Primitives </span> <br><br> <span title="During assembly tasks, the pose of an object in the robot's gripper needs to be known with high precision in order to manipulate it afterwards. In this talk, we present a method to determine the in-hand pose of a grasped object using only general purpose grippers and wrist force sensors, based on particle filtering and Bayesian state estimation." style="text-decoration: underline"> Felix von Drigalski, In-hand pose estimation using active touch </span>
<font color="grey">10:45-11:15 </font> | <font color="grey">Coffee break</font> |
11:15-11:45 | **Kensuke Harada**, Osaka Univ., JAPAN | <span title="In this talk, we explain about our recent progress on industrial automation done in our research lab. We first explain some results on randomized parts picking for tangled and shiny objects. Then, we explain some results on product assembly by utilizing the human skill. Especially, we focus on how to capture human skill, assembly planner, construction of gripper used for product assembly."> Industrial Automation by Parts Picking and Product Assembly </span>
11:45-12:15 | **Zheng Hao (Reeve) Chong**, NTU, SINGAPORE | <span title="As demand from emerging economies encourages the deployment of robots to shift from lab proof of concept to practical application, they are likely to assimilate into our living environment. In this presentation, I will present the research development in the lab and the competitions that I participated previously and how these concepts are transformed into the practical application at industry. Several pick and place solutions will be shared in this presentation, which include surgical tools picking, linen picking, multiple items cluster bin picking and picking from the shelf. Robot manipulation task such wall cutting and valve turning will also be discussed. At the same time, I will also show how these technologies being performed in competitions such DARPR Robotics Challenge, Amazon Robotics Challenge 2017 and DHL Robotics Challenge 2017 and how did it turned into practical application at real industry and its challenges. (Requirement disparity between research and deployment)" style="text-decoration: underline">Competition as Innovation Shortcut in Robotics Solutions</span>
12:15-12:35 | **Tao Wang**, Dorabot Inc., CHINA | <span title="Recent advances in robotic manipulation has peaked interest in the logistics industry into adopting robot arms for improving efficiency, cost, and service. A fundamental and common requirement of such a solution, is the grasping capability. In the past, suction cups are the industry standard for manufacturing and assembly line robotic solutions in deterministic environments. This is the reason why suction cups are well studied and optimized by researchers and industrial leaders worldwide. The limitations of using suction cups arises when the logistics industry has further requirements, for example, grasping soft packages and envelopes. Therefore, the next step is to further research different hardware and software grasping solutions that provides stable and efficient manipulation in complex and undeterministic environments for a variety of objects in the logistics industry." style="text-decoration: underline">Stable grasping in the field of logistics</span>
12:35-13:05 | Open Talk Session II | <span title="TBD" style="text-decoration: underline"> Jelizaveta Konstantinova, SoMa - Soft Manipulation, commercial food handling </span> <br><br> <span title="Recently, aerial manipulation is popular with the development of the multirotor robot. However, most of the current work focuses on basic pick-and-place task, and further dexterous manipulation skills are in lack of discussion, which limits the performance of aerial manipulation. In our research, we are aiming to develop planning and control framework for aerial multilink transformable robot to achieve several of challenging aerial regrasping tasks through contact. In this talk, we would like to show our latest work and discuss the similar and different features in manipulation between aerial and normal manipulator robots." style="text-decoration: underline">  Fan Shi, Steps Towards Aerial Dexterous Manipulation </span> <br><br> <span title="A redundant manipulator has multiple inverse kinematics solutions per an end-effector pose. Accordingly, there can be many trajectories for joints that follow a given end-effector path in a Cartesian space. In this talk, we present a trajectory optimization of a redundant manipulator to synthesize a trajectory that follows a given end-effector path accurately, while achieving the smoothness and collision-free manipulation. Given these desirable properties, our method optimizes a trajectory based on gradient descent. To further improve the performance and avoid falling into local minima, we apply the quantum annealing that iteratively randomizes various configurations of the trajectory, followed by updating the trajectory. We first show benefits of our method with environments containing external obstacles. We then compare ours with the state-of-the-art methods, in their favorable setting, environments without having obstacles. Our method robustly minimizes the pose error in a progressive manner while satisfying various desirable properties. This work was submitted to ICRA 2020." style="text-decoration: underline"> Mincheul Kang, Collision-Free Trajectory Optimization of Redundant Manipulator given an End-Effector Path </span>
<font color="grey">13:05-14:05 </font> | <font color="grey">Lunch break</font> |
14:05-14:35 | **Maximo Roa**, DLR, GERMANY | <span title="This talk presents the development of the CLASH hand, an antagonistic hand with variable stiffness. Its  inherent mechanical intelligence allows the hand to seamlessly adapt and embrace contacts with the environment. Embedded sensors provide the hand with the information required to quickly recover from potential failures, and to continue operation even in the case of problems in the motors or tendons. Combined with suitable grasp planners that consider the smart usage of the environment, this hand enables a safe and reliable grasp of challenging objects."> Robustness and performance of CLASH, a compliant sensorized hand with variable stiffness </span>
14:35-14:55 | **Miao Li**, Cobot Inc., CHINA | <span title="TBD"> TBD </span>
14:55-15:15 | **Huan Liu**, Mujin Inc., JAPAN | <span title="We will tell a few stories about the challenges we face everyday and our culture. We will explain how the most talented and motivated people work together to push the limits of robotics." style="text-decoration: underline">Never give up, never surrender! What it takes to deploy the latest and greatest robotics technologies in production</span>
15:15-15:45 | Open Talk Session III | <span title="The lack of tactile reasoning still remains one of the main limitations of dexterous robotic manipulation, and a long-standing challenge in the robotics community. Even after decades of advances in sensing instrumentation and processing power, the basic question remains: How should robots make use of sensed contact information? To address this question, my work builds from a recent interest in image-based tactile sensors such as GelSlim or GelSight which achieve very high spatial acuity and pressure sensitivity, yielding highly discriminative tactile signals. In this talk, we will exploit the discriminative power of contact sensing by presenting an approach to tactile localization that can do first-shot localization of objects, i.e., localization is possible from the first contact with the object. Moreover, our tactile localization method can easily include visual information and multiple contacts, providing an effective solution for those contact-rich tasks that require accurate object localization." style="text-decoration: underline"> Maria Bauza Villalonga, Precise Tactile Localization for object manipulation </span> <br><br> <span title="Deep Reinforcement Learning techniques demonstrate advances in the domain of robotics. One of the limiting factors is the large number of interaction samples usually required for training in simulated and real-world environments. In this work, we demonstrate that tactile information substantially increases sample efficiency for training (by 97% on average), and simultaneously increases the performance in dexterous in-hand manipulation of objects tasks (by 21% on average). To examine the role of tactile-sensor parameters in these improvements, we conducted experiments with varied sensor-measurement accuracy (Boolean vs. float values), and varied spatial resolution of the tactile sensors (92 sensors vs. 16 sensors on the hand) in the MuJoCo physics engine. We conclude that ground-truth touch-sensor readings as well as dense tactile resolution do not further improve performance and sample efficiency in the tasks. We make available these touch-sensors extensions as a part of OpenAI-Gym robotics Shadow-Dexterous-Hand environments." style="text-decoration: underline"> Andrew Melnik, Tactile Sensing and Deep Reinforcement Learning for In-Hand Manipulation Tasks </span> <br><br> <span title="Soft hands like the DLR CLASH show quite good results in grasping unknown shape objects like fruits and vegetable by tactile exploration, as long the vision and planing errors are less than 1 cm for example an apple. Also grasping objects like bottles semi autonomy  for example works quite well, as long the  positioning errors by the operator is not to big. To solve this issue we show a combination of tactile and proximity grasp position adaption, which can reduce pre grasp error up to 6 cm to less than 1cm. The combination of three different sensor inputs works also with glass and black objects, instead of an only proximity based solution. Furthermore a big advantage of CLASH is the variable passive  stiffness, which allows to stop the robot or finger soft for higher velocity than a stiff hands, if the hand is touching something. This feature helps to use the tactile exploration for acceptable end effector velocities." style="text-decoration: underline"> Werner Friedl, Grasp pose adaption by tactile and proximity input for a soft hand to improve grasping in crowded scenes </span>
<font color="grey"> 15:45-16:15 </font> | <font color="grey">Coffee break</font> |
<font color="green"> 16:15-17:15 </font> | <font color="green">Discussion</font> |
17:15 | End |

# Organizers

**Main Organizer**
- [Yifan Hou](http://www.cs.cmu.edu/~yifanh/), Ph.D. Student, Carnegie Mellon University, yifanh@cmu.edu
- [Weiwei Wan](https://sites.google.com/site/weiweilab/), Assoc. Professor, Osaka University, wan@sys.es.osaka-u.ac.jp
- [Mehmet Dogar](https://engineering.leeds.ac.uk/staff/743/dr_mehmet_dogar), Ass. Professor, University of Leeds, m.r.dogar@leeds.ac.uk
- [Jurgen Leitner](https://staff.qut.edu.au/staff/j.leitner), Postdoc, Queensland University of Technology, j.leitner@qut.edu.au

**Co-organizers**
- [Nikhil Chavan Dafle](https://nikhilcd.mit.edu/), Ph.D. Candidate, MIT, nikhilcd@mit.edu
- [François Hogan](https://www.linkedin.com/in/francois-hogan-2b4025b6), Ph.D. Candidate, MIT, fhogan@mit.edu

![]({{site.url}}/assets/img/ending.png)
