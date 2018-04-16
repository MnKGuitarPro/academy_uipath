# Exercise 008

## Practical Exercise

### Find the Hidden Password 

Somebody hid a password so it is not easily read. More specifically, they did the following steps:

1. Replaced “_“ with “ ”.
2. If the password starts with “r”,  “%” is replaced with “$”.
3. Added a random number of spaces at the beginning and at the end of the word so you don’t know where it starts nor where it ends.

Examples:

* The password “r0ck_st%r” was replaced with “r0ck st$r”.
* The password “mock____st%r” was replaced with “   mock    st%r    ”.

Create a robot that reads the manipulated password and retrieves the original password from it.

## Solutions

Here you have two solutions:

1. `exercise008/Main.xaml` (my solution)
2. `exercise008/official_answer/Password decoder.xaml` (the official Academy's solution)