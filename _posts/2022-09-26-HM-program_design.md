---
toc: true
comments: false
layout: post
title: Program Design
description: Look for a real need.  Program Design, ideation, and eventual development work a lot better if you have a real need or an idea of purpose.
permalink: /collegeboard/design
image: /images/UML_logo.png
categories: [C1.6, C2.0, C2.1, C2.2, C2.3, C2.4, C2.5]
type: human
week: 5
---

![uml]({{site.baseurl}}/images/UML_logo.png)

## Project Planning
> Look for a real need, Teacher/Student need, Educational Study or Simulation, Campus Club, Campus Interest, Business Interest, Charitable Organization, mimic portions of a system like Amazon, etc.  Of course, the greatest interest is <mark>Student Interest</mark>.  The project will not work if only one student is interested.
    - Program Purpose and Function.  Think about inputs, outputs, UI, and data that will be in the program.
    - Be sure to pick something that you don't burn out on after a couple of weeks.  If you are a couple days into something and it is not working it is best to change. 
    - IMO, it is much more interesting to work on something that has 3rd party interest or that you design something with intention to acquire a 3rd party interest.  Working on something to acquire accolades is a big motivator.
- Begin a code base.  Some of ideation may come in play with code.  This could also be done in Jupyter Notebooks.
- Data Abstraction.  UML is pictured in article.  Think about how data will be formed and managed.
- Managing Complexity.  Think about frontend and backend portions of the system.  Remember that objective is to use JavaScript in frontend and Python in backend.
- Procedural Abstraction.   Design some of the key objects of the system.  Think about the key elements of User Design.  This should help you divide work amongst team.   Effectually, you will be creating the sub systems of the system in this design effort.
- Algorithm Implementation.  The key aspects of your project and its algorithms must be considered and prototyped early.  This will help you understand capabilities of team and some of the longer/research required activities.
- Testing.  Be sure that you are performing iteration and testing as you go.  Do not stack things up or integrate infrequently.  Develop, Integrate, Test a couple of times weekly!!!  Also, think about the things that needs to be tested.  Think about how to put data into the system to ensure quality is produced and everything is easily validated.

## Teacher Needs
> PBL. Concept/Idea in CSP Education.  This could be achieved using Blogging and Jupyter.  Some have said, it is possible to pass the AP exam in 1 month of study.  This would be several 1 hour lessons.
- Highlight all 5 Big Ideas from CB.
- Remake CB site to be Student Friendly, More Code, and less Video.
- The Web Site covers key topics from CB, also includes Mini-labs, and thus should be interactive.  The code and visuals should teach more than the words.
- FRQs could be challenges or hack-a-thon activities that could enhance a Test Prep sessions. 

> PBL. Concept/Idea around Classroom Management. Build data for a series of classroom needs.  This could be CompSci, but these requirements are for me.
- A system were students can do administration.  
    - Users and Passwords.   A single source for all projects to minimize duplication of data across periods and transitions during year.  Graduation year would be a big key, to active or alumni.
    - Access through accounts RESTful API
    - User Setting and Attributes for students to be self updated
- Attributes
    - Name, Grad year, and some other basics (birth day without year)
    - Password integration with Email
    - GitHUB ID, Slack ID
    - Track student history
        - Track All GitHub projects for the user through Year (Tri 1,2,3)
        - Track all Period through year
        - Roles of Development for User through Year
        - Scrum Teams and other students worked with
        - Pull sources like GitHub commits
        - Runtime project that are alive
    - Integration with GithUb pages, ability to Comment on assignments
- Backup of Data to JSON
- Restore Data from JSON

> Last year Projects.   I have access to student projects from last year that were never finished.  Working on them and extending them is often better than starting from nothing.

## Hacks
> Now is time to transition to Design and Development. Designs are required and must meet Teacher Approval.  If you get negative feedback act quickly.  Designs should be put together around a Blog. 
- Brain Write. The process of just elaborating on ideas and sharing them with your team.
- Wire Frame, Concept.  Before coding start to outline what the project will look like.
- Modeling or UML.  Behavior, Interaction, Data diagrams

> Additionally, some development of Concepts can/should occur.  This should be focused on frontend or backend concepts.
- Frontend.  Wire Frame development is better than coding, at early stages.  But if you have clear idea and can articulate it in HTML or CSS it is OK to work there as well.
- Backend. Jupyter notebooks is a great way to thing about data and outputs.  Often a console program can help you imagine data as well as interaction.

> This work does not need to be finished in trimester.