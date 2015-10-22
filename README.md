# AIDeer-Overview

This project will aim to create a series of intelligent software agents with simulated 
embodiment that are designed using scientific insights into the nature and function of
human and animal consciousness.  The goal is to create software agents that pass a “consciousness test”
or ensemble of consciousness tests (as yet undefined) analogous to the Turing Test for human
level artificial intelligence. 

The focus of the project is on achieving artificial consciousness and not directly on building
strong artificial intelligence.  We will create only as much artificial intelligence as needed
to demonstrate consciousness. It is anticipated that the required level of artificial intelligence
will be very much less than “human level” artificial intelligence.

While not a direct goal of the project, it is possible that some of the constraints put upon an artificial
intelligence by attempting to make it “conscious” (such as  single threaded consciousness and small
integer working set size), will result in a “sweet spot” in pruning the combinatoric explosion that plagues
inference and induction.

#Basic Architecture

AIDeer consists of three main elements that exist as seperate Github repositories:

  - AIDeer-Unity3D, a Unity3D Project provides a game "world" that our AIDeer exists in.

  - AIDeer-Opencog, a python program that uses Opencog python bindings to create a "mind" for our AIDeer.

  - zmqswitch, a python program implements a switching point between potentially multiple Unity GameObjects and multiple AIDeer-Opencog programs.

ZeroMQ is used to communicate between the elements.

My current implementation runs on two machines connected by an ethernet gigaswitch.

![Architecture Diagram](http://i.imgur.com/vOMVw6K.png)
