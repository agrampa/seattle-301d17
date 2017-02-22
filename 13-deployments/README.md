# Class 13 - Deployment with Heroku

####Overview

*The focus of this class is on understanding the concept of production deployments in conjunction with development and production environments.  Through the use of Heroku, students will learn about the deployment process, configuration of environment variables, and general issues that can arise during the deployment phase of a project. Students should also understand development, production, and feature branches and how they are used in collaborative development.*

Song for the day: "Somewhere Over the Rainbow" performed by Ray Charles

- Announcements
	- Project Week is coming!
		- Today we'll continue discussing project ideas *(we'll talk about this after finishing announcements, and look at the related Canvas assignment)* so that we can get a sense of how to scope them, and also develop a list of possible projects.
		- Friday we'll finalize project teams and get Project Week underway! Teams will be able to pick whatever project they want from the list, or propose a new one, as most of you experienced in 201 last month.
	- Let's look at a few recent final 301 projects!
		- [Price I$ Right Parking](http://priceisrightparking.herokuapp.com/)
		- [Barkrawl](https://barkrawl.herokuapp.com/)
		- [Fremont Patroller](https://fremont-bike-patroller.herokuapp.com/)
		- [DroneStrike](https://whendronesattack.herokuapp.com/)
		- [Moviefinder](https://movfinder.herokuapp.com/)
		- [Crime City](http://crime-city.herokuapp.com/)
		- [Find My BikeTown](https://find-my-biketown.herokuapp.com/)
	- Reminder: the entrance exam for the 401 courses (which doubles as the final exam for this course) will be published on Friday afternoon and be available until 11:59pm Sunday.
	- 	If you'd like to schedule a one-on-one meeting with Sam over the next week, please select one of the slots available at [this link](https://sam-301d16.youcanbook.me/).

[**Slides: RESTful endpoints and External APIs**](https://github.com/codefellows/seattle-301d17/blob/master/12-rest-apis/12-REST-APIs.pdf)

- ["How I explained REST to my brother..."](https://gist.github.com/brookr/5977550)
- REST concepts
- RESTful routes
- App state and transition

`BREAK (10 minutes)`

**[Slides: Deployments](13-deployments.pdf)**

- Development vs. Production
- Linux Kernel & Git
- Managing Complexity
- Separation of Concerns
- Environment Variables
- Local & Remote Server Environments

**[Slides: Heroku](13-heroku.pdf)**

- Productivity
- Better Apps
- Trusted Platform
- Deployment Workflow: releases & easy rollbacks
- Logging
- Sharing
- Dynos
- Add-ons

`BREAK (10 minutes)`

**Key question: What to do with the GitHub token?**

- Do not want to push it to GitHub!
- How to make it accessible to a remote server yet still protected?
- `npm i --save express-request-proxy`

**DEPLOYMENT DEMO**

- Let's make a few changes to yesterday's demo and get it deployed!
- More on client-side vs. server-side routing
- How to set environment variables locally and on Heroku

**Discuss the lab assignment for today**

- Look at the README
- Lots of REVIEW items in the code to look at
- Find the TODO items in the code

**Other topics on REST to explore...**

- [Wikipedia: Rest](https://en.wikipedia.org/wiki/Representational_state_transfer)
- [Who the heck is Roy Fielding?](https://en.wikipedia.org/wiki/Roy_Fielding)
- [Make that ***Dr.*** Roy Fielding, whose doctoral dissertation initially defined REST](https://www.ics.uci.edu/~fielding/pubs/dissertation/top.htm)
- [SOAP vs REST](http://blog.smartbear.com/apis/understanding-soap-and-rest-basics/)

--

### Class 13 Readings (to be completed before class)

* [Heroku: Getting Started with Node](https://devcenter.heroku.com/articles/getting-started-with-nodejs#introduction)

* [Deploying a Simple Blog to Heroku](https://howtonode.org/deploy-blog-to-heroku)


### Learning Objectives

* Be able to push a dev site to production, so the world can see it.
* Understand the difference between a static page and a dynamically generated app page.
