# Goal Tracker

## Goal of the tool
- Help user achieve their goals
  - Writing them down
  - Keeping track of them
  - Seeing progress
    - short term (weekly, monthly)
    - long term
  - peer motivation
    - Some sort of sharing
    - competition

## User Stories

### As a User I want to be able to store my goals and the details that go with them
- As a User I want to have a list of goals that I am working on
- As a User I want to be able to add a new goal to my list of goals
- As a User I want to be able to add and edit action items and sub-goals for a specific goal
- As a User I want a place where I can store and edit information on a specific goal that I can look back at
- As a User I want to create a repeating goal resets the action items on a basis that I specify
- As a user I want to be able to prioritize my list of goals

### As a User I want to be able to keep track of my progress
- As a User I want to be able to view my current active goals
- As a user I want to select a Goal and see the specifics of that goal like it's subgoals, action items and notes
- As a user I want to mark action items complete
- As a user I want to be able to mark off goals as complete and be able to see the state it was in when I marked it off as complete
- As A user I want to be able to mark a goal as no longer active
- As a user I want to see a report on how consistent I am at doing my repeating goals
- As a user I want to get a report of all my goals (active, completed, inactive)
- As a User I want to be able to see when I actioned on a goal

## How to
- Storing data
  - mysql lite/file system
  - store locally
    - data lives between program starts and stops
  - Saving locally as Json
  - Code for reading and writing data to disk
    - then putting them in working format (class.. etc..)
- Create a goal list class
  - Functions
    - Add
- Goal Class
  - Function
    - Add action
  - Function
- Actions item (make this a class or part of a Goal)
  - Mark as complete
- user interface
  - Command line

### Make this into jira card (trello)



## Project details
- Terminal app
  - looking for basic functionality first
- Python3
  - A widely used Language that is cross platform
  - The language I used most communally and am most familiar with

### Basic outline
- Basic functionality of the goal tracker
- Running list of goals
  - Add Goal to list
  - Mark a goal as completed
  - Show current active goals
  - Show all goals (completed/active)
- Goal(object)
  - the goal
  - Date created
  - Goal end date (optional)
  - Date completed
  - status (active, complete, not started, failed)


## Meeting Notes
### 3/29/21
- Go over User stories

### 3/15/21
- Talk about the project as a whole
- How I'm going about it
- details of project

- [User Stories](https://en.wikipedia.org/wiki/User_story)
  - structuring outcome in plain english
    - concrete sentence
      - Communicate what the tool does
  - from the users point of view
    - what they should be able to do
      - specific enough
    - define the parameters
  - Dependences on each other
  - Possible problems
    - bring up other things to think about
- Active Record pattern
