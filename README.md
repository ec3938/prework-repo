# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Evie Cundy**

Time spent: **9** hours spent in total

Link to project: https://small-curvy-potato.glitch.me


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

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
![](gif1-link-here)
![](gif2-link-here)
![](gif3-link-here)
![](gif4-link-here)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

To figure out what RGB color codes I wanted to use, I utilized the website https://www.rapidtables.com/web/color/RGB_Color.html.

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
One challenge that I had encountered during coding the Prework stemmed from the fact that I haven’t coded anything using html since middle school 
and I have no experience coding in CSS, so I struggled a little bit with figuring out the conventions of the languages. However, I found the Prework 
tutorial to be very helpful in guiding me to re-acquaint myself with the fundamentals. Later on in the project, I had a little bit of trouble with the 
reasoning used in the logic loop regarding the multiple choices the program must make based on the user’s guesses being correct or not. The way I was 
able to overcome this problem was by drawing out a diagram for myself on paper, and then drawing out how I thought the loop would work as well. It helped 
me to visualize how the user’s choices would lead them to facing multiple outcomes in a way I could understand and writing the code out on paper was also
beneficial for me. Even so, I still had trouble translating the drawing I made into executable code and ended up messing up the logic loop a few times 
before finally arriving at a way that would function correctly.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

I’m very curious as to how developers make a website run well if it has a large number of assets that have to be loaded in when the page is 
accessed by a user, such as images or interactive buttons in a menu. After seeing how long and complex the code can become for a simple four 
button memory game, I also began to wonder how web developers organize the code they write to be easy to read, and how I can learn these 
conventions to do the same. I began wondering if there is a specific science to making the website you are coding to both work efficiently, 
load in in an optimal time frame, and also be easy on the eyes of those visiting the web page. I also had a few specific questions come to mind
while working on the project about how to apply more cosmetic designs to web pages.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

If I had a few more hours to work on this project, I would want to change the buttons so that they were arranged to look and worked like a very, 
very small piano. This new game would retain the light and sound memory game features, only make it so it would play a tune and have you play it back, 
note by note. To do this, I would have to make it so there are more than four buttons and change their designs so that they look like black and white 
bars arranged on the page in a specific layout. Since the idea seems far too complicated for me to handle in only a few hours, I would probably only 
stick with five buttons, or a small number for now to make it easier to implement. Then I would have to research more about how the sound engineering 
of the page works in order to figure out a way to map specific notes to the buttons so that they would play the note that the key button represents. 
I would also add new arrays of button orders, with each sequence of notes representing a tune they might recognize. This way, the light and sound memory 
game could function as a sort of extremely simplified piano lesson game, where it teaches you how to play a short tune by lighting up the keys in the melody 
in sequence, with the player having to repeat the tune back to win. To help keep track of the number of turns, I might add a scoreboard that counts the 
“combo” or number of sequences performed back successfully in the form of an integer that is incremented after the user completes a turn correctly.



## Interview Recording URL Link

[My 5-minute Interview Recording](your-link-here)


## License

    Copyright [Evie Cundy]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.