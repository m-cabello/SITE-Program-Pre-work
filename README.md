# Pre-work - *Memory Game*

Musical Squares is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Martin Cabello

Time spent: 3 hours spent in total

Link to project: https://glitch.com/edit/#!/real-dull-detective?path=README.md%3A42%3A91

## Required Functionality

The following **required** functionality is complete:

* [X] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [X] "Start" button toggles between "Start" and "Stop" when clicked. 
* [X] Game buttons each light up and play a sound when clicked. 
* [X] Computer plays back sequence of clues including sound and visual cue for each button
* [X] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [X] User wins the game after guessing a complete pattern
* [X] User loses the game after an incorrect guess

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
![](https://cdn.glitch.com/e2542eaf-0cd4-43bd-b799-3f24de7756cf%2Fvideo.gif?v=1616440094032)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
  W3 Schools

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
  A challenge I encountered in creating this submission was understanding the copy and paste code, specifically, the one where the sound was created. I was able to overcome this by reading the code line by line and trying to interpret the meaning of each one. Often when I see a large amount of code come out of nowhere, I tend to become anxious and don’t read the code well. However, to fix this issue I read the entire code line by line and based on the limited experience I have on JavaScript, I was able to guess what each line attempted to do. Whenever I couldn’t quite figure out what each line of code did, I utilized w3 schools to help me understand the purpose of each line of code that confused me. I was also confused on what was the purpose of and what were the differences between the JavaScript, HTML, and CSS files. Based on the lines of code given by the tutorial, I was able to figure out that the HTML and CSS files contained and developed the front end of the code. On the other hand, the JavaScript file developed the back end. In other words, the JavaScript file makes the game run. It’s where the variables and constants are stored and used by the functions needed to run the game. These are the challenges I faced while creating this submission.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
  I have so many questions about web development after completing my submission including how the program is able to use an outside source to get sounds. Does it work like colors? I also have questions on how developers are able to achieve certain features in their websites. For example, how are developers able to use databases in order to obtain and store key details like their name and email address and keep those details until the account has been deleted. Specifically, I have noticed how several sites use google's authorization system and have questions about how they are able to do that. Do they need permission from google? Another example is how websites are able to use external verification methods like google verification in which the site attempts to keep bots from using the site. These verification systems make tests so that only humans would be able to answer them, even though some advanced and well developed bots are able to get through. I somewhat understand the front-end with the CSS and HTML file but I have questions about what each different CSS element does. There are so many and I only know a few. These are a few of the questions that I have currently on web development.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
  If I had a few more hours to work on this project, I would include databases in which each player can create an account and be able to sign in. I would give a score to each player depending on how fast they get the wins, and how many wins. Then, each player registered in the game would then be ranked based on their points. Since we will be using points to rank players, a point system will have to be implemented. The amount of points you get per game will depend on how fast you complete each task and if you are successful in winning or not. To do this we will have to implement a timer to the game to keep track of the speed of each user. Since points should accumulate based on all the games each user has played(even if the games are not played all in a row), our program will have to keep track of each user’s current point total and be able to add the new points gained in the most recent games. Since you can gain points, points being lost should exist and I would implement this if I had more time. If you completely lost a game, a certain amount of points should be deducted from the total points of the user playing. These are a few features I would implement if I had more time.



## License

    Copyright Martin Cabello

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
