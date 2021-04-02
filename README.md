# HW4-DevOps

**Unity Id:** stallur2

**Name:** Sruthi Talluri 

## Class activities

Describe your discussion for testing.


![ClassDiscussion](https://media.github.ncsu.edu/user/16063/files/ae361480-933d-11eb-9a2a-8856c290a82d)

I joined the us-east-1 channel at 2:00 pm on Tuesday(03/09/2021) and discussed about the below topics.

1. What are some tradeoffs in having lots of unit tests and/or UI/integration tests in a CI pipeline?

   Finding errors in modules is easy. Maintenance of unit test is cheap. It pays attention to the behavior of single modules

2. What are some reasons why 100% test coverage (i.e. statement coverage), might be difficult, impossible, impractical, or even counter-productive to achieve in practice.

   Even if it were possible, it’s likely to be so labor-intensive that you’d get more value from your software development efforts elsewhere. Even if you attained 100% coverage, it doesn’t mean that the software actually works. Maybe you attained 100% line coverage but missed a branch. Coverage can’t tell you about code that doesn’t exist but should. Making 100% code coverage the target can encourage counterproductive behaviors. Maybe you warp the code to facilitate testing (“test-induced design damage”). 

### Conceptual Questions

1. What are the two different senses of testing and how do they differ?



2. What is the goal of code coverage?

3. Does condition coverage imply branch coverage? Why not?

4. Why might be data-flow coverage be a more effective criteria for testing than achieving path coverage?

5. What is the primary limitation of mutation coverage?

6. How can an acceptance test be automated while still allowing human review?

7. Why might the failure rate of a test be useful to know when analyzing a test suite?

8. What's the highest level of flakyness a test can achieve and why? Hint: Think what behavior are purely random decision would be?

9. What is the difference between generative and mutation-based fuzzing techniques?

10. Why might minification of fuzzing inputs be useful for debugging an fault?

11. Why regex isn't enough for performing static analysis?

12. When implementing a code smell detector, how might you detect duplicated code?

13. Why is an visitor pattern using technique for writing static analysis based code checks?

14. How might advanced analysis techniques such as statistical analysis or automated program repair impact the design and usage of an automated software pipeline?


### Coverage Calculation 

Calculate the branch coverage of the following test suite:
   - demo(1,1,1);
   - demo(0,0,0);

The coverage for the above test suite is: 

1. Statement Coverage - 7/10 (70%)
2. Branch Coverage - 10/15 (66.67%)
3. Functions - 1/1 (100%)


### Workshops

* Document completing the Coverage workshop.

Please find below the images depicting the completion of Coverage Workshop: 

![CoverageWorkshop](https://media.github.ncsu.edu/user/16063/files/aeceab00-933d-11eb-939c-a13cd413dee4)

![CoverageWorkshop2](https://media.github.ncsu.edu/user/16063/files/b42bf580-933d-11eb-9a26-f7a131ba4a76)

* Document completing any two of the following workshops. 

Please find below the images depicting the completion of the Workshops: 
   - Test Suites

   ![TestSuites](https://media.github.ncsu.edu/user/16063/files/b55d2280-933d-11eb-9644-a5e44aacb96a)

   ![TestSuites2](https://media.github.ncsu.edu/user/16063/files/b5f5b900-933d-11eb-8342-783301a9df88)

   ![TestSuites3](https://media.github.ncsu.edu/user/16063/files/b68e4f80-933d-11eb-9407-a2fbf7820147)   

   - Fuzzing

   ![Fuzzing](https://media.github.ncsu.edu/user/16063/files/b7bf7c80-933d-11eb-88a3-8d1dee6b6ee4)


