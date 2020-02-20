# List of prime-factorized numbers

## What is this?

This repository contains a list of numbers and their prime factors *(100 = 2 * 2 * 5 * 5)*:

* ...
* 84:2,2,3,7
* 85:5,17
* 86:2,43
* 87:3,29
* 88:2,2,2,11
* 89:89
* 90:2,3,3,5
* 91:7,13
* ...

## some facts

Within my list of the numbers up to 100 million, the number with the most factors is of course: 9,699,690 (2<sup>26</sup>); And the number with the most unique factors is: 9,699,690 (2 * 3 * 5 * 7 * 11 * 13 * 17 * 19). In total there are 5,761,461 numbers with only one prime factor (prime numbers) up to 100 million.

## Mertens Function

* start with 0
* go through all the numbers:
  * if they have a duplicate prime factor -> do nothing
  * if they have an even number of prime factors -> add 1
  * if they have an odd number of prime factors -> subtract 1

![100m](https://user-images.githubusercontent.com/28928394/74924575-0bd5fe80-53d3-11ea-9107-7ae2fefaa1b7.png)


## Why?

Yeah, don't ask. I guess this counts as a hobby of some sort.

Does anyone really need this repository? - I think not.
