Interactive Git Graph View
======================
Introduction
------------
The purpose of the interactive Git graph view is to allow students to understand the chronological and branching flow of commits to a repository. In addition, it will serve as an example for good commit message formatting and other good Git practices. 
Goals
-----
This feature aims to appeal to haptic learning styles by providing a space to better understand how branching benefits a project, without recreating something like an interactive shell (like [trygit](https://try.github.io/) does).  
Specifications
--------------
* The interactive Git graph view will be supported by [React-Commits-Graph](http://github.com/gitrit/react-commits-graph), a React and SVG-based display system for commit trees that supports mouse events.
* Scope
  * This feature is restricted to Git trees only.
  * The Gitgraph tree must be created manually. 
  * Parsing from Github API must be performed manually in order to build a usable tree. 
  * What problems does this feature not solve?
* Implementation
  * Load branches from repo using [Github API](https://developer.github.com/v3/repos/#list-branches)
  * Load commit json for each repo from repo using [Github API](https://developer.github.com/v3/repos/commits/)
  * Add commits to the CommitsGraph element in React.render
* Dependencies
  * React.
* Overhead
  * CPU, memory, browser requirements have not been tested.
  * The library is 16kB in size.
* Performance/Scalability
  * This has not been tested.
Use Cases
---------
* Pending
UI flow
-------
A visual mockup of the feature (Pending)
