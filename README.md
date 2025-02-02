# Array_and_ArrayList

## Description

This repository contains Java programs that perform various array operations, including separating even and odd numbers, finding the smallest distance between neighboring elements, and converting between arrays and ArrayLists.

## Files in the Repository

- Main.java: The main entry point of the program that demonstrates the functionalities.
- UserInput.java: Handles user input for creating and processing arrays.
- ArrayExercise.java: Contains methods to perform various array-related tasks.

## Features

- Separates Even and Odd Numbers
- Declares two arrays, even and odd, and moves user-input numbers into respective arrays based on parity.
- Finds Smallest Distance Between Neighboring Numbers
- Implements a function to find two neighboring numbers with the smallest distance and returns the index of the first number.
- Converts an array to an ArrayList and vice versa.

## How to Run:

1. Compile the program using javac Main.java
2. Run it using java Main

## Methods in ArrayExercise.java

- separateEvenOdd(int[] numbers): Accepts an array of integers. Separates numbers into even and odd arrays. Returns a 2D array containing both separated arrays.
- findAllSmallestDistancePairs(int[] arr): Finds two neighboring numbers with the smallest distance. Returns the index of the first number.
- convertArrayToArrayList(Integer[] arr): Converts an Integer[] array into an ArrayList<Integer>.
- convertArrayListToArray(ArrayList<Integer> arrayList): Converts an ArrayList<Integer> back into an Integer[] array.

## Git Commit History:

- Added Main.java with main program entry point (with valid description).
- Added UserInput.java to handle user input (with valid description).
- Added ArrayExercise.java with Array operations (with valid description).
