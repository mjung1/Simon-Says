# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Matthew Jung**

Time spent: **5.5** hours spent in total

Link to project: (https://light-and-sound-game-matt-jung.glitch.me/)

## Required Functionality

The following **required** functionality is complete:

* [x] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [x] "Start" button toggles between "Start" and "Stop" when clicked. 
* [x] Game buttons each light up and play a sound when clicked. 
* [x] Computer plays back sequence of clues including sound and visual cue for each button
* [x] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [x] User wins the game after guessing a complete pattern
* [x] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [ ] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
* [ ] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [x] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [x] Reduced duration of button playback to expedite game / reduce waiting

## Video Walkthrough (GIF)

Press the start button to initiate a game. If you correctly recall the pattern, the pattern will increase by 1.
![](http://g.recordit.co/JoMuSjrpIB.gif)
Pressing the stop button will stop the game.
![](http://g.recordit.co/fIppVGG2PO.gif)
If the pattern is not correctly recalled, the game will stop and a pop-up alert will state that you have lost the game.
![](http://g.recordit.co/D8x74TfINv.gif)
If a pattern of length 8 is reached and recalled correctly, the game will stop and a pop-up alert will state that you have won the game.
![](http://g.recordit.co/wrB3L29bc1.gif)
The pattern will be randomized and will vary between games
![](http://g.recordit.co/w5Tpa5Tp3i.gif)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

[I utilized stack overflow for guidance on how to randomize the game pattern in JavaScript (have only used a handful of times), learning how to create an array of a desired length, with a random number chosen from a specified range.]

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

[The biggest challenge I encountered in creating this submission was trying to implement the randomization of the game pattern. The initial prework provided a walkthrough for the game implementation but only for a predetermined pattern that would remain the same for each game. Since the original game of Simon Says randomized the pattern to be recalled between games, I wanted to randomize the pattern between games since it would add significant functinoality to the game. Since I have very little experience with JavaScript, my initial idea was to try to implement the randomized pattern feature in Python as it's the language I have the most experience with. I would then try to make the necessary changes to the code so that it would run in Javascript - I found that to be rather unsuccessful as there was less transferability / more syntax than I expectede to go from Python to JavaScript. I ultimately took the approach of just to search online for how to create an array of randomized digits in JavaScript. After some searching, I found a post on StackOverflow that provided a walkthrough of the logic of the code and a generalized implementation. From that post, I learned how to implement an array of randomized digits in JavaScript and coded it up to meet the desired needs for the program (arr of length 8, with randomized digits chosen from 1-4 inclusive).]

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

[Some questions I have about web development after completing my submission revolve around learning more about HTML, CSS, and JavaScript. Firstly, is knowing HTML, CSS, and JavaScript sufficiently to build almost any web app one desires, or are there additional languages that one must add to their toolkit? Is the process of learning HTML, CSS, and JavaScript more focused on learning how to do specific, practical things in the languages or is there also somewhat of a theoretical focus like when learning one's first language such as Python or Java in an introductory computer science course? Are most software engineers capable of web development / is the capability expected, or is web development something that certain software engineers specialize in while others focus on other areas? Lastly, is web development something that is constantly changing and if so, what is the best way to stay up to date with those changes?]

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

[If I had a few more hours to work on this project, I would have added the feature of speeding up the playback each turn to make the game harder. I think that would make the game significantly more interesting. I also would add an on-screen counter that updates after each turn to let the player know the current pattern length they are trying to recall. Lastly, I would add the functionality of a survival mode where there is no set pattern length and the game lasts an indefinite amount of time, until the player recalls the pattern incorrectly. The player would then have the option to play either survival mode or standard mode where the player tries to recall the pattern of 8 correctly.]



## Interview Recording URL Link

[My 5-minute Interview Recording](your-link-here)


## License

    Copyright [Matthew Jung]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
