---
author:
- Somewha7
title: 'Clutter and Confusion'
type: Activity
---

Summary
=======

Activity to teach the creation of an insertion sort. Part of the Sorting Algorithm Series

Objective
=========

Having foiled Bubble Boy's attempts in the [previous exercise](https://github.com/junior-devleague/data-dissaray), you sent him running back to Dr. Monsoon's lair of evil, located deep on the sea floor. At the moment, Dr. Monsoon is all tied up dealing with Heroes Inc., but unfortunately his right hand man, Billy the Squid, is not. Now he and Bubble Boy are here and are wreaking havoc! They've already unsorted several lists, and they're messing up more every minute... Create an [insertion sort] (https://en.wikipedia.org/wiki/Insertion_sort) and stop them before it's too late!

Prerequisites
=============

-   Basic usage of Python REPL


Requirements
============

-   Shell terminal or Python IDE
-   A collection of cluttered info

Desired Outcomes
================

-   Basic understanding of insertion sorts

Tasks
=====

1.   Start by definining a function, with 1 argument -- a list to sort. This is your sort function, so call it something like sort(myList)
2.   Using an index based for loop, iterate over every number in your input list
3.   Inside the first loop, use a second for loop to iterate over every number up to your current index value
4.   Inside that for loop, compare every number to the value of your list at the index value given by the first loop
5.   If the value given at the index value from the first for loop is less than the value given by the second for loop,
6.   Create a new variable and use myList.pop(indexValue) to set it equal to the list at the first index value while simultaneously removing it.
7.   insert your new variable at the index value given by the second for loop
8.   Outside of both loops, return the function as being equal to your list
9.   Outside of the function, define a list to be used as an input, create an output variable, and set it as equal to the sort function being ran
10.   print your output variable

### Choto Stretch Goals
-   Create a list using user input rather than predefining it.
