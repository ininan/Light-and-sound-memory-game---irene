# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Irene Ninan**

Time spent: **3.5** hours spent in total

Link to project: (https://glitch.com/edit/#!/tabby-acute-meadowlark?path=README.md%3A1%3A0)

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
* [ ] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough

Here's a walkthrough of implemented user stories:
![](https://github.com/ininan/Light-and-sound-memory-game---irene/blob/main/LightandSoundGame.gif)
![](https://github.com/ininan/Light-and-sound-memory-game---irene/blob/main/LightandSoundGamept2.gif)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
[n/a , only used instructions given by CodePath.]

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
[A challenge I encountered in creating this submission was getting the colors to change when I clicked on each button. At first, when I clicked on each button, the colors did not change but after going through my code a couple times I was able to figure out my mistake. In my style.css file, I noticed that I did not update my #button1:active, #button1.lit for each corresponding button. I left them all to call button 1, when I was actually supposed to use 2, 3, and 4, to call the four different buttons. Another issue I encountered was incorrectly entering a code in my script.js file where I put var guessCounter = 0 under function playClueSequence() when I was just supposed to leave it at guessCounter = 0. This mistake caused my game to display that I lost the game although I clicked the correct button. Overall, through these errors, I was able to figure out my mistake by rereading the instructions and going through my code line by line. ]

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
[After completing this project, I have questions about how we can debug errors on our system without using any aid from the complier itself. When creating a web application, is it common to use layouts that other webpages already have? What types of programming languages support back end and front end ? How does web development correlate to UI/UX design or even Cloud Computing ? What are the different career paths you can take after learning how to develop on the web ? What is the best language to use when you want to design your own webpage ? How do you tackle code that you can't seem to debug ? How do you become a good programmer ? How many languages are actually useful when going into the workforce ? Are using API keys and bootstrap always permitted when developing or is it better to start from scratch ?]

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
[If I had a few more hours to work on this project then I would spend them by making the game more fun, colorful, and interactive. I would change the background to something brighter and the font to something more eye appealing. I would like the buttons to be different shapes and sizes. I would also want to implement the option to choose various levels at the start of the game. The player would be able to choose between "easy", "medium", and "hard". The easy level would only contain 4 buttons and wouldn't move too fast, medium would contain 6 buttons and would be a little faster, and hard would be 10 buttons and move pretty quickly.]



## License

    Copyright [Irene Ninan]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
    
