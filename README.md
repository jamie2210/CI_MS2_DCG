# DC Games
(Developer: Jamie Letts)

![Mockup image](docs/device-display.jpg)

[Live webpage](https://jamie2210.github.io/CI_MS2_DCG/index.html)

This is the website for DC Games, it is designed to be responsive and accessible on all devices. It consists of 2 games, a hangman game, and a multiple-choice quiz. Both games are themed around the animated comic of Batman.

## Table of Content

1. [Project Goals](#project-goals)
    1. [User Goals](#user-goals)
    2. [Site Owner Goals](#site-owner-goals)
2. [User Experience](#user-experience)
    1. [Target Audience](#target-audience)
    2. [User Requirements and Expectations](#user-requirements-and-expectations)
    3. [User Stories](#user-stories)
3. [Design](#design)
    1. [Design Choices](#design-choices)
    2. [Colours](#colours)
    3. [Fonts](#fonts)
    4. [Structure](#structure)
    5. [Wireframes](#wireframes)
4. [Technologies Used](#technologies-used)
    1. [Languages](#languages)
    2. [Frameworks and Tools](#frameworks-and-tools)
5. [Features](#features)
6. [Testing](#testing)
    1. [HTML Validation](#HTML-validation)
    2. [CSS Validation](#CSS-validation)
    3. [JavaScript Validation](#javascript-validation)
    4. [Accessibility](#accessibility)
    5. [Performance](#performance)
    6. [Device testing](#performing-tests-on-various-devices)
    7. [Browser compatibility](#browser-compatibility)
    8. [Testing user stories](#testing-user-stories)
8. [Bugs](#bugs)
9. [Deployment](#deployment)
10. [Credits](#credits)
11. [Acknowledgements](#acknowledgements)

## Project Goals

Primary goal is to provide a user-friendly, fun, and good-looking interactive website which offers the game Hangman and a multiple-choice quiz.

### User Goals
- Play both games that are fun and engaging.
- Easily find the rules of each game.
- Easily get in touch via a contact form.

### Site Owner Goals
- Create a website with entertaining games.
- Create visually appealing designs throughout.
- Easy navigation throughout.
- Provide a fully responsive and accessible design. 

### Developer Goals
- A clean design that stands out and catches the users attention.
- A website that responds correctly on all devices where design and effectiveness is not hindered on any device.
- An easy to navigate website with clear pathways to specific pages such as rules, each game, home, and contact.

## User Experience

### Target Audience
- Ages 8 to 12.
- It is specific to those who have an in interest in DC comics, particularly Batman.

### User Requirements and Expectations

- A simple and intuitive navigation system.
- Quickly and easily find relevant information.
- Links and functions that work as expected.
- Good presentation and a visually appealing design regardless of device used.
- Easy to follow the games and rules.
- Simple content that the user can follow and understand.
- An easy way to contact the developer for feedback.
- Accessibility.

### User Stories

#### Site User (General)
1. I want to easily understand the rules of each game.
2. I want to easily navigate to my chosen game.
3. I want the games to be fun, enjoyable, and easy to understand.
4. I want to know how I did at the end of each game.
5. I want a means to contact the developer and have confirmation the message has been sent.

##### Hangman
6. I want to play the game both by clicking the mouse and using the keyboard.
7. I want to know which letters I’ve used already.
8. I want to know how many guesses I have left.
9. I want the gallows image to add on sections of the hangman each time a letter is guessed incorrectly.
10. I see to my score of wins vs losses.

##### Quiz
11. I want to know how much time is left to answer the question.
12. I want to know which answer is correct if answered incorrectly.
13. I want to know the answer if I run out of time.
14. I want to see my score at the end.
15. I want to easily play again or quit once I have finished.

#### Site Owner 
16. I want the user to get a genuine feel this is a DC Batman themed site. 
17. I want the user to easily understand and play the games.
18. I want both games to be fully responsive.
19. In hangman, the phrases / words are limited, so to increase the difficulty and longevity of the game, the word will not be revealed if guessed incorrectly.
20. I want the user to be able to contact me for any reason they feel fit.
21. I want the user to come to a 404 page and be automatically re-directed to the home page should they enter an invalid url.
22. I want the user to have a link to my work via my Github repositories. 

## Design

### Design Choices
The design has been influenced by the comics like keeping the buttons square and grey to present comments in comic books. Each game has been designed around the colours and personality of the characters in the comics. 

### Colours

DC uses a specific blue which is used sparingly throughout the website.

Batman colours are predominantly black and yellow.

Both The Riddler and Joker are themed by purples and greens.

<details><summary>Colours Used</summary>
<img src="docs/colour-pallet.png">
</details>

### Fonts

Google fonts were used to import the ‘Anton’ font used with a sans-serif fallback throughout the website:

- [Anton]( https://fonts.google.com/specimen/Anton?query=anton)

I chose this font as it stood out to me as a strong and bold font that represented Batman well. It is also easy to read which is good for the target audience.

### Structure
The page is structured in a user friendly and visually appealing way. Upon arriving the user will see a simple display with clear instructions to what the site offers and where to find the rules of each game.

The website consists of four separate pages with rules and result modals: 
- A homepage with a with clear navigation to the games and rules.
- The Batman Hangman game page
- The Riddler’s Quiz game page.
- A contact page with a form that will directly send messages to the developer.
- Modals with the rules of each game.
- There is also a 404 page that directs the user back to the home.

### Wireframes

<details><summary>Home</summary>
<img src="docs/wireframes/home.png">
</details>
<details><summary>Batman Hangman</summary>
<img src="docs/wireframes/hangman.png">
</details>
<details><summary>The Riddler’s quiz</summary>
<img src="docs/wireframes/quiz.png">
</details>
<details><summary>The Rules</summary>
<img src="docs/wireframes/rules.png">
</details>
<details><summary>Contact</summary>
<img src="docs/wireframes/contact.png">
</details>
<details><summary>404</summary>
<img src="docs/wireframes/404.png">
</details>


## Technologies Used

### Languages
- [HTML](https://en.wikipedia.org/wiki/HTML)
- [CSS](https://en.wikipedia.org/wiki/CSS)
- [Javascript](https://en.wikipedia.org/wiki/JavaScript)

### Frameworks and Tools
- [Visual Studio Code](https://code.visualstudio.com/)
- [Bootstrap v5.3](https://getbootstrap.com/)
- [Git](https://git-scm.com/)
- [Github](https://github.com/)
- [GitPod](https://www.gitpod.io/)
- [Tiny PNG](https://tinypng.com/)
- [Balsamiq](https://balsamiq.com/wireframes/)
- [Google Fonts](https://fonts.google.com/about)
- [Adobe Suite (Illustrator, Photoshop & InDesign)](https://www.adobe.com/uk/)
- [Font Awesome](https://fontawesome.com/search)
- [Favicon](https://favicon.io/)
- [Giphy](https://giphy.com/)
- [W3C validator](https://validator.w3.org/)
- [Jigsaw CSS validator](https://jigsaw.w3.org/css-validator/)
- [WAVE Web Accessibility Evaluation Tool](https://wave.webaim.org/)
- [jshint](https://jshint.com/)

## Features
The page consists of four pages and eleven features.

### Home Page

#### DC Logo and introduction

- Upon arriving to the site a welcome modal pops up.
- It details where to find the games, the rules and contact information.
- The rules are modals accessed by clicking the '?' symbols.
- The logo is DC's official logo.
- User stories covered:  1, 2, 3, 5, 16 & 17.

<details><summary>Intro</summary>
<img src="docs/features/intro.png">
</details>
<details><summary>Home Page</summary>
<img src="docs/features/home.png">
</details>


#### Navigation Buttons & Character Images (Navigation buttons featured on all pages)
- Both the Batman and Riddler characters are that of The Batman animated series, which the games are based on.
- Navigation buttons are featured on all pages; they all have squared edges to represent sections and comments of a comic.
- Link to each game and the home page.
- It allows users to easily navigate through the website.
- The buttons are animated depending on which page they are on, matching the themes.
- User stories covered: 2, 5, & 16.

<details><summary>Buttons & Characters</summary>
<img src="docs/features/buttons-batman.png">
</details>
<details><summary>Buttons & Characters</summary>
<img src="docs/features/buttons-riddler.png">
</details>

#### Rules Modal
- Clicking the question mark under the selected character will bring up the rules for that game.
- User stories covered: 1.

<details><summary>Rules Modal</summary>
<img src="docs/features/rules-modal.png">
</details>

#### Footer (displayed on all pages)
- Featured on all pages.
- Details who the developer is, a link to Github and contact page.
- User stories covered: 5, 20 & 22.

<details><summary>Footer</summary>
<img src="docs/features/footer.png">
</details>

### Batman Hangman

#### Game Function & Game Screen
- Consists of empty gallows, empty score, and number of wrong guesses left.
- Letter keys for entry guesses, allows user to use either mouse or keyboard for entries.
- If the letter is guessed correctly the letter is revealed in replace of the '_'
- If the phrase is guessed correctly a modal is presented confirming the win with the total number of wins and losses.
- If the letter is guessed incorrectly the hangman image increases as does the number of wrong guesses.
- If the phrase is guessed incorrectly a modal is presented confirming the loss with the total number of wins and losses.
- On pressing a letter, it is highlighted yellow and then greyed out once used, it cannot be used again.
- Reset button resets the game but keeps track the total wins and losses until page is refreshed.
- The theme of the game is Batman and The Joker, and all colours, wording and design are based on the animated series.
- A comical element has been added to the results modal which is light-hearted fun. For each win and loss both characters have 5 different phrases which are randomly selected each time and play on the characters personality.
- User stories covered: 6, 7, 8, 9 10, 16, 18 & 19.

#### Win Modal
- Displays current score, wins v losses.
- Close Button that resets the game.
- User stories covered: 4, 10 & 19.

#### Lose Modal
- Displays current score, wins v losses.
- Close Button that resets the game.
- User stories covered: 4, 10 & 19.

<details><summary>Game Screen</summary>
<img src="docs/features/hangman-screen.png">
</details>
<details><summary>Win Modal</summary>
<img src="docs/features/win-modal.png">
</details>
<details><summary>Lose Modal</summary>
<img src="docs/features/lose-modal.png">
</details>


### The Riddler’s Quiz

#### Game Function & Game Screen
- Start Button.
- Navigation buttons.
- The game is themed in the colours of The Riddler, green and purple.
- Game modal is presented once start button is pressed.
- Game consists of a timer, time bar and multiple choice questions the user can click or tab to and press enter to select.
- When a question is answered correctly it is highlighted in green with a tick icon.
- When a question is answered incorrectly it is highlighted in black with a cross icon and the correct answer is displayed.
- At the end of the game the score is tallied and revealed in a modal.
- A comical element has been added to the results modal which is light-hearted fun. Dependning the score The riddler's phrase will change.
- User stories covered: 3, 11, 12 & 13.

#### Results Modal
- Displays score.
- Replay button that resets the game.
- Quit button that refreshes the page.
- User Stories covered: 4, 14 & 15.

<details><summary>Game Screen</summary>
<img src="docs/features/quiz-screen.png">
</details>
<details><summary>Game Modal</summary>
<img src="docs/features/game-modal.png">
</details>
<details><summary>Results Modal</summary>
<img src="docs/features/results-modal.png">
</details>

### Contact Form Page

- Allows user to directly contact the developer
- Alert box pops up when message has been sent successfully.
- User stories covered: 5 & 20.

<details><summary>Contact Form</summary>
<img src="docs/features/contact-form.png">
</details>

### 404
- Explains to the user they have landed on an unrecognised page.
- It automatically returns the user back to the home page after 10 seconds, detailed by a count down.
- There is also a home button should the user wish to use it.
- User Stories covered: 21.

<details><summary>404 Page</summary>
<img src="docs/features/404.png">
</details>

## Testing

### HTML Validation

The W3C Markup Validation Service was used to validate the HTML of the website. All pages pass with no errors.

index.html [results](https://validator.w3.org/nu/?doc=https%3A%2F%2Fjamie2210.github.io%2FCI_MS2_DCG%2Findex.html)

hangman.html [results](https://validator.w3.org/nu/?doc=https%3A%2F%2Fjamie2210.github.io%2FCI_MS2_DCG%2Fhangman.html) 

quiz.html [results](https://validator.w3.org/nu/?doc=https%3A%2F%2Fjamie2210.github.io%2FCI_MS2_DCG%2Fquiz.html) 

contact.html [results](https://validator.w3.org/nu/?doc=https%3A%2F%2Fjamie2210.github.io%2FCI_MS2_DCG%2Fcontact.html) 

404.html [results](https://validator.w3.org/nu/?doc=https%3A%2F%2Fjamie2210.github.io%2FCI_MS2_DCG%2F404.html)

### CSS Validation
The W3C Jigsaw CSS Validation Service was used to validate the CSS of the website.
When pasting in my index url 16 Parse Errors are flagged, all linked to Bootstrap as well as 286 warnings.

style.css [results](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fjamie2210.github.io%2FCI_MS2_DCG%2Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)
<br>

When validating just my own custom CSS file it passes with no errors and flagged three warnings using pointer-events twice used and 1 warning for the google fonts import used.
<details><summary>style.css</summary>
<img src="docs/validation/validation-css.png">
</details>

### JavaScript Validation

JSHint JS Validation Service was used to validate the Javascript files. No significant issues were found. One undefined Variable found in quiz.js for the questions variable used as it's linked to a separate file.

OnClick buttons were flagged as unused, but /* exported */ feature was used to remove the flags as they are called in the html files.

<details><summary>index.js</summary>
<img src="docs/validation//jshint/index.png">
</details>
<details><summary>hangman.js</summary>
<img src="docs/validation/jshint/hangman.png">
</details>
<details><summary>questions.js</summary>
<img src="docs/validation/jshint/questions.png">
</details>
<details><summary>quiz.js</summary>
<img src="docs/validation/jshint/quiz.png">
</details>
<details><summary>contact.js</summary>
<img src="docs/validation/jshint/contact.png">
</details>
<details><summary>404.js</summary>
<img src="docs/validation/jshint/404.png">
</details>

### Accessibility
The WAVE WebAIM web accessibility evaluation tool was used to ensure the website met high accessibility standards. All pages pass with 0 errors apart from quiz.html that has 3. They are all contrasting errors to which I disagree with, the white on purple to me is perfectly visible and matches the colour scheme so have chosen to leave it as it is.

index.html [results](https://wave.webaim.org/report#/https://jamie2210.github.io/CI_MS2_DCG/index.html) 

hangman.html [results](https://wave.webaim.org/report#/https://jamie2210.github.io/CI_MS2_DCG/hangman.html)

quiz.html [results](https://wave.webaim.org/report#/https://jamie2210.github.io/CI_MS2_DCG/quiz.html)

contact.html [results](https://wave.webaim.org/report#/https://jamie2210.github.io/CI_MS2_DCG/contact.html)

404.html [results](https://wave.webaim.org/report#/https://jamie2210.github.io/CI_MS2_DCG/404.html)

### Performance 
Google Lighthouse in Google Chrome Developer Tools was used to test the performance of the website. All results scoring 95 or above.

<details><summary>index.html</summary>
<img src="docs/validation/lighthouse/index.png">
</details>
<details><summary>hangman.html</summary>
<img src="docs/validation/lighthouse/hangman.png">
</details>
<details><summary>quiz.html</summary>
<img src="docs/validation/lighthouse/quiz.png">
</details>
<details><summary>contact.html</summary>
<img src="docs/validation/lighthouse/contact.png">
</details>
<details><summary>404.html</summary>
<img src="docs/validation/lighthouse/404.png">
</details>

### Performing tests on various devices 
The website was tested on the following devices:
- MacBook Pro
- iPad Tablet
- Google Pixel 5
- iPhone 12

In addition, the website was tested using Google Chrome Developer Tools device toggle option for all available device options.

### Browser compatibility
The website was tested on the following browsers:
- Google Chrome
- Apple Safari
- Mozilla Firefox

## Testing user stories


### Site User (General)


1. I want to easily understand the rules of each game.

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| '?' Icon | Click either '?' icon | Modal pops up explaining rules of choses game | Works as expected |

<details><summary>Find Rules</summary>
<img src="docs/user-story-testing/user-story-rules.gif">
</details>
<br>

2. I want to easily navigate to my chosen game.

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Button | Click button | Takes user to chosen game | Works as expected |

<details><summary>Find Buttons</summary>
<img src="docs/user-story-testing/user-story-buttons.gif">
</details>
<br>

3. I want the games to be fun, enjoyable and easy to understand.

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| '?' Icon | Click either '?' icon | Modal pops up explaining rules of choses game | Works as expected |
| Button | Click button | Takes user to chosen game | Works as expected |
| In-game Play | Games are easy to follow, pleasing on the eye and fun | In-game play | Work as expected |
| Score Modal | Finish each game | Humorous modal pops up displaying score. | Works as expected |

<details><summary>Find Rules</summary>
<img src="docs/user-story-testing/user-story-rules.gif">
</details>
<details><summary>Find Buttons</summary>
<img src="docs/user-story-testing/user-story-buttons.gif">
</details>
<details><summary>Play Hangman</summary>
<img src="docs/user-story-testing/user-story-play-hangman.gif">
</details>
<details><summary>Play Quiz</summary>
<img src="docs/user-story-testing/user-story-play-quiz.gif">
</details>
<br>

4. I want to know how I did at the end of each game, and easily play again.

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Score Modal | Finish each game | Humorous modal pops up displaying score. | Works as expected |
| Play Again | Finish game | Close modal, game resets, score is tallied. | Works as expected |

<details><summary>Hangman Score</summary>
<img src="docs/user-story-testing/user-story-play-hangman.gif">
</details>
<details><summary>Quiz Score Modal</summary>
<img src="docs/user-story-testing/user-story-score-modal.gif">
</details>
<br>

5. I want a means to contact the developer and have confirmation the message has been sent.

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Email Icon | Click Icon | Takes user to contact page | Works as expected |

<details><summary>Find Contact Form</summary>
<img src="docs/user-story-testing/user-story-contact-form.gif">
</details>
<br>

### Hangman


6. I want to play the game both by clicking the mouse and using the keyboard.

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Keyboard Test | Use mouse & keyboard | Key should highlight when pressed / clicked down then disable after | Works as expected |

<details><summary>Find Keyboard</summary>
<img src="docs/user-story-testing/user-story-keyboard.gif">
</details>
<br>

7. I want to know which letters I’ve used already.

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Keyboard Test | Use mouse & keyboard | Key should highlight when pressed / clicked down then disable after | Works as expected |

<details><summary>Find Keyboard</summary>
<img src="docs/user-story-testing/user-story-keyboard.gif">
</details>
<br>

8. I want to know how many guesses I have left.

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Guesses Left | Select incorrect key | Guess left display increases by one | Works as expected |

<details><summary>Find Guesses Left</summary>
<img src="docs/user-story-testing/hangman-screen.png">
</details>
<br>

9. I want the gallows image to add on sections of the hangman each time a letter is guessed incorrectly.

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Gallows Image | Select incorrect key | Gallows image adds body part | Works as expected |

<details><summary>Find Gallows</summary>
<img src="docs/user-story-testing/user-story-keyboard.gif">
</details>
<br>

10. I want to see to my score of wins vs losses.

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Main screen | Win or lose game | Score is updated | Works as expected |
| Result Modal | Win or lose game | Score is displayed | Works as expected |

<details><summary>Find Score</summary>
<img src="docs/user-story-testing/hangman-screen.png">
</details>
<details><summary>Find Results Modal</summary>
<img src="docs/user-story-testing/win-modal.png">
</details>
<br>

### Quiz


11. I want to know how much time is left to answer the question.

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Countdown Timer & Bar | Start game | Countdown timer and time bar are displayed | Works as expected |

<details><summary>Find Timer / Bar</summary>
<img src="docs/user-story-testing/game-modal.png">
</details>
<br>

12. I want to know which answer is correct if answered incorrectly.

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Highlight correct answer | Select incorrect option | Correct answer is displayed | Works as expected |

<details><summary>Find Correct Answer</summary>
<img src="docs/user-story-testing/user-story-play-quiz.gif">
</details>
<br>

13. I want to know the answer if I run out of time.

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Highlight correct answer | Let time run out | Correct answer is displayed | Works as expected |

<details><summary>Find Out Of Time</summary>
<img src="docs/user-story-testing/user-story-correct-out-of-time.gif">
</details>
<br>

14. I want to see my score at the end.

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Quiz Finish Modal | Finish Quiz | Score is tallied | Works as expected |

<details><summary>Find Finish Modal</summary>
<img src="docs/user-story-testing/user-story-finish-modal.gif">
</details>
<br>

15. I want to easily play again or quit once I have finished.

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Quiz Finish Modal | Finish Quiz | Restart and Quit buttons displayed | Works as expected |

<details><summary>Find Restart / Quit</summary>
<img src="docs/user-story-testing/user-story-finish-modal.gif">
</details>
<br>

#### Site Owner 
16. I want the user to get a genuine feel this is a DC Batman themed site. 

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Batman Theme | Display pages | All colours and imagery are that of DC's Batman animated series | Works as expected |

<details><summary>Find Theme</summary>
<img src="docs/user-story-testing/user-story-dc-theme.gif">
</details>
<br>

17. I want the user to easily understand how to play the games.

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| '?' Icon | Click either '?' icon | Modal pops up explaining rules of choses game | Works as expected |

<details><summary>Find Rules</summary>
<img src="docs/user-story-testing/user-story-rules.gif">
</details>
<br>

18. I want both games to be fully responsive.

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Responsiveness | Test in google developer | Adjusts to each device correctly | Works as expected |

<details><summary>Find Responsive Home Page</summary>
<img src="docs/user-story-testing/user-story-responsive-index.gif">
</details>
<details><summary>Find Responsive Hangman</summary>
<img src="docs/user-story-testing/user-story-responsive-hangman.gif">
</details>
<details><summary>Find Responsive Quiz</summary>
<img src="docs/user-story-testing/user-story-responsive-quiz.gif">
</details>
<br>

19. In hangman, the phrases / words are limited, so to increase the difficulty and longevity of the game, the phrase will not be revealed if guessed incorrectly.

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Score Modal | Finish each game | Score displayed but he hidden phrase is not | Works as expected |

<details><summary>Find Score Modal</summary>
<img src="docs/user-story-testing/user-story-incorrect-score-modal.gif">
</details>
<br>

20. I want the user to be able to contact me for any reason they feel fit.

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Email Icon | Click Icon | Takes user to contact page | Works as expected |

<details><summary>Find Contact Form</summary>
<img src="docs/user-story-testing/user-story-contact-form.gif">
</details>
<br>

21. I want the user to come to a 404 page and be automatically re-directed to the home page should they enter an invalid url.

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| 404 Page | Enter invalid url | 404 page is displayed, countdown timer returns user to home page | Works as expected |

<details><summary>Find 404</summary>
<img src="docs/user-story-testing/user-story-404.gif">
</details>
<br>

22. I want the user to have a link to my work via my Github repositories. 

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Github Icon | Click Icon | Takes user to repository page for the game | Works as expected |

<details><summary>Find Github</summary>
<img src="docs/user-story-testing/user-story-github.gif">
</details>
<br>

## Bugs

### Hangman

1. Each time a key on the board selected an incorrect word two mistakes were added instead of one. The checkLetter function was called in both the keydown and keyup event listeners. By removing it in one fixed the issue.

2. During testing when using some iPhones all the button styling was off. This is down to using default button stlying. To fix I added my own styling to match that of the chrome default.
<details><summary>iPhone Default</summary>
<img src="docs/bugs/iphone-bug.png">
</details>
<details><summary>iPhone Fix</summary>
<img src="docs/bugs/iphone-fix.png">
</details>
- This caused more errors, when I added a #000000 color class to the buttons to prevent the blue default as it stopped the default disabled display from working. To work around the issue, I added a 0.5 opacity to the disabled class which fixed the issue as it then clearly indicates which buttons were are disabled.

```css
        .button-keys:disabled {
            opacity: 0.5;
        }
```
4. I really wanted my 'Reset' button to change yellow on 'keydown' like it does with a mouse click, my first attempt isolated the enter to key to only work on the reset button. This had a negative effect on the other buttons and affected accessibility as enter no longer worked on any other buttons. I then ran into issues with the event listeners being constantly active once called on which caused the 'Reset' button to constantly flash yellow if enter was pressed. This was eventually fixed by adding removeEventListener functions if enter is pressed when the reset button was not targeted.

```javascript
        function removeEventListeners() {
            document.removeEventListener('keydown', keyDown);
            document.removeEventListener('keyup', keyUp);
        }
        if(!keyDownButton || !keyUpButton) {
            removeEventListeners();
            }
```

### Quiz

3. When the user selected an answer the timer continued to tick down and if it then reached 0 the function was called to display the right wrong or answer, which were already on display as an answer was already clicked. This caused the game to display icons twice and looked messy. It was fixed by adding the clearInterval function to the answerSelected function once one had been clicked, resulting in the timer freezing until the next question button is clicked.

4. When the user clicked restart the question number was not reset, so the game displayed 10 out 10 questions instead of 1 out 10. To fix this I reset the question number to 1 in the restart function.

5. Issue with the display not covering the full screen on certain screen dimensions, particularly long / tall iPads in google developer tools. Fixed by adding a specific vh height to the title in media queries.

##### Media Query commands
```css
        @media screen and (max-width:920px) {
            #hangman-title {
            height: 40vh;
            }
        }
```

## Deployment
The website was deployed using GitHub Pages by following these steps:
1. In the GitHub repository navigate to the Settings tab.
2. On the left-hand menu select Pages.
3. For the source select Branch: main.
4. After the webpage refreshes automatically you will see a ribbon on the top saying: "Your site is published at https://jamie2210.github.io/CI_MS2_DCG/index.html.

You can for fork the repository by following these steps:
1. Go to the GitHub repository.
2. Click on Fork button in upper right-hand corner.

You can clone the repository by following these steps:
1. Go to the GitHub repository .
2. Locate the Code button above the list of files and click it.
3. Select if you prefer to clone using HTTPS, SSH, or Github CLI and click the copy button to copy the URL to your clipboard.
4. Open Git Bash.
5. Change the current working directory to the one where you want the cloned directory.
6. Type git clone and paste the URL from the clipboard ($ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY).
7. Press Enter to create your local clone.

## Credits

Images and logos not referenced below are owned or created by the developer. 

All images used have a free licence for personal use.

### Media

Images taken from [Clipartmax](https://www.clipartmax.com/);

- [DC Logo](https://www.clipartmax.com/max/m2i8H7b1m2A0m2Z5/)
    <details><summary>DC Logo</summary>
    <img src="docs/credits/dc-logo.png">
    </details>
<br>

- [Batman](https://www.clipartmax.com/middle/m2i8N4i8Z5i8Z5i8_batman-from-batman-the-animated-series-by-alexbadass-batman-the-animated-series/)
    <details><summary>Batman</summary>
    <img src="docs/credits/batman2.png">
    </details>
<br>

- [The Riddler](https://www.clipartmax.com/middle/m2H7i8K9H7d3K9K9_riddler-design-batman-the-animated-series/)
    <details><summary>The Riddler</summary>
    <img src="docs/credits/riddler1.png">
    </details>
<br>

- [The Riddler Logo](www.clipartmax.com/middle/m2H7K9i8m2i8i8N4_logo-clipart-riddler-villian-riddler/)
    <details><summary>The Riddler Logo</summary>
    <img src="docs/credits/riddler_logo.png">
    </details>
<br>

- [The Joker](https://www.clipartmax.com/middle/m2i8d3d3m2d3N4d3_the-joker-by-dawidarte-batman-the-animated-series-joker/)
    <details><summary>The Joker</summary>
    <img src="docs/credits/joker.png">
    </details>
<br>


Images taken from [pngimg](https://pngimg.com/);

- [Batman Logo](https://pngimg.com/image/29078)
    <details><summary>Batman Logo</summary>
    <img src="docs/credits/batman_logo.png">
    </details>
<br>

- [Batman](https://pngimg.com/image/29060)
    <details><summary>Batman</summary>
    <img src="docs/credits/batman-head.png">
    </details>
<br>

Images taken from [Free Vector](https://www.freevector.com/);

- [Batman Background](https://www.freevector.com/free-batman-illustration-29232)
    <details><summary>Batman Background</summary>
    <img src="docs/credits/batman-background.png">
    </details>
<br>

Images taken from [Vecteezy](https://www.vecteezy.com/);

- [Gallows - yoosillyone](https://www.vecteezy.com/vector-art/169206-gallows-vector-icons)
    <details><summary>Gallows</summary>
    <img src="docs/credits/gallows-vector-icons.jpg">
    </details>
<br>

- [Grass](https://www.vecteezy.com/vector-art/6960062-green-grass-illustration-isolated-white-background)
    <details><summary>Grass</summary>
    <img src="docs/credits/grass.jpg">
    </details>
<br>

Images taken from [freepik](https://www.freepik.com/);

- [Robin](https://www.freepik.com/free-vector/hand-drawn-robin-collection_18895184.htm#query=robin%20bird%20free&position=38&from_view=search&track=ais)
    <details><summary>Robin</summary>
    <img src="docs/credits/robin2.png">
    </details>

### Code 

- The Javascript for [Sweet Alert](https://sweetalert.js.org/guides/) email submit response was taken from the Sweet Alert guide.

- Guidance was taken from this tutorial [Useful Prgrammer](https://www.youtube.com/watch?v=7XbsQlwyHYw) to add tab answer function to quiz answer selection and question icons.

- [Stack Overflow](https://stackoverflow.com/questions) was used throughout for hints, tips and tricks.

- [w3schools](https://www.w3schools.com/jsref/met_win_setinterval.asp) was used for a better undertstanding of set intervals and timers.

- [MDN](https://developer.mozilla.org/en-US/docs/Web/API/EventTarget/removeEventListener) helped me understand removeEventListeners further.

- Inspiration and guidance for hangman was taken from [Simon Suh](https://www.youtube.com/watch?v=dgvyE1sJS3Y) hangman Game tutorial on youtube.

- Inspiration and guidance for a quiz with a timer was taken from [Ali Aslan](https://www.youtube.com/watch?v=xZXW5SnCiWI&t=224s) quiz tutorial on youtube.

### Acknowledgements

I would like to take the opportunity to thank;

- My mentor, Mo Shami, for his excellent feedback, advice support and guidance throughout.
- Tutor support from Code Institute for their swift response.
- The slack community of coders for immediate and helpful response.
- WAES College and my Tutor Michael for their support and help throughout.



