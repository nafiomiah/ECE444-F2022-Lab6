# ECE444-F2022-Lab6
TDD Lab for ECE444

In this repo, I replay the examples and follow the instructions of the following repository:  https://github.com/mjhea0/flaskr-tdd

## Adding Unit Test to Project 1:

Link to Test: https://github.com/ECE444-2022Fall/project-1-web-application-design-education-pathways-group-21-ninjas/blob/docker-prep/Education_Pathways/tests/test_app.py

![image](https://user-images.githubusercontent.com/59378799/203197068-dcfc4c77-895d-4d8e-8a3b-a8a20370b3b8.png)

## Pros and Cons of TDD

Test Driven Development (TDD) has its pros. One pro is that TDD promotes good design practices as it leads to the development of modular code. This is because you focus on the development of a sub-feature at a time.  Also, it makes small errors easier to find, and thus defects/bugs are limited. This prevents a lot of time from being wasted in debugging during later stages. TDD also restricts developers to only write code that is necessary as they would need to stop writing implementation code once tests are all passed. TDD helps make the collaborative coding experience less difficult as developers can make changes to code written by other developers and run tests to know the impact of their changes. TDD also imposes that unit tests are written prior to writing actual implementation code. This aids in the refactoring process allowing a developer to refactor with more ease and efficiency as they know the code passes certain tests. TTD also aids developers into understanding the code more thoroughly. TDD is beneficial when adding new features or applying bug fixes as these changes can be done more easily and efficiently with existing tests.  TDD also promotes having good interfaces between different components of a software application as the interfaces must be in a manner that is testable. TDD also encourages a team to have clear requirements from the start to know how to begin writing tests. TDD also allows for better documentation as the tests can serve as documentation that demonstrate how code component is used. 

Furthermore, there are some cons to Test Driven Development (TDD).  One con is that TDD can be tedious and can slow down the development process. The actual code cannot be written until tests are done being written. Also, another con is that that the tests must be maintained. As product requirements change, the tests associated to those requirements will also first need to be changed before making changes to the implementation code. TDD also requires an entire development team to cooperate with each other and maintain their tests to allow TDD to work well and prevent the system from breaking down. TDD can also be difficult to apply on legacy code. Lastly, TTD will not be able to find bugs that are introduced in the testing that leads to bugs in the implementation code. 
