

---
layout: post
title:  "General update and flowchart"
date:   2020-09-28
categories: rpa-tomorrow blog 
---
Greetings!

Some initial progress has been made on the project, the team has been divided into groups and each member has been given the task to figure out issues for the sprint board starting with Sprint 2.

Internal groups
- Automation 
    - Aron, Gustav, Niklas, Hugo

- Natural language processing
    - Alexander, Mark, Viktor

These group formations are loosely based and naturally members will help out where is needed for further progress. 

![Flowchart](images/Flowchart-1.jpg)

A first prototype for the CLI has been written which simply parses the input and forwards it to spaCy. The intention here is expand the functionality later down the road and possibly write a GUI for the application as well. Most likely the GUI will be browser-based. 

Further, work has been started on an API for the automation which will take the output from spaCy and trigger various use cases. Firstly, we will focus on getting mailing to work, using CalDAV and Gmail. Other use cases with be expanded upon later down the road. 

Use-cases
- Send an e-mail, with attached file(s). 
- Ask if a person is busy in meetings based on the calendar.
- Remind me in x hours about y subject.

/The RPA Tomorrow Team