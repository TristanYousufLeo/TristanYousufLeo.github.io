
---
layout: project
type: project
image: img/projects/billiard-ball-number-eight-2650055201.jpg
title: "Magic-Eight-Ball-Server"
date: 1/26/2024
published: true
labels:
  - Python
  - DevLeague
summary: "An experiment with creating and using sockets to connect with other computers"
---

<img class="img-fluid" src="../img/projects/billiard-ball-number-eight-2650055201.jpg">

This project, albiet a very small one, was an interesting dive into learning how computers talk to one another. This was back in my DevLeague days during high school, where my interest in computers had picked up steam and where I started to formulate what I want to do in life. Despite the relative compacted nature of this project, this one had taken a lot of my time as not only was I dealing with functions that we had never dealt with before in DevLeague, but my continued interest in the way computers connected to one another drove me to continue the project despite a lot of setbacks and roadblocks along with other developing projects during my time in DevLeague.

The project imports the socket and sys libraries from Python first before opening up the ability to input the host computer's IP address and opening up port 45000, which is a common port for communication. This is where the program creates a socket and attempts to connect to the IP address of the computer in question. Failing that, it would output an error message and then exit from the system. If it succeeds in establishing a connection, it would display a message saying that it successfully connected.

While this project was a minimalist one at best, I felt like I learned a lot about sockets and ports and how computers utilized themw when they want to talk to each other. I may revisit this project and see what I could add to it at some point in the near future.

Source: <a href="https://github.com/TristanYousufLeo/Magic-Eight-Ball-Server"><i class="large github icon "></i>TristanYousufLeo/Magic-Eight-Ball-Server</a>
