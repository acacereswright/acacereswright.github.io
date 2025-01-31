---
layout: page
title: Projects
---

### Simulating Trading Models

As part of my Computational Investment course, I worked to develop a simple trading model and test it in various ways. A secondary goal of this project was to test out different backtesting libraries. This was a group project with contributions from individuals with both economics and computer science backgrounds emphasizing both interdisciplinary communication as well as developing an understanding of both programming and economic concepts.

We developed two basic trading models and implemented them in python, using various backtesting models such as backtesting.py, zipline, and quantopian to determine model performance. Data was drawn from the companies currently listed on the S&P 500 index. For each company we drew weekly data for the last 20 years. Using this information, we were able to report results on different levels such as individual or groups of stocks, different sectors (as listed on the S&P), and the overall S&P index.

### Museum Interactive Experience

This was completed as my master's capstone project. It was a full stack web application developed for the Niagara Aerospace Museum. Designed primarily to allow museum patrons to complete a scavenger hunt using a smart phone, it also could serve as an inventory system for museum curators as well.

On the patron side, each participant is able to specify a level of difficulty and the length of time, and are presented with a subset of available questions based on their choice. To solve each clue the participant would tap their phone on an Near Field Communication (NFC) token nearby each exhibit, and would be presented with immediate feedback. Once all clues were satisfied the player is able to see how long their hunt lasted and are asked if they would like their score to be submitted to the leaderboard.

On the Museum Curator side, each curator is able to enter scavenger hunt clues as well as exhibit information. Once an item has been entered into the system, curators are also able to edit it's information, including marking items as active or not, which indicates if they can be presented to patrons or not.

### Financial Literacy Application

This was an application developed at UBHacking, an annual 24 hour hackathon run at the University at Buffalo. My group chose to create a Financial Literacy Application designed to consolidate information that new immigrants may find useful when they arrive in the United States. Such information could include different types of bank accounts and credit cards and how to open them, as well as information related to the FAFSA and other scholarship information.

For more information about the hackathon please [click here.](https://devpost.com/software/something-catchy)

### Research Project in Cognitive Systems

As part of my undergraduate coursework I was required to complete a research project, which I conducted in the [Center for Applied Moral Psychology](https://sharifflab.com/) at the University of British Columbia. My project was in the areas of moral and privacy psychology, and was focused around how the level of privacy affects a person's altruism. To do so, I coded a variation on the public goods game using python and a framework designed for economic games called oTree. Once my program was developed I then deployed it to Heroku, a web hosting service, and ran several instances of the game to collect data. Once this was done I wrote a report discussing previous work in the area, as well as analyzing and discussing the data I had collected.

If you'd like to view a copy of the final report you can [view it here.](documents/Caceres-Wright_undergrad_capstone.pdf)

### Pintos: Simple Operating Systems

As part of a course in operating systems, I developed multiple parts of the [Pintos Operating System](https://web.stanford.edu/class/cs140/projects/pintos/pintos_1.html). Main areas of focus included Scheduling Algorithms, User Argument Parsing, system calls, as well as some basic memory management.

### Text Chat Application

As part of my networking course, I had to develop a simple text chat application involving implementing several important network functions on both the server and client side over TCP connections. Important functions included IP address identification, viewing a list of logged in clients, and blocking and unblocking other clients. Along with this, it supported sending and receiving between clients, and messages to logged out clients would be stored and delivered upon next login.

### Internet Packet Transmission Protocol Simulator

As part of my networking course, I had to implement several different packet transmission protocol protocols such as selective repeat and go-back-n protocol. This project involved ensuring accuracy in delivering packets, both in terms of order and contents. This involved having a deep understanding of the relevant network protocols as well as how to utilize checksums. Once implemented, I analyzed performance via tests and summarized my findings via a report.

### Lossy Image Compression

This was a project completed in my undergraduate coursework designed to algorithmically change images by partitioning images in such a way that the color variability within each partition is minimal while maintaining color distinction across partitions. To do so each pixel must be looked in within a variety of partitions before the program decided the optimal partition and returned the altered image.

### Book Management System

I wrote a basic book inventory and management system for my software construction course. This project was written in Java and allowed users to input information on books such as title, author, and number of pages. Along with this, users were able to enter information such as if the had lent the book to a friend and track how long it had been lent out. It also gave users the ability to save and load their information across multiple sessions. Additionally, I developed a simple graphical user interface(GUI) using the JavaFx library.  