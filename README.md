# Pre-work - *Memory Game*

*Memory Game* is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Bingying Chu

Time spent: 4 hours spent in total

Link to project: (insert your link here, should start with https://bingyingchu-memory-game.glitch.me/)

## Required Functionality

The following **required** functionality is complete:

* [√] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [√] "Start" button toggles between "Start" and "Stop" when clicked. 
* [√] Game buttons each light up and play a sound when clicked. 
* [√] Computer plays back sequence of clues including sound and visual cue for each button
* [√] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [√] User wins the game after guessing a complete pattern
* [√] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [√] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
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
![](your-link-here)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
https://developer.mozilla.org/en-US/docs/Learn/Common_questions/What_are_browser_developer_tools
https://developers.google.com/web/updates/2017/09/autoplay-policy-changes#webaudio

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
The challenge I had was that sometimes I was not able to hear the sound played by my computer. I discovered the following might be the reasons:
1) the setting of my browser's autoplay policy stopped it;
2)I was not consistent with my coding style in the JavaScript file(missing a bracket or a semicolon caused the crash).
The way I overcame it was to debug with the development tools and I found and fixed all the bugs. 


3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
I enjoyed this project and have learned a lot about the development process. My questions about web development include:
1) since this is a frontend project, I am curious to know how to connect it with backend data;
2) all the development procedures are clear and well written, but I would like to learn how to develop the design thinking so I can complete a project like this completely on my own. 

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
If I had more time on the project, I would like: 
1)the computer to create a random sequence each time the user clicks on the start button, instead of following the settled existing pattern;
2)to stop the user playing with the buttons until the user hits the start button;
3)to set a timer calculating the time the user spends on winning the game.



## License

    Copyright [YOUR NAME]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.