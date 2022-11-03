# COEN346-Assignment2

## Simulating Fair-share Process Scheduling
### Problem statement: 
Implement the simulation of a process scheduler that is responsible for scheduling a given list of processes that belongs to a given list of users. The scheduler is running on a machine with one CPU. 

The scheduling policy is type of fair-share scheduling and works as follow:

- Several users may exist in the system and each user may own several processes.
-  Scheduler  works  in  cyclic  manner.  This  means  that  in  each  scheduling  cycle  it  distribute  a  pre-
defined  time  quantum  of  CPU  between  different  users  and  processes.  The  first  scheduler  cycle will start at second “1”.
-  At  any  scheduling  cycle  the  scheduler  distributes  the  time  quantum  equally  between  different
users that have at least one process ready for execution. -  Furthermore,  the  scheduler  distributes  each  user’s  time  share  equally  between  processes  that
belong to that user -  The  order  which  the  processes  will  be  scheduled  in  one  cycle  is  not  important,  i.e.  there  is  no
priority on users and processes.
