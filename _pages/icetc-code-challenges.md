---
permalink: /icetc24-code-challenges/
title: "ICETC - Influence of Large Language Models on Programming Assignments – A user study [Appendix 1]"
author_profile: false
---

# APPENDICES
## A.1 Tasks proposed to solve to the participants
In this section we report the programming problem that participants found during the experiment. We have two different session and two task for each session.

### First Task: Buying the Maximum Number of Toys

Goal: Paul wants to buy the maximum number of toys for his child with a budget of K euros. Write a function that takes as input an array of toy prices and the budget K, and returns the maximum number of toys Paul can buy.
Example:
const prices = [1, 12, 5, 111, 200, 1000, 10];
const budget = 50;
const maximumToys = maximumToysPaulCanBuy(prices, budget);
console.log(maximumToys); // Output: 4
Requirements:
1.     	The function must be called maximumToysThatCanBuy.
2.     	The function must return an integer representing the maximum number of toys that can be bought.

### Second task: Merge Two Arrays

Objective: Write a function that takes as input two arrays of numbers (representing song identifiers) and returns a new array containing all elements of the two input arrays, without duplicates, in ascending order.
Example:
const playlist1 = [5, 2, 9];
const playlist2 = [1, 7, 2];
const playlistFinal = mergeArray(playlist1, playlist2);
console.log(playlistFinal); // Output: [1, 2, 5, 7, 9].
Requirements:
1.     	The function must be called mergeArray.
2.     	Remove duplicates from the final array.
3.     	Sort the final array in ascending order.