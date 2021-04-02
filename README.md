# HW4-DevOps

**Unity Id:** stallur2

**Name:** Sruthi Talluri 

## Class activities

Describe your discussion for testing.

1. What are some tradeoffs in having lots of unit tests and/or UI/integration tests in a CI pipeline?
2. What are some reasons why 100% test coverage (i.e. statement coverage), might be difficult, impossible, impractical, or even counter-productive to achieve in practice.

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

```js
function demo(a,b,c) {
   if( c && b ) { c = b * b; }
   else if( a )
   {
      if( b )
      {
         if( c )
         {
            console.log( a + b + c );
         }
      }
   }

   if( a || b || c )
   {
      return 0;
   }
   return 1;
}
```


### Workshops

* Document completing the Coverage workshop.
* Document completing any two of the following workshops. 
   - Test Suites
   - Fuzzing

