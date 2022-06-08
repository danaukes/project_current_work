# What are the major goals of the project?

This project envisions a unified and automated pipeline for understanding and leveraging compliant behavior in tuned dynamical systems that are affordable and easily prototyped. Our goal is to make it possible for a non-expert to design and prototype a two hundred dollar robot in under two hours.

We propose four main research objectives to accomplish this goal:

1.  Modeling and representation of compliant materials
2.  Leveraging compliance-enabled phenomena,
3.  Simulation-based co-optimization of design and control of dynamical systems
4.  Verifying the pipeline at element, subsystem, and system levels.

We believe this will be accomplished through a focused set of activities:

1.  Simplifying the process of modeling, prototyping, testing, and controlling robots
2.  Focusing on the use of affordable material systems within robot design
3.  Focusing on accessible, rapid-prototyping-based fabrication strategies that promote iteration and keep cost low
4.  Factoring in, fully utilizing, and optimizing systems in full consideration of the innate compliance of lower-cost material systems, for use in high-performance applications.

# What was accomplished under these goals and objectives?
> (you must provide information for at least one of the 4 categories below)? more information about what was accomplished under these goals (revised 2020)

## Major Activities

Our focus in Y2 has been along the following major activities, all surrounding the design of compliant, laminate systems:

1.  The ideation, design, and prototyping of legged laminate systems that permit us to encode desired, nonlinear spring stiffness profiles into laminate structures and combine them with linkage-based parallel mechanisms.
2.  Developing models of these systems based on the "template" and "anchor" approaches for representing legs. "Templates" may be thought of as simple spring-mass-damper "pogo-stick" models. "Anchors" are more realistic kinematic and dynamic representations of the materials and geometry involved in the actual leg design.
3.  Developing a design and testing pipeline for experimentally: 1) prescribing actuation signals, 2) measuring ground reaction forces, 3) tracking leg motion, and 4) measuring subsystem and system stiffness.
4.  Analyzing experimental results to draw conclusions about the appropriateness of template vs. anchor models, about the role nonlinear compliance plays in jumping and other activities, and to better understand the role that un-modeled interactions play in causing model/experiment divergence.

These activities are intended to permit the rapid development, modeling, prototyping, and testing of families of compliant legged systems whose stiffness can be tuned on demand as a function of laminate geometry and material selection while maintaining a common design template.

A second set of activities \-- recently begun \-- includes the ideation, prototyping, and initial testing of hierarchical compliant feet, for interaction with a variety of ground substrates, including hard ground, soil, and granular media. Current work is looking at the role surface area and compliance play in the foot's ability to generate tangential forces under prescribed normal loads.  We have begun a prototyping-based exploration of how/whether stiff, claw-like structures can play a role in improving surface traction on soft or granular surfaces without hindering performance on hard surfaces. 

## Specific Objectives

The following are the objectives driving the above leg design activities:

1.  Understanding the mechanisms by which simple changes in the kinematics or geometry of laminate leg systems can be tuned in order to change the linearity of the leg stiffness profile.
2.  Understanding whether nonlinear leg compliance plays a role in improving performance across a range of activities, with an initial focus on jumping. Our goal is to proceed to study nonlinear compliance's role in landing, walking, running, and other terrestrial gaits and activities.

The following are the objectives driving the above foot design activities:

1.  Understanding the role compliance, shape, area, and other design factors play in the interactions with harder, softer, and granular soils.
1.  Understanding whether hierarchical, multi-material or "multiple-compliance" laminate structures embedded within robotic feet can play a role in improving locomotion performance 1) across a range of ground models and properties, and 2) across different types of interactions/activities with the ground, such as digging.
1. Understanding the physical properties and modeling methods of available laminate materials and how to integrate or mitigate their compliance given design requirements. 

## Significant results

We are wrapping up a set of design, data collection, and analysis activities surrounding laminate leg design that is culminating in our first journal paper submission, to be submitted this month. Current results in the form of our draft paper are attached in supplemental documentation.

## Key outcomes or Other achievements

This work has resulted in a family of jumping robotic leg designs whose stiffness profiles are highly tunable and nonlinear. Legs within this family can be rapidly prototyped.  For example, once a parameterized CAD file is designed, subsequent iterations from a desired stiffness and motion profile to an actual working leg prototype takes about an hour. We have also "mass produced" multiple legs at the same time, which cuts down some of the repetitive steps and further reduces the average fabrication time.  This permits  experimental characterization and validation of both "template"-based and "anchor"-based models throughout a large design space. These legs have been studied from the perspective of understanding how linearity in compliance can play a role in expanding jumping capabilities, especially as we begin to consider the needs of competing activities such as landing, walking, and running, which may dictate different design goals that require trade-offs. The legs have been prototyped, experimentally characterized in a series of dynamic jumping tests, and compared against model-based predictions of their motion.

