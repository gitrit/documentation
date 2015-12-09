#LearnVCS Design Document

##Abstract
This document describes the design of the learnVCS project. It outlines the goal of the project, the target audience, and the constraints, and in doing so allows us to design the best project within those limitations.

##Mission Objective
Version Control is an important part of development, but it can be very difficult to grasp when you're first starting out. School is a great place to learn about this before entering the real world, but as of now it is not being given much focus. The goal of this project is to __give students a resource they can use to understand Version Control concepts and give teachers a resource they can use to integrate Version Control lessons into their presentations.__

##Constraints
1. __The product should be easy to integrate into professors existing lessons.__ Redesigning the IGM curriculum would be a major undertaking that is beyond the scope of this 5-month student project. We should focus on making a product that can be integrated into existing lessons, such as extra slides that can be inserted into existing presentations.

2. __The product should consist of a single page.__ If a person were to stumble on this site, we would want them to be able to find exactly what they are looking for with minimal effort. They should have to click around the site to find something basic. As such, the site should consist of a single page with all of the information laid out in an easy to understand manner.

##Target Audience
__Professors__ - Because this product is intended to be integrated with the IGM curriculum, professors are very important. The product should be easy to demonstrate in front of a class of students. Additional materials, such as slides to use in presentations, would also be helpful.

__Newcomers to Version Control__ - This product is intended to be used to teach version control to IGM students, but in theory it should be accessible to anyone interested in learning version control. It should be accessible and easy to understand, even if the person has never used version control before. 

##Resources

LearnVCS will collect multiple resources together in a single, easily accessible location. The following section contains a list of the resources we will provide. 

###Git Graph

####Dependencies:
 - React
 - React-Commits-Graph
 - A sample app to demonstrate graph
 
####Purpose
The purpose of this section is to demonstrate principles of version control. It does this by displaying a git tree of a repository hosted on GitHub.

####Initial State
Initially the graph that is displayed will be the commit history for a simple console application. The sample application is designed to effectively demonstrate version control principles through its branching model and quality commit messages. The sample application is hosted on GitHub, but the commit information is stored locally as a JSON file for faster loading, and in the event that GitHub is down. __GitHub support must not be required in order to get the most out of this interaction.__ The sample application will be a simple CLI calculator program, written in C#, though the actual form of the application for is incidental. 

####Loading a Graph
Given a git repo hosted on GitHub, it retrieves the commit info and displays it as a git graph. By default, it displays the commit information of a calculator application that was made for this project. This project has commit messages that are designed to be descriptive of the version control process.

###Why Use Version Control?

####Purpose
The Purpose of this section is to highlight some of the main reasons why people may want to use version control in one of their projects. By doing this, we hope to convince people to use it if they are on the fence. The things we want to highlight are __version control's ability to track file changes over time,__ __version control's ability to make collaborating among multiple people easier,__ and __version control's ability to store a working backup of you project__

###Learn Git

####Purpose
Our graph can illustrate some concepts of git and give a basic overview, but it is outside the scope of this project to go in-depth on these topics. This section will be link the User to outside resources which cover these topics. Of note should be the Atlassian Documents, which provide a detailed overview of basic commands, and the Git Book, which provides more in-depth coverage.

###Find Out More

####Purpose
While the project is focusing on Git, we want to acknowledge the fact that there are more version control systems, since the User may very well end up using them in the future. The purpose of this section is to link to outside resources about the different version control systems and provide a brief description of them.

###About

####Purpose
The Purpose of this section will be to credit the people who made the site and link to their other work. Since it isn't immediately related to version control, it should be more out-of-the-way. 


##Style Guide

