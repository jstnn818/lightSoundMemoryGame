# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Justin Nguyen**

Time spent: **1** hours spent in total

Link to project: (insert your link here, should start with https://glitch.com/edit/#!/peach-magnificent-pendulum)

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

* [X] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
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
![](https://cdn.glitch.com/e69bb871-467f-44ab-9061-c6a8d738a9e3%2FcodepathSoundMemoryGame.gif?v=1616370518068)
(Recordit didn't capture the frames when a button was clicked on and changed color, later in the gif you can see it changes color when I clicked on it slower)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

[I used w3school to look up different CSS colors, besides that I mostly just followed the tutorial that was given to me]

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

[Overall, I wouldn't say that I was super challenged by this project, as it was really easy to follow the tutorial and understand it.
However, if there was anything particularly difficult, I would say it was mostly the guess function. While I mostly understood the logic,
I found that sometimes I mixed up the variables inside the if statements, leading to unforeseen errors. Another thing that I found odd was
when I called if(btn == pattern[guessCounter]) which for whatever reason did not work as I want to. After a few minutes of testing I
decided to check the code given to us in the tutorial. I saw that it was actually the opposite as in if(pattern[guessCounter] == btn)
rather than my other statement. Though, I am unsure why it made a difference as the logic should still be the same. Either way the tutorial
was very helpful and helped teach me a lot about this project and React. Something else that I would say that was challenging, actually came
to creating the GIF and adding it to the README.md file itself. As I found that Recordit didn't record everything completely accurately,
as I noted, on occasion, it did not capture the few frames where the color of the button changed as I clicked on it quite fast.]

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

[I wouldn't say that I have any particular questions about web development. But if I were to ask something, I would ask what is the scope of
the content in the class, as in, how ambitious of a project would we be able to make after completing the program. As I learned many new features
of JavaScript and HTML today that I hadn't known previously. As when I first learned about these 3 coding languages, I mostly self-taught myself
in no particular order. As it was more of trial and error rather than following a specific tutorial when it came to a certain function I wanted to implement.
Regardless, I really look forward to seeing the many aspects of web development that is taught in this internship.]

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

[If I were to have a few more hours to work on this project, I would probably continue down the list of optional features that are given in the
README.md file. In particular, I would mostly be interested in adding more game rules and other aesthetic features. For example, I might consider
adding more buttons so that it would be harder for players. Something else that might be interesting is if I could create a function that would change
the order of the buttons, which may make it more fun, as the layout will be different each time. Besides that, I would want to change the 
aesthetic of the game. I have already done this somewhat in the CSS file. But I was thinking I could make it so that I could add images in some way.
For example, I could give the game a theme, wherein I would add particular images from media to give it more of a unique design.]



## License

    Copyright [Justin Nguyen]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
