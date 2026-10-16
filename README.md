# Number Theory: Subtraction

In this lab you've learned the basics of number theory as it relates to subtraction.

## Rubric

| Item | Description | Value |
| ---- | ----------- | ----- |
| Summary Answers | Your writings about what you learned in this lab. | 25% |
| Question 1 | Your answers to the question | 25% |
| Question 2 | Your answers to the question | 25% |
| Question 3 | Your answers to the question | 25% |

## Names
Jackson Grayhek, Rowen Lair

## Summary
In this lab, we learned how to implement a half-subtractor in verilog. We also learned how to implement a ones compliment converter and a twos complement converter in verilog. 

## Lab Questions

### 1 - Explain the differences between our Half Adder from last lab and the Half Subtractor from this lab.
The difference between the half adder from last week and the half subtractor from this week is that the carry/borrows boolean equation is (~A & B) as compared to the carry's boolean equation from last week being (A & B).

### 2 - What about the end around carry of One’s Complement makes it hard to use and implement?
It makes it hard to use because it forces us to connect the carry out from the last full adder and connect it back to the first full adder. This causes the implementation to be slow and somewhat confusing. 

### 3 - What is the edge case and problem with Two’s Complement number representation?