We have also developed a new set of script-based tools that permit the rapid translation of leg designs from Autodesk Fusion 360 to be exported to a layer-based representation that can be used to compute the manufacturing files required for fabrication.

# What opportunities for training and professional development has the project provided?

The project is allowing a group of Ph.D. students to work collectively and collaborate to solve a number of challenging engineering problems. They have received training on the design cycle of foldable robots and are using that methodology as they proceed through iterative cycles of engineering research & design, including tasks like modeling & analysis, design, prototyping, manufacturing planning, control, experimental validation, etc.

This group includes students who have already authored peer-reviewed work in related topics; these students are helping to mentor and train the newer students. Training in Y2 has focused on teaching fabrication techniques and tools common within our lab (3d printing, laminate fabrication, laser cutting, etc), experimental data collection methods and tools (camera-based tracking, linear stage and mobile robot programming, taking force/torque measurements, etc), as well as laboratory best practices for working with and sharing code, using existing software packages, etc. Mentoring topics include how to craft a good research question, writing, and presenting, etc. Students get regular feedback from PI Aukes in weekly PI meetings as well as from their peers in weekly lab meetings. Students are encouraged to present their work to the group and provide feedback to each other, to encourage cross-pollination of good ideas and best practices across the lab, and to develop a culture of high-quality research.

Two students assigned to this project accompanied me to ICRA 2022 this year, and presented their work in workshops, attended sessions, etc.  This was their first opportunity to attend a conference in person since they began their PhDs, due to COVID and their international travel limitations.

Other training opportunities are mentioned in the subsequent section on development of human resources.

## Have the results been disseminated to communities of interest? If so, please provide details.

We have begun to disseminate our work, though we anticipate higher output next year.  We recently presented initial work on hierarchical foot design at a workshop at ICRA 2022 in Philadelphia.  We are preparing similar initial work on nonlinear, compliant leg designs to be presented this Summer. 

## What do you plan to do during the next reporting period to accomplish the goals?

With the beginnings of our design, fabrication, modeling, and analysis pipeline in place, our plan is to broaden our activities to focus not just on jumping, but landing, walking, and running, as well.   Our goal is to explore the role leg, foot, and ankle compliance play in improving stability during these activities, increasing performance (through improved traction, lower mass, and tuned dynamics), and expanding from focusing on single leg systems to bipedal robots.

The developed pipeline also enables us to co-optimize the mechanism, compliance and controller design of legged robots. We aim to explore the balance between the subtasks that can be offloaded to mechanical intelligence/preflexes (such as perturbation rejection and energy reuse) and those that are feasible through software control (such as body trajectory tracking and failure recovery) given a low budget constraint. 

We are also beginning to think more about how to conduct legged walking experiments in our lab, and are considering our options for tethered, semi-constrained walking experiments, as well as minimal-tethered options for evaluating walking performance across.  We expect to develop an experimental testbed over the next 12 months for evaluating performance across a wide range of activities and media.

## Supporting Files


--------------------------

# Impact

> What is the impact of the project? How has it contributed? more information about the Impacts
> 
> INSTRUCTIONS - This component will be used to describe ways in which the work, findings, and specific products of the project have had an impact during this reporting period.
> 
> For NSF purposes, include, where appropriate, discussion of data resources and the acquisition of data skills. Include the emergence of new career paths, such as data scientists, or new disciplines.
> 
> If there is nothing significant to report during this reporting period, please check \"Nothing to Report\" if applicable.

# What is the impact on the development of the principal discipline(s) of the project? 

> more information about the impact of the development of the principal discipline more information about the impact of the development of the principal discipline, specific to NSF
> 
> Describe how findings, results, techniques that were developed or extended, or other products from the project made an impact or are likely to make an impact on the base of knowledge, theory, and research and/or pedagogical methods in the principal disciplinary field(s) of the project.

Though many jumping robots have been previously reported, many of these devices represent highly-optimized expert-driven designs focused solely on jumping, wherein all the important decisions are encoded a priori into the mechanical structure and static, pre-selected, off-the-shelf parts. Few designs focus on cost-conscious fabrication approaches, consider the flexibility of their constituent building materials, or consider how/whether that built-in compliance can be tuned so as to improve performance of an activity, let alone across multiple robotic tasks. Our approach aims to holistically consider these aspects using a fabrication strategy that permits a high degree of tunability during design to balance the needs of potentially competing performance targets across multiple desired tasks or in a variety of situations or environments.

