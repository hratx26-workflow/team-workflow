# team-workflow
Project Name
Product Description
__________________________________________________________________________________________________________________

Team Members

Project Owner: Trace

Scrum Master: Guillermo

Development Team: Michael


Stretch Goals
List Stretch goals here
  -to be better than guillermo

Stack
  -c++
  -assembly
  -c#

Individual Goals

Trace:
  -Really wants to get better using databases, it would also be great to beef up their skills in React. In charge of the app authentication, front to back.
Guillermo:
  -Feature and goals...
Michael:
  Feature and goals...

Workflows

Git
## update your master branch
git checkout master
git pull --rebase upstream master
git push origin master

## start work on a feature
git checkout -b feature-branch

## write code, commit, repeat
git add .
git commit 

## rebase before pull request
git pull --rebase upstream master

## push to a feature branch on YOUR fork
git push origin feature-branch

## make a pull request on GitHub

## if pull request is rejected
## fix bugs, commit
git add .
git commit
git pull --rebase upstream master
git push origin feature-branch

## make a pull request on GitHub

## if pull request is accepted
git checkout master
git pull --rebase upstream master
git branch -d feature-branch


Waffle (Backlog)

Backlog
  A list of future tasks and ideas
  Should be continuously updated

  Ready
  Updated at the beginning of every sprint
  Contains all of the tasks being worked on for the current sprint

  In Progress
  Move a task from ready to in progress when you start working on it
  When you finish a task, write closes #{issue-number} in a commit or in a pull request comment.
  Done

  When a pull request is merged that contains closes #{issue-number} in either a commit message or in the pull request’s comments, the issue will be automatically closed in GitHub, and the task will be Moved to the done column in waffle.

Stand-Up Schedule
Below is an example of your stand-ups should look for each two day sprint. Take some time as a group to figure out the best structure for maintaining consistent and open communication. Creating an established stand-up structure at the beginning and sticking to it will be invaluable to your team as you progress through the project. If you are using a project management tool like Waffle, be sure to incorporate that workflow here.
Day 1
Morning Stand-Up & Sprint Planning
What is the main focus for this sprint?
What can be added to the backlog?
What are the individual goals for this sprint?
What files will everyone be working in?
Where do we expect to be by the end of Day 1?
Evening Stand-Up
What was accomplished today?
What obstacles did we run into today?
What does everyone anticipate Day 2 to look like?
Do we need to scale this sprint up or down?
Day 2
Morning Stand-Up
What is everyone working on today?
What files are everyone working in?
What needs to get done to meet sprint goals?
Sprint Retrospective
What did everyone accomplish on Day 2?
Were the sprint goals met?
Where can we foresee any future issues?
Does anything need to roll over into next sprint?

Sprint Log
Use this area to keep track of all of your sprints. Be as thorough as possible!

Sprint Dates
Sprint Goals
Individual Goals
11/01 - 11/02
Create schema
Set up the database
Set up user authentication routes

Team Member A
User authentication routes
Files: server/user-routes.js

Team Member B
Users controller
Files: db/user-ctrl.js

Team Member C
Set up server index
Files: client/index.js

Team Member D
Front end authentication
Files: server/index.js




