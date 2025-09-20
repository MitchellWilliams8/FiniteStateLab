# FiniteStateLab
Finite State Lab Project for CS439

# Introduction
This project is an interactive text based adventure game titled "Silent Ship". It follows the story of someone who has woken up on a ship in space with no memory of how they got there. The goal is to explore the ship and piece together the mysteries of what happened to the crew and how you got there. This game has 15 nodes and 4 different endings. The purpose of this project was to explore the concept of Finite State Machines in game development.

# Technical Framework
This project was created using Twine which is a tool for creating interactive stories and switching between states. The core components of Twine that were used were:
- Passages: These are the individual story nodes that you switch between.
- Linking Brackets: These allow you to navigate to the different nodes.
- Variables and conditionals: There is a boolean variable used that determines what happens next depending on if it is true or false.

# Installing and Running the Project
To run the project simply download the Silent Ship html file and open it in your browser. Additionally the Silent Ship twee file is included which can be opened in twine and ran there as well.

# Node Storage and State Switching
In Twine each node is called a passage which includes text, links, and logic. These are all stored together in a single html file for the final project. Twine has a built in linking system that alows you to switch between nodes. This linking is formatted with double brackets and the link text followed by a passage name. cliking the link text will then take you to that passage or node.

# What I learned
This project allowed me to be able better grasp the concept of a Finite State Machine and state switching in general. Applying those concepts to something like a text based adventure was a greate way to be able to fully picture these topics. In this example each passage is a state and the choice the player makes allows switching between these states. The variable that is stored represents how memory can be stored in a Finite State Machine which was an interesting thing to see.

# What I'm Proud Of
The part of this project I am most proud of is using a boolean variable for the conditional ending. I initially knew I wanted to have multiple endings and this was a cool yet simple way to accomplish that. I was able to turn two choices into four distinct endings which is pretty cool.

# What I Would Like to Add
One of the things I think would be cool to add would be a inventory system. Variable could be used to track items that could unlock new parts of the ship or allow for different choices. An additional thing to add what be some visuals or even just css styling. I think this would add a lot of depth to the story for the user.
