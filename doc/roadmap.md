
# Roadmap


##  Milestone 1

Basic abstractions and simplistic stateless jobs.

* Basic Job and JobDef abstractions.
  - JobDef is the code to run, 
  - Job is the process of running that JobDef
  - What you enqueue is a JobRequest
* Job enqueue (pass parameters, indicate which jobdef)
* Job dequeue and execution (decoupled from enqueue)


## Milestone 2

Polish the previous milestone and make the 

* Log activities
* Error handling
* Retry 
* Exponential backoff

## Milestone 2.5

 How do jobs acquire resources? up to each job? up to the containing service?

* Service Lookup and initialization 
  - for example db connections
  - connections to other services

## Milestone 3

* Web app front end
* Standalone service

## Milestone 4

* Distributed workers
