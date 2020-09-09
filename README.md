# Board-Infinity

Created a REST API in nodejs with mongodb as database for creating tasks with a duration (in minutes). 
User can insert a todo record with a sample schema like:
- task name
- task description
- creator
- duration
- createdAt
 It have an automatically deleted after the assigned duration. That means if I create a task called "Interview Assignment" with duration set to 30 mins at 1:00pm on 1 January, the record in the database will be automatically removed at 1:30pm on 1st January.

In this I have converted time into min, hr and sec for automatically deleteion of data.
i have commited all the files at same time.
