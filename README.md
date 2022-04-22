# Pre-work - *Zen-Memory Game*

**Zen-Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Micah Casey-Fusco**

Time spent: **12** hours spent in total

Link to project: https://glitch.com/edit/#!/zen-memory

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

* [x] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [x] Buttons use a pitch (frequency) other than the ones in the tutorial
* [ ] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [x] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [x] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented (unchecked items are features I planned to implement with more time):

- [x] A more pleasing background setting
- [ ] Zen background music in the same key as the button tones
- [ ] A water ripple effect trailing the mouse (and onclick) using a jQuery component
- [ ] Layout adjustment for mobile use
- [ ] Easter egg that displays a special message if you play a specific tune without clicking start !

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:


*Text format & Start/Stop button function*

![](https://i.imgur.com/5SYzxIe.gif)


*Win function & Win message*

![](https://i.imgur.com/4WCWySf.gif)


*Lose function & Lose message*

![](https://i.imgur.com/htwJhZ7.gif)


*Stop game function*

![](https://i.imgur.com/XD2LkpC.gif)



## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
- [x] https://angular.io/cli (for card component implementation)
- [x] https://stackoverflow.com/questions/3490216/html-css-adding-an-icon-to-a-button (how to add icon to a button)


2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
After mistaking the minimum requirements for the guideline of the project (rather than the required steps), I began coding the website using Angular, which I had begun to learn within the past semester. About halfway through, I revisited the prework website to check my progress and realized that the submission required a link to glitch.me. Hoping I wouldn't have to transfer all of my files into a separate IDE, I contacted to TA's on slack asking about the matter and found out that glitch was indeed required to be used. This turned out to be more beneficial that I anticipated, though. Previously, I had let angular generate all the components I needed without any manual help from me by utilizing terminal commands like "ng g c navigation @angular" and such. After learning I had to transfer my files, though, I needed to take a deeper look into my routing modules in order to find out what needed to be changed to fit the format given by Glitch.me. During this process I learned how the .json file, assets folder, and routing modules worked in tandem with each other to import, assign, and utilize different media and components I typically add to my projects. This, in turn, also made it much easier for me to go about working with Angular now having a deeper understanding of its function as a framework. So, although it may not be direclty related to the project, I found it to be a difficulty that was highly rewarding to overcome.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
I understand how the remote files work in tandem with eachother, and how each component affects the funcitnoality and look of the website, but one thing I still have trouble understanding fully is the server's role in it all. The communication between the Web API's requests and the DOM is intuitive but the details are still a bit fuzzy. How does console logging fit into it all? In what order to requests and the respective data grabbing execute? Are there more efficient ways to format our HTML or JS files in order to make the requests run in an optimal manner? There's a lot to dive into and I feel having help from more experienced coders would be very helpful for such a topic.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
I guess I already kind of adressed this topic but the idea for Zen Memory was to create a website that would ease the mind while stimulating it at the same time. This is similar to meditation in my opinion; a calm state that can be reached by focusing on something repetitive in order to tune everything else out. The way in which I planned on reaching such a state with the website was by adding background music that would consist of meditative tones played by zen-like instruments (perhaps a flute, chime, or singing bowl), and assigning the tones of the buttons relative to the chords being played. If I were to get really complex with this, I would create the background music myself in FL Studio, making each chord last a certain amount of time, then assigning the buttons new notes as the chords changed based upon this time. As a final touch, I found a jQuery component that creates a water-ripple trail effect as you drag your mouse across the screen, and a drop effect when clicking! I though this would be a nice extra addition that would increase the sites interactive nature and vibe as a whole. Finally, mobile compatibility would be necessary as well if I were to continue on this project.



## Interview Recording URL Link

[My 5-minute Interview Recording](your-link-here)


## License

    Copyright Micah Casey-Fusco

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
