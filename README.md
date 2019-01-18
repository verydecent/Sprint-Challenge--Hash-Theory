# Sprint Challenge: Theory of Computation and Hash Tables

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in a concrete project. This Sprint, we explored the history and theory of computation, diving deep into memory and pointers by building array functions and hash tables. In your challenge this week, you will demonstrate proficiency by filling out boolean truth tables and solving algorithms in C using hash tables.

## Instructions

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the Sprint Challenge. However, you are encouraged to follow the twenty-minute rule and seek support from your PM and Instructor in your cohort help channel on Slack. Your work reflects your proficiency in C and your command of the concepts and techniques in the computation theory and hash tables.

You have three hours to complete this challenge. Plan your time accordingly.

## Commits

Commit your code regularly and meaningfully. This helps both you (in case you ever need to return to old code for any number of reasons and your project manager.

## Description

This sprint challenge is divided up into three parts: Boolean algebra (11 points), hash tables (24 points) and a short interview (20 points). There is also a stretch goal in the boolean algebra section which should only be attempted after the rest of the problems have been completed.

## Interview Questions

During your challenge, you will be pulled aside by a PM for a 5 minute interview. During this interview, you will be expected to answer the following three questions:

  * 1. What is a computer and how does it work?
  A computer is a machine that computes instructions. A computer processes these instructions as input through its processing unit using arithmetic in memory. Then an output is returned after said processing.

  * 2. What is an array and how does it work?
  Arrays are one of the most common data structures we work with in memory. Arrays are index based contiguous blocks of memory that is allocated based on the number of declared items in the array. One important thing to remember about Arrays are that we access the address of all blocks on said array by referening to the first block of memory. These are called pointers, rather than having to carry around the whole wize of the array, which can cause slow down, we can carry pointer and run arithmetic to find subsequent items in the array. Insertion for arrays is O(1), deletion is O(n), and search is also O(n).

  * 3. What is a hash table and how does it work?
  Hash tables are also another form a common data structure. Hash tables accept key value pair items into its array. Hash table uses a hashing function that inputs the items key wether thats a string or integer and returns a number based on the amount of allowed space in the Hash tables array. This number is used as the key value items index in the Hash tables array. Sometimes when a new item is processed through the hashing function, a number is returned and that index numbers place had already been taken. This is called collision and there are two approaches to this challenege. The first solution, we can implement a function to check if the next available space in the array is taken. The second solution, we can implement linked lists to each array in the hash table. If we run into a collisioin, we can use that same array index and implement a link to the next key value item.

You will receive points at the PM's discretion based on the following criteria:

  * 20: Would love to have this person on my team!
  * 14: Wouldn't mind working with this person.
  * 10: Knowledge is lacking OR poor communication skills
  *  6: Knowledge is lacking AND poor communication skills
  *  2: You get 2 points for showing up



## Project Set Up

#### [Theory of Computation](https://github.com/LambdaSchool/Sprint-Challenge--Hash-Theory/tree/master/theory)

You can either copy your answers into a new text file or fill out the README with your solutions. Just make sure your PM knows where to find them.

#### [Hash Tables](https://github.com/LambdaSchool/Sprint-Challenge--Hash-Theory/tree/master/hash-tables)

For the hash tables portion of the sprint challenge, you'll be working through two algorithm problems that are amenable to being solved efficiently using a hash table. You know the drill at this point. Navigate into each exercise's directory, read the instructions for the exercise laid out in the README, implement your solution in the .c skeleton file, then make sure your code passes the tests by running the test script with make tests.

A hash table implementation has been included for you already. Your task is to get the tests passing (ideally using a hash table to do it). You can remind yourself of what hash table functions are available by looking at the hashtable.h header file that is included in each exercise directory (note that the hash table implementations for both exercises differ slightly).

## Minimum Viable Product

You can earn 35 points from the main coding portion of the sprint challenge and up to 4 extra points for completing the stretch goal. Stretch points will only be counted if all regular problems have been completed.

#### [Theory of Computation](https://github.com/LambdaSchool/Sprint-Challenge--Hash-Theory/tree/master/theory) - 11 pts
  * Boolean 1 - 3 pt
  * Boolean 2 - 3 pt
  * Boolean 3 - 5 pt

#### [Hash Tables](https://github.com/LambdaSchool/Sprint-Challenge--Hash-Theory/tree/master/hash-tables) - 24 pts
  * ex1 - 12 pts
  * ex2 - 12 pts

Both Hash Table problems will be graded as follows:
  *  3: Code attempted
  *  6: Code resembles the correct solution
  * 10: Tests pass
  * 11: Tests pass, no hash table memory leaks
  * 12: Tests pass, no hash table memory leaks, linear runtime complexity  


#### [Computation Stretch](https://github.com/LambdaSchool/Sprint-Challenge--Hash-Theory/tree/master/theory) - 4 pts
  * Truth Table - 1 pt
  * Sum - 1 pt
  * Carry - 2 pts



### Grading

Students can receive up to 100 points for their work over the entire week: Array and Hash Table project in C (35 points), coding Sprint Challenge (35 points), interview (20 points), and participation during the week (10 points). 90+ points is a 3, 70-89 is a 2 and 0-69 is a 1.

  * __Project__: 35
  * __Challenge__: 35
  * __Interview__: 20
  * __Participation__: 10
----------
  * __3__: 90+
  * __2__: 70-89
  * __1__: 0-69
