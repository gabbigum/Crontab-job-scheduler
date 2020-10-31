mycrontab - a program for managing cron jobs 

Cron is a demon to execute scheduled commands

The five main functions of the program are the following:
 
 1. Display crontab jobs -->Display all cronjobs 
 2. Insert a job --> Insert a new cron job
 3. Edit a job --> Modify existing cron jobs
 4. Remove a job --> Remove any  existing cron jobs
 5. Remove all jobs --> Eares all cron job for the user

Note that you need to have the right privilege order to edit, delete, or add cronjob for a different user.

Special considerations exist when the clock is changed by less than 3 hours, for example at the beginning and end of daylight savings time.  If the time has moved  forwards,  those  jobs  which
would  have  run  in  the time that was skipped will be run soon after the change.  Conversely, if the time has moved backwards by less than 3 hours, those jobs that fall into the repeated time
will not be re-run.

Gabriel Saliev,  Markus Meresma, and David Gábor Uzonyi is the author of mycronjob and original creator of this page.

