---
title: Planning the Game
draft: "true"
description: 
tags:
---


# Getting Started

#### 1. Choosing a Programming Language
Choosing a Language is important and you need to think about how this will affect the end user. Some [[#2. Choose a Development Framework|frameworks]] will have built in programming languages that may be better suited, however will not help you outside of that program. Frameworks such as [[Godot 4]] uses GDScript and although it is very similar to Python, you will not be able to use this language in other applications.
- **Python** - has a lot of libraries for quick development
- **JavaScript/HTML** - If you want to run it in a browser
- **C# with unity** - has the ability to give more interactivity, however, you will need to learn the program on top of learning a language. You will also need to keep in mind that C# is .Net and therefore you will need to use a windows computer to compile the code.
- **Rust or C++** - if you are worried about performance or just want a challenge
- This will likely be best if we make a program using Python that can be deployed to [Steam](https://store.steampowered.com/) or [Itch.io](https://itch.io/)
#### 2. Decide on Game-play Mechanics
There are a few options for small text-based or choice based adventure/horror games that you can expand upon, but you will need to choose the mechanics before choosing a framework to build your game.
- Will it be choice based?
- Do you want RPG elements? (inventory, stats, combat)?
- Will it be a [[parser-based game]]?
- Will there be random elements for replay-ability?
#### 3. Write a Story Outline
Writing a story outline can help you better plan the overall game and how you can implement it with different softwares. For example, if you want to build a triple A title, yo u probably do not want to use [Ren'Py](https://www.renpy.org/) as your application of choice.
- Think of scary settings
	- Haunted house
	- abandon spaceship
	- cursed town
	- unseen forest
	- looping house
	- **mountainous abandoned town**
- Define player choices and consequences (this could be made into multiple endings)
- Sketch out a story flowchart to track differing paths
#### 4. Choose a Development Framework
This one is more optional because you can always make a terminal based application or you can build everything using the python libraries, however choosing a framework can help you streamline the process. Here are a few popular options:
- **[[Godot 4]]** - A FOSS community driven 2D and 3D game engine. This can be installed on linux unlike a lot of the other applications
- **Ren'Py** - This is a visual novel engine which could be good for some use cases. 

#### 5. Start Coding
Just start coding the project. You can start with something as simple as this python script and expand from there:
```python
print("You wake up in a dark room.")
choice = input("Do you light a match? (yes/no) ").lower()
if choice == "yes":
    print("The room is empty except for a locked door.")
else:
    print("You hear breathing in the darkness...")

```
#### 6. Add Atmosphere
- **Add audio** - Adding audio for suspense 
- **Delays** - using `time.sleep()` for suspense
- **Randomization** - For replayability or simply keeping things unpredictable
#### 7. Monetize it
- Sell on Itch.io (perfect for indie games)
- Patreon (offer early access or exclusive content)
- Steam (takes a lot of effort but can be worth it to reach a larger audience)
- Advertisements (Show advertisements in game while the user plays or offer rewards for watching ads)
