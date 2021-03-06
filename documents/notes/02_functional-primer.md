# Lecture 1: Functional Primer

## Objectives

1. Introduction to Functional Programming and Lambda Calculus
2. Practice some examples of FP

## Metrics/Desired Outcomes

* Write a simple `helloworld.clj` from scratch

## Reading Assignment

* Higginbotham, Daniel. Chapter 3 from [Clojure for the Brave and True](http://www.braveclojure.com/). A free PDF version (of Chapter 3) is available from No Starch Press.

## Pure functions

Pure functions have two requirements:
* `referential transparency` -- always return the same result if provided same arguments
* No side effects -- through immutable data structures

Other intangible aspects of Functional Programming:
* Functions are first class citizens
* Treatment of functions (shifting our way of thinking) are more important than data
* Emphasis on algorithm over data structures
* Small and decomposable functions (tasks or actions)

### Recursion

Functional programmers rely heavily on recursion; several important (fringe) benefits of recursion is the enforcement of immutability and making code more elegant.

* Base case (aka stopping condition)
* Induction step (moving to the next recursion)

### Functional Decomposition

Decoupling function and data; breakdown problem into decomposable abstraction rather than data.  The focus here is on functions (doing) versus data (being).

## Introduction to Clojure Videos

1. Getting Started with Light Table (3:14)
2. Types (4:51)
3. Control Flow (6:07)
4. Functions (7:42)
5. Collections (7:02)
6. Recursions (8:16)
7. Leinigen (4:05)
8. Modules (3:44)

## Exercise

Write our first `helloworld.clj` clojure program.

* Do this with `LightTable`
* Do this with `lein` project

Run the helloworld using the REPL tool and run it using `lein`

