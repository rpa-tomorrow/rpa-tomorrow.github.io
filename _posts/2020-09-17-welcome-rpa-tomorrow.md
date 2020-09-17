---
layout: post
title:  "Introduction to RPA Tomorrow"
date:   2020-09-17
categories: rpa-tomorrow blog 
---
Welcome to the RPA Tomorrow project blog!

The purpose of RPA Tomorrow is to create a proof-of-concept robot solution where given a task from a user in written form, will be
able to interpret, process and execute it. The system aims to support a small set of use cases, but it will have to be implemented
in such a way that future extensions can easily be developed for it. The plan is to have a working solution in December 2020.

The project goals are:
* Interpreting tasks correctly with natural language processing (NLP) 
* A front-end for the user to input text and receive feedback from 
* Design an API for extensions
* Integration with the OS 

The use cases the first iteration of the system we are aiming to complete are:
* Send and write emails to contacts, given their names or addresses
* Update calendars and set reminders for the user, as well as tagging other users in them
* Find and move files for the user on their computer

Due to time constraints we limit ourselves Linux and only support CalDAV supported mail providers and calendars.

The source code of this project will be available [here][rpa-repo].

/The RPA Tomorrow Team

[rpa-repo]: https://github.com/rpa-tomorrow/substorm-nlp
