mycrontab - a program for managing cron jobs 

Cron is a demon to execute scheduled commands

usage  ./mycrontab
Command-line argument, not available

The five main functions of the program are the following:
 
 1. Display crontab jobs -->Display all cronjobs 
 2. Insert a job --> Insert a new cron job
 3. Edit a job --> Modify existing cron jobs
 4. Remove a job --> Remove any  existing cron jobs
 5. Remove all jobs --> Eares all cron job for the user

In the insert job and edit job if you do not want to specify  timing please write "unspecified"

Note that you need to have the right privilege order to edit, delete, or add cronjob for a different user.

	Insert job and Edit a job  does not cover special cases such as 
	Value list separator “,” 
	Range of values - 
	Jobs that which can execute every X hours/day etc. 


Gabriel Saliev,  Markus Meresma, and David Gábor Uzonyi is the author of mycronjob and original creator of this page.