<!--
The fundamental research contribution of this proposal lies within the consideration and integration of compliant material systems into a unified robot modeling framework that supports the specialization and optimization of dynamical robots.
This involves developing reduced models for the multidimensional, nonlinear mechanics of compliant materials and considering that compliance in simulations to model and optimize their performance. Our approach utilizes machine learning to automatically tune parametric, template-driven designs in a way that balances competing performance tradeoffs like speed, payload, and efficiency.
-->

# What is the impact on other disciplines?

> Describe how the findings, results, or techniques that were developed or improved, or other products from the project made an impact or are likely to make an impact on other disciplines.

The aim of this project is to translate our current work -- rapidly fabricable, dynamic systems, whose compliance is considered and optimized against in completing various tasks -- to a variety of applications important to other fields, for the purposes of disseminating this design, modeling, fabrication, and control approach in such a way that the design and fabrication of bespoke dynamic robotic systems becomes more ubiquitous and useful outside of the field of robotics.

One of the ways we hope to demonstrate the utility of our approach is through metrics like cost and time.  If external, non-expert researchers can utilize our design, fabricate, and model bespoke robotic systems quickly and easily, we feel that our approaches are validated.  We aim to demonstrate this in our own work by showing how physical prototyping can be accomplished fast enough to be time and cost competitive vs alternative approaches.

Through this project, we aim to collaborate with technical experts in other fields to demonstrate the feasibility of such translations in subsequent years. This work aims to provide more approachable robotics experiences for students and new hands-on interactions with younger students leading to favorable outcomes. Our work planned through outreach in future years will help establish this as well as measure impact.

We envision the results of this project will impact fields in which specialization is desirable; this includes assistive robots for the elderly, custom agricultural applications, and trash pickup in smart cities.

# What is the impact on the development of human resources? 

> more information about the impact on the development of human resources
> 
> Describe how the project made an impact or is likely to make an impact on human resource development in science, engineering, and technology.

Through the development of a robotics day camp, described in more detail below, I am training two local teachers in the technology, curriculum, and delivery of a foldable-robotics focused curriculum in a one-week day camp.  These teachers will be accompanying me each day in the classroom this year, learning in parallel with the campers.  After the conclusion of the day camp, I anticipate these teachers will be able to take what they have learned back to their home schools (one of the teachers is at a middle school, while the other works with grades 7-12), help develop new modules, and ultimately form a new tier of teaching associates who can help train and deploy the camp to new locales or an expanded program.  My aim is to grow this teacher training along with camper enrollment, in the form of new sites, expanded age ranges, and/or multiple sites/sessions throughout the summer.

The graduate researchers involved in this project are working collaboratively to solve a challenging and multifaceted technical problem. Through their research they are being trained in how to develop their own research program. The mentorship and training they receive helps develop their presentation skills in oral and written form, ensures they have the technical skills and abilities to interpret and visualize complex physical phenomena sampled through experimentation and data collection. Furthermore, their analytical and interpretive skills developed through these activities will lead to better critical thinking skills, useful in design and creative pursuits. These skillsets will contribute to the national workforce, whether it be industry or research.

# What was the impact on teaching and educational experiences? 

> more information about What was the impact on teaching and educational experiences
> 
> Describe how the project made an impact or is likely to make an impact on teaching and educational experiences.


I have embarked on a number of new teaching and educational initiatives on themes supported by this project. 

