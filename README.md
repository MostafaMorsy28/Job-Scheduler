# Job-Schedular

This project simulate in-process crons scheduler implemented in Java.

## Main Concept

### The program has 3 main classes which are Job, Job Scheduler and Job Logger.

- Job: an abstract class which has some data about job for scheduling and pure function for execution which will be implemented by derived classes.
- Job Schedular: it's main purpose is to shedule the jobs executions.
- Job Logger: simple logger class that logs when the job starts and ends.
