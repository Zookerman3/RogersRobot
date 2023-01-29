### Mr Rogers Robot

## This application takes in a number and outputs 3 different responses based on the numbers inputted

## Setup: clone this repo to your local computer, open index.html, run using live server extension

## Contributions by Stephen Zook

## No known bugs


# TDD:

Describe: beepboop()


Test: "It should return an array of numbers from 0 to the user's inputted number"
Code: feedInputNumbers(5);
Expected Output: [0, 1, 2, 3, 4, 5]

Test: "It should return a "Beep!" if the number in the array is 1"
Code: feedInputNumbers(5);
Expected Output: [0, "Beep!", 2, 3, 4, 5]

Test: "It should return a "Beep!" if the number in the array is 1, return "Boop!" if the element is 2, return "Wont you be my neighbor? if the element is 3"
Code: feedInputNumbers(5);
Expected Output: [0, "Beep!", "Boop!", "Wont you be my neighbor?", 4, 5]