First, I currently teach _Foldable Robotics_, a graduate-level course that introduces the concept of rapidly-prototypable, multi-material, compliant robots to students.  This course draws directly upon topics from my current research for its curriculum while training the students who take it for performing research in my lab, or labs like mine. It also serves as a testing ground for determining the effectiveness of foldable robotics as a teaching approach through IRB-approved data collection in conjunction with ASU CREST(https://crest.asu.edu/). Other direct connections can be seen in course projects, which often generate critical “preliminary results”, demonstrating feasibility that I can then point to in proposals; this has previously resulted in both new funding and IP generation. Most notably, 24 of my published, refereed papers are co-authored by students who have taken my graduate foldable robots courses in the past.  I anticipate this number to grow substantially over the course of this current project.

CREST's final report from _Foldable Robotics 2022_ are attached in supplemental documents (The 2021 report was previously emailed to I. Dolinskaya and can be provided again if needed.).  These reports will be used to improve the curriculum in future iterations of the course.

My second initiative this year was to serve as a mentor for a senior engineering capstone team, for the purposes of developing a kit of parts and teaching plan for a summer camp aimed at middle schoolers, surrounding the topic of Foldable Robotics.  This team was provided supplementary funding through this CAREER project in order to complete their project.  As part of this effort, I met with the team roughly every three weeks to discuss their progress, provide feedback, and guide their project.  Through this project, students applied their knowledge of the engineering design process to speak with stakeholders, develop specifications, ideate and brainstorm design concepts, create prototypes, obtain feedback from stakeholders, and revise their designs.  They were able to present their proposed kit of parts and lesson plan to this summer's camp teaching team and obtain valuable feedback based on the teachers' level of comfort with the topics and technology involved.

A third initiative related to this project was serving as a thesis advisor for a senior honors thesis through ASU's Barrett honors college.  This student thesis focused on the issue of integrating data collection into the design of foldable-robotics-inspired curriculum for elementary and middle school students, developing an IRB for collecting data from parents and teachers, and using their data-collection experience in providing a framework for executing IRB-approved surveys in future years.

A fourth initiative directly related with this project was serving as a faculty mentor to two high school students participating in Arizona State University's SCENE program (https://eoss.asu.edu/access/scene).  In the SCENE program, high school students "work in state-of-the art labs at Arizona State University, under the guidance of professors and university students, to answer their own original research questions and compete in regional and national science competitions."  The topics of the two mentorships revolved around using foldable robotics themes to answer students' individual research questions for a health care and space application, respectively.

Finally, as mentioned previously, I am organizing a "foldable robotics day camp" to be held in June 2022.  19 students, ages 14-17, are currently enrolled in this one-week, full-day session, and up to 25 students will participate the following week in a similar session organized by ASU's Barrett Summer Scholars Camp Series(https://eoss.asu.edu/bss), aimed at 9th graders.  In both sessions, students will work through a number of modules, including: 

* Origami & Folding  
* Biomechanics and Bioinspiration  
* Prototyping and Making
* Microcontrollers and Programming in Python
* Motors and RC Servos  
* Making Tools & Manufacturing  
* Physics and Modeling  
* Experimentation
* Leg Design  
* Circuits & Sensors   
* Parent Showcase

I am integrating data collection via a final student and parent survey, administered again through ASU's CREST evaluation team.  I hope to gain valuable insights in this inaugural camp year in fine tuning and expanding this program in subsequent years.

Further information on the camp can be found on my website at https://idealab.asu.edu/events/.  I have also attached the final lesson plan developed by the Capstone team in supplementary materials.

# What is the impact on physical resources that form infrastructure?

> Describe ways, if any, in which the project made an impact, or is likely to make an impact, on physical resources that form infrastructure, Including physical resources such as facilities, laboratories, or instruments.


This project is likely to reduce the cost of physical infrastructure required to teach the fundamentals of robotics design.


# What is the impact on institutional resources that form infrastructure?more information about the impact on institutional resources that form infrastructure

> Describe ways, if any, in which the project made an impact, or is likely to make an impact, on institutional resources that form infrastructure,

By focusing on affordable fabrication strategies such as origami-inspired or laminate fabrication techniques, the startup costs associated with developing a new facility capable of teaching these concepts can be dramatically reduced.

# What is the impact on information resources that form infrastructure?more information about the impact on information resources that form infrastructure

> Describe ways, if any, in which the project made an impact, or is likely to make an impact, on information resources that form infrastructure,

I continue to develop the course website for foldable robotics, located at https://foldable-robotics.github.io/, and have added and updated many of the pages on the site to reflect the newest additions to the class, improvements in the way I am teaching the course, etc.

I plan to develop a companion website for the summer camp as well, though this will not be complete until next year.

# What is the impact on technology transfer? more information about the impact on technology transfer

> Describe ways in which the project made an impact, or is likely to make an impact, on commercial technology or public use.

This work related to this project likely to lead to new IP on the topic of origami-inspired design and optimization by the end of the project.

I am already listed on three patents, two patent applications, and one provisional patent that is related to prior work on foldable robotic topics, all with current or former students of the foldable robotics course and/or my PhD students; I believe this demonstrates my committment and level of activity in submitting relevant work to ASU's IP management office.  

# What is the impact on society beyond science and technology? more information about the impact on society beyond science and technology

> Describe how results from the project made an impact, or are likely to make an impact, beyond the bounds of science, engineering, and the academic world.

Robot kits for competing in national robotics competitions can be prohibitively expensive in underserved communities. The leg designs developed through this project will serve as a more affordable starting point for kids to compete in local “robot track and field meets”. These competitions will challenge kids to solve locomotion challenges unique to the desert Southwest by running the competitions in free, public, open spaces.

I have developed V1 of this kit and will be demo'ing it for the first time this June.  I will share information about the kit and accompanying lesson plan once I receive feedback and finish developing the Camp website in the following year.

# What percentage of the award\'s budget was spent in a foreign country? 

> more information about What percentage of the award\'s budget was spent in a foreign country more information about what percentage of the award\'s budget was spent in a foreign country, specific to NSF
> 
> Describe what percentage of the award's budget was spent in foreign country(ies) for this reporting period. If more than one foreign country was involved, identify the distribution of funding between the foreign countries.
