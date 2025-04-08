# Coding-typing-trainer

## Table of Contents
- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Contributing](#contributing)
- [License](#license)

## Introduction
This project is being designed largely as a way to develop a webapp and help me practice my typing speed at the same time. There are other typing trainers out there, however, I found that one thing that annoyed me when using them, is that during practice there wasn't a way that would help me improve specifically keys that I was having trouble with or constantly making mistakes on. If there was something that would dynamically change the content for typing practice to help facilitate these difficult keys, then that might help accelatate the rate at which my typing would improve.

I still haven't decided how this is going to happen, but there are two potential options that I am considering right now.
1 - when there are mistakes, the user is bumped into a pop out or dialogue box that has a string of characters that has the mistaken character dispersed in it a high density. This happens everytime there is a mistake, when the user has "Training mode" turned on.

2 - If we are using a LLM to generate the text that is to be typed, then we train or add to the model some aspect that makes it so that the keys that have mistakes made show up much more frequently. This would require adding the actual typed information information as the inputs to the model, as well as the intended typed prompt.
I am not quite sure how do this yet. We need the model to be fast, so we can use lightweight models because accuracy or usable code is not the priority here, and speed of generating the text is the important.
We want the text to be typed to change somewhat dynamically, however, too much dynamics might make this difficult if the next character or even the current word changes if there is a wrong key that was typed, although that might actually make things somewhat fun.

Regardless the first steps are not these detailed mechanics but getting the webapp up and running and rudementary typing training functional.


## Installation

## Usage

## Features
The major features of this 

## Contributing

## License

## Acknowledgments

