# GIT & CLI: Assignment

## Brief 

This is a research assignment where students will be given time for research and put into group for discussion.

Version control tools are plenty and have wide range of practices. This research assignment aims to help learners expand their choice of version control tools (Part 1) and being acquainted with the branching strategies best practices in the industry (Part 2).

| Time    | Item          |
| ------- | ------------- |
| 40 mins | Self readings |
| 10 mins | Q&A           |
| 10 mins | Break         |
| 30 mins | Discussion    |
| 30 mins | Presentation  |

### Part 1

Problem Statement: GIT is not the only version control tool in the industry. 

[Reference Link](https://www.softwaretestinghelp.com/version-control-software/) or search online with key word "Version Control Tool".

Discussion Points:

1. What are the version control tools used in the industry?

The various types of the version control systems are:
1. Local Version Control System
2. Centralized Version Control System
3. Distributed Version Control System

2. Why are they being used?

Local version control system maintains track of files within the local system. This approach is very common and simple. This type is also error prone which means the chances of accidentally writing to the wLocal version control system maintains track of files within the local system. This approach is very common and simple. This type is also error prone which means the chances of accidentally writing to the wrong file is higher.rong file is higher.

Distributed version control systems come into picture to overcome the drawback of centralized version control system. The clients completely clone the repository including its full history. If any server dies, any of the client repositories can be copied on to the server which help restore the server.

Version control, also known as source control, is the practice of tracking and managing changes to software code. Version control systems are software tools that help software teams manage changes to source code over time.


### Part 2

Problem Statement: Branching strategy varies largely across companies’ practices and there are not fixed way of doing this.

Reference Links:

- https://launchdarkly.com/blog/git-branching-strategies-vs-trunk-based-development/
- https://www.gitkraken.com/learn/git/best-practices/git-branch-strategy
- https://www.creativebloq.com/web-design/choose-right-git-branching-strategy-121518344

Discussion Points:

1. How many branching strategies are there? What are they?

There are 5 branching strategies. They are;
   a) Trunk Branch - In trunk-based development, the trunk is the central branch to which all developers send their code changes.
   b) Development Branch - The development branch is a long-lived feature branch that holds changes made by developers before they're ready to go to production.
   c) Feature Branch - Often used by a single developer for only their changes, but it is possible to share it with other developers.
   d) Release Branch - This reflects a set of changes that are intended to go through the production release process.
   e) Hotfix Branch - It is used generally to hold changes related to emergency bug fixes.

2. Which branching strategy looks the most practical for you personally?
The answer to which Git branch strategy is the best depends the team’s environment, product and specific development needs.
There is not a one-size-fits-all Git branch strategy, and regardless of which one ends up selecting, it’s likely that one can optimize it with further modifications.
However, of the three Git branch strategies, GitHub flow is the most simple. Because of the simplicity of the workflow, this Git branching strategy allows for Continuous Delivery and Continuous Integration. This Git branch strategy works great for small teams and web applications. As a beginner, it's best to use the simplest strategy for learning. Therefore, Github flow is most practical for a beginner. 

3. Consider the following scenarios, recommend a branching strategy suitable for the scenario, and explain why?
   a. Startup with less than 5 developers
   Feature - Startup have to innovate and create new features for an app/page hence it is most suitable for single team startup.
   b. Startup with multiple small team of developers (3 teams of 3 developers)
   Hotfix - Multiple small teams are flexible to quick to react to minor updates hence hotfix is best suited for these situation.
   c. Startup with no specific team make up. It’s just a group of 8 developers.
   Development - The development branch would sound logical as the process requires many aspects of development. Staging, development and production needs to be laid out properly for the startup project.
   d. SME with multiple small team of developers (4 teams of 3 developers)
   Release - A release branch can be either short-lived or long-lived depending on the strategy. In either case, the release branch reflects a set of changes that are intended to go through the production release process.
   e. MNC & Banking with multiple large team of developers (10 teams of 12 developers)
   Trunk - The trunk branching would be most suitable as it offers foundation to a project and it may be a good way to stabilize the process.


## Submission Guidelines

- Cite any relevant sources consulted during your research
- Solve the problems using your own code
- Do not copy and paste solutions from the source material
- Submit your assignment to black board.
