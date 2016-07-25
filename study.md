# Game Project Scope Study

## Required Readings

-   [Game Project](https://github.com/ga-wdi-boston/game-project)
-   [Game API](https://github.com/ga-wdi-boston/game-project-api)
-   [What is a User Story](http://searchsoftwarequality.techtarget.com/definition/user-story)

## Deliverables

After reading the `game-project` prompt and the `game-project-api` documentation
please do the following and be prepared to share and discuss during our next
class.

Submit detailed answers to these in this file via a pull request.

-   A wireframe of what your game project will look like.

```md
http://imgur.com/SpgvwFO
```

-   The data structure you plan to use.

```md
All JavaScript files will be within the same folder called JS (most likely).
All files regarding sign-up, sing-in, sign-out and change password will be within folder called auth and scirpts.
I'm still not sure about branches.
HTML file is called index.html and it is already added and commited and it looks ok. You can see it here: http://imgur.com/AgcIzOo
CSS file is within folder called styles.
```
-   How you will take the markup of the game board and represent it in JS

```md
 I would like to represent each box with a certain value. X would have value of 1 and O would have value of 2, and a box that hasn't been clicked yet would have value of 0. With each itteration I plan to test if the total value in each direction is a certain number, and use that to find out if the game has a winner. If there isn't a winner, I would test if any of the boxes have value of 0 (it means that game can continue). After all boxes are clicked and there is no winner, the game needs to start over.

I have already added and commited selecting X and Os using DOM.
```

-   How you plan to approach this project.

```md
Small steps. First I want to focus on the game (not much on the layout), and then everything else (sign in, sign out etc.)
```

-   4-8 user stories for your game project.

```md
As a user, I want to sign up and play the game.
As a user I want to know when is my turn.
As a user I want to know when the game is over.
As a user I want to sign out.
```

-   How you plan to keep your code modular.

```md
Not there yet.
```

-   What creative spin will you add to your project.

```md
I might add a picture or jQuery attributes for changing background color etc.
```
-   How you will use version control to backup / track your project.

```md
Commiting every 10 minutes. (goal)
```
-   Do you plan to attempt any of the bonuses.

```md
Only if I meet all requirements. Othewise, no, I don't plan to do any of the bonuses.
```
