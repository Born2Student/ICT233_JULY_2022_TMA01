# ICT233_JULY_2022_TMA01

**ICT233 Data Programming July 2022 Semester Tutor-Marked-Assignment (TMA01)**

**Question 1 (46 marks)**

**Objectives:**
+ Understand dataset with data scientist mindset.

+ Understand and design computation logic and routines in Python.

+ Assess use of Python only and Python data structures to perform extract, load, and transformation operations.

+ Assess use of Pandas dataframe to perform extract, load, transformation and calculation operations.

+ Structure code in appropriate methods (functions), looping and conditions.

+ Conduct visualization in an appropriate way.

There are 4 synthetic datasets which capture the project management data of an organization.

1. users.csv: contains a set of users. Each row contains (id, first_name, last_name).

2. teams.csv: contains a set of teams. Each row contains (id, name) with name being the name of a team.

3. tasks.csv: contains a set of tasks. Each row contains (id, description, assignee, sprint, team, story_points).

**Column name | Description**

**id:** The task ID

**description:** The task description

**assignee:** The user ID of the person who is assigned to work on the task This column references the id column in the users.csv.

**sprint:** The sprint id, for example, 1 is the first sprint in Scrum project management framework.

**team:** The team ID which the task is owned. This column references the id column in the teams.csv.

**story_points:** The Scrum story points represent the effort / complexity of the task. The larger number of story points is, the more effort required to complete the task by the assignee is.


4. state-transitions.csv: contains a set of state transitions of tasks. Each row contains (id, task_id, state). Whenever a task changes its state, there is a corresponding row in the csv. The valid state transitions are captured in the following diagram.

![alt text](https://github.com/Born2Student/ICT233_JULY_2022_TMA01/blob/main/Task_State_Change_Diagram.png?raw=true)

Note that, the arrows in the above diagram indicate valid state transitions. No arrow from done to implementation mean the transition from done back to implementation is not allowed.



