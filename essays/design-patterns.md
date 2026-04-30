---
layout: essay
type: essay
title: "Patterns in Practice"
date: 2026-04-29
published: true
labels:
  - Software Engineering
  - Design Patterns
---

<img width="300px" 
     class="rounded float-start pe-4" 
     src="../img/design-patterns/locks.png" >

## Unlocking Design Patterns

Once in your lifetime you have probably needed to secure your belongings whether that be your phone, bag, or household. This is a general problem that has many different solutions such as locks, alarm systems, stationing guards, etc. The solution one chooses depends on the context of the problem. Let’s say we simply need to secure our backpack in a locker. Naturally, the best solution to choose would be a lock. However, this can then be broken into more choices. Do we prefer a physical key that may be inconvenient to constantly pull out, another number code to remember, or maybe having to recall a series of up, down, left, and right on a directional lock. This scenario is what is considered a design pattern: Standardized solutions — or patterns — to a recurring problem that can be adapted based on context. In this case, the recurring problem is securing belongings while the lock is one such pattern. This pattern can then be changed to further fit any specific scenario. In the world of computer science, there are many recurring problems with several template solutions. 

## A Few Common Patterns

First off, there is the Factory Method. This is an interface for creating objects even from different classes. This promotes flexibility when creating objects and allows for an easy way to add additional object types to the factory without breaking the code. Next is the Singleton Pattern, which provides one instance of a class globally making it easier to control the access and behavior of a class over the program. The Observer Design Pattern uses event handlers to inform observers — objects that react to state changes — about the current state of the object they are watching (the subject). One last example is the Model-View-Controller (MVC) Design Pattern that divides an application into three connected components. The model encapsulates the current state of the application where it is rendered by the view. The view sends user input to the controller where the input is interpreted and updates to the model are supplied. 

## How I have used Design Patterns

Although prior to this essay I did not know about design patterns, I have consistently used them in my own coding projects. One such project is a website for promoting recycling on the UH Manoa campus by providing a map with recycling locations, general recycling information, and local statistics. This project demonstrates MVC through an integration of React and Prisma. Prisma aids with storing information about the announcements, user, and recycle bin locations acting as the model. The view is done through React where pages are presented to the user and dynamically updates information based on the current state of the model. Lastly, a file named dbActions.ts acts as the controller by updating database information when users fill out forms. Moreover, this project exhibits an Observer Design Pattern through event listeners. For example, when users interact with the pins on the map, additional information is presented since the state of the map has changed. In this case, the map pins are the subjects and the information to be displayed are the observers. Just these couple examples of how I have used design patterns showcase their impact on application development.
