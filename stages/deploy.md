# __RACIVS matrix for DevOps Pipelines__   

<img src="https://user-images.githubusercontent.com/10748736/112030685-6c81be80-8b32-11eb-94b8-c2c01b8f4581.png">

## __Pipeline stage:__  Deploy  
### __Stage description:__  
Insert your description of the stage here
  
| Pipeline Stage:<br>Deploy                                      | Developer  | Product Owner  | UX Designer  | Senior Developer          | Lead Dev (6 teams to manage)  |
|--------------------------------------------------------------- |----------- |--------------- |------------- |-------------------------- |------------------------------ |
| Local Deployment for internal testing                          | R V        |                |              | A S                       |                               |
| Version Control - For Rollbacks                                | I          |                | I            | R                         | A S                           |
| Integration - Works with dependencies in production enviroment | R          |                | R            | A V                       | S                             |
| Acceptance - All users happy with release for deploy           |            | S              |              | S                         | S                             |
| Docker/Server Build                                            | R          |                | C            | C V                       | A S                           |
| Canary Launch to verify stability                              | R          | S C-Feedback   | I V          | A V                       | S                             |
| Blue-Green/Production Deployment                               | I V        | C S            | I            | R                         | A                             |
 
  
  
[Home](../index.md)  
