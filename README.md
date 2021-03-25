# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Sadhana Indukuri**

Time spent: **4** hours spent in total

Link to project: https://glitch.com/edit/#!/precious-placid-index

## Required Functionality

The following **required** functionality is complete:

* [Y] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [Y] "Start" button toggles between "Start" and "Stop" when clicked. 
* [Y] Game buttons each light up and play a sound when clicked. 
* [Y] Computer plays back sequence of clues including sound and visual cue for each button
* [Y] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [Y] User wins the game after guessing a complete pattern
* [Y] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [Y] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [Y] Buttons use a pitch (frequency) other than the ones in the tutorial
* [Y] More than 4 functional game buttons
* [Y] Playback speeds up on each turn
* [Y] Computer picks a different pattern each time the game is played
* [Y] Player only loses after 3 mistakes (instead of on the first mistake)
* [Y] Game button appearance change goes beyond color (e.g. add an image)
* [N] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [N] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough

Here's a walkthrough of implemented user stories:
Three Strikes and you are out displayed:

![](https://cdn.glitch.com/a1f5b5e9-57d7-467d-b297-40a2f8a188d4%2Fezgif.com-gif-maker.gif?v=1616653760712)

All buttons are clicked correctly and you win:
![](https://cdn.glitch.com/a1f5b5e9-57d7-467d-b297-40a2f8a188d4%2Fezgif.com-video-to-gif.gif?v=1616653766253)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

I used: https://www.w3schools.com/js/js_random.asp, https://www.w3schools.com/html/html_css.asp, and https://www.w3schools.com/howto/howto_css_button_on_image.asp

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

I found the guess function logic to be hard to implement from the flowchart. For some reason, the game would never end even if I guessed wrong. 
So, I used the debugger to see what was the issue. Going through it step by step helped me realize where I went wrong in my code. My brackets were placed in the incorrect place. 
After fixing my brackets, the code worked! I then compared my solution to the given solution and it matched. Debugging forced me to slow down and rationalize why I was doing the things I was doing. 
Why did I add that line of code here? If this line of code is executed, what happens immediately after? When I code, I work so fast that I often don't think about these questions. 
But when debugging, I ask myself these questions in order to understand what went wrong.  

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

Javascript seems to have limitless possibilities. I have used javascript in making websites but I haven't gone in-depth into the language. 
I would love to learn more about how the state-of-the-art websites we use day to day implement javascript, HTML, and CSS. 
These websites use more than just these three languages, so I want to know how I can take my websites to the next level. 
I have a vague understanding that frameworks or Javascript libraries like Angular JS and React help create these beautiful websites. 
I am heavily interested in learning more about these tools. I would also love to learn how to implement complex graphics into my websites and clean up my layout. 

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

I would love to add the ticking clock and prettier tones for the game. I think I would also center the game in the middle of the website rather than it being aligned to the right.
I would also like to add a background for the entire website and add shadows around the buttons to make them pop! A cohesive color scheme and more interesting font styles are also something I would be interested in. 
Eight buttons would also be a nice feature. I also think that making the light-up feature brighter and more apparent will make the game much better. 


## License

    Copyright [Sadhana Indukuri]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.