# *Simon Says*

**Simon Says** is a light and sound memory game based on the classic electronic game which requires a player to correctly recall an increasingly long pattern of positions. 

Link to project: (https://light-and-sound-game-matt-jung.glitch.me/)

## Functionality

The app contains the following functionality:

* Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* "Start" button toggles between "Start" and "Stop" when clicked. 
* Game buttons each light up and play a sound when clicked. 
* Computer plays back sequence of clues including sound and visual cue for each button
* Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* User wins the game after guessing a complete pattern
* User loses the game after an incorrect guess
* Computer picks a different pattern each time the game is played
* Reduced duration of button playback to expedite game / reduce waiting

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
