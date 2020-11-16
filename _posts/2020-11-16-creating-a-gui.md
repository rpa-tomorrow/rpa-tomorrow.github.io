---
layout: post
title:  "Work-in-progress Creating a GUI Application (Part 1)"
date:   2020-11-16
categories: rpa-tomorrow blog 
---
There is now a work-in-progress graphical user interface (GUI) application as an alternative to using the CLI.
Note that this GUI is an early prototype and is not finished, the final product may look and function differently from what is written and shown in this post.

For non-programmers who might use this software it was important to make sure there is a solution that is easy to use.
With a graphical user interface there are more opportunities to visualize things since it is not restricted to only viewing text like the CLI.

![GUIThemes](/images/guithemes.png)

This is the current design of the user interface and there are multiple views in this GUI that are indicated by the icons to the left of the window.
In this image the design view is currently opened is only explored in this post since it is the most developed one.
There are multiple themes both dark-theme and light-theme, is also possible to easily extend this to include more themes but for the time being the focus is on these two.

![GUIExample](/images/guiexample.png)

This example image above shows the process query `send email to John saying hello world`. In the visualization view below we can see two rectangles these are called process blocks and can hold some data and information about what kind of automation task it will perform. Every process starts with the main block which only is there to signal where the process will start and then connected from main there is another block for sending the email wich comes from the process query written above. These process queries are then executed in sequence as they are connected. Blocks can be disconnected and reconnected and also removed or altered via directly interacting with the blocks in the GUI. The position of each block is also stored even though it carries no semantical meaning it is used to later recreate the process the way it was laid out. There are more features here in the works, see issue [#134](https://github.com/rpa-tomorrow/substorm-nlp/issues/134) for more information

/The RPA Tomorrow Team

