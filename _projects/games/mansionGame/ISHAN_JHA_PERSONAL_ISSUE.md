# Ishan Jha Personal Issue -- Level 5 Mansion Game

## Summary of Personal Contributions
As a scrum master I delegated work to everybody and ensured team cooperation. I also led most ideation and developing strategies. Personally, as the **Product Owner**, I was the one who created the environment for everybody to work out of it, as well as counseling other levels and assisting them if they had any questions.

## Evidence of Work

<img src="https://github.com/user-attachments/assets/e5979200-892d-4ef4-94fa-fd8689da8f9e">

I had 8 commits for our level during this time.

I also set up the original game structure by moving mansionGame to _projects as you can see here through these 2 commits.

<img src="https://github.com/user-attachments/assets/f25869ae-67e1-47cb-b42d-c84c2181b5f2">

## Specific Commit Details
Here I highlight key contributions in each commit and what I specifically worked on.

## 'wip' and 'game functioning now!'
In commits 'wip' and 'game functioning now!' (commit hashes `0c4c991` and `c8bac8e`) my main goal was to set up the game environment for everybody. My key changes were:
- Moving the old mansionGame from trimester 1 over to the `_projects` directory
  - This moved the old mansionGame files into the `_projects` folder and organized it within the new directory structure.
- Adjusting code to rely on new asset paths so that the file would load.

Key files changed:
- `_projects/.makeprojects`
- `_projects/games/mansionGame/notebook.src.ipynb`
- `_projects/games/mansionGame/js/GameControl.js`
- `_projects/games/mansionGame/js/mansionLevel1.js`
- `_projects/games/mansionGame/js/mansionLevel2.js`
- `_projects/games/mansionGame/js/mansionLevel3.js`
- `_projects/games/mansionGame/js/mansionLevel4.js`
- `_projects/games/mansionGame/js/mansionLevel5.js`
- `_projects/games/mansionGame/js/mansionLevel6.js`
- `_projects/games/mansionGame/images/*` (core game assets and level sprites)

<img src="https://github.com/user-attachments/assets/cf313f15-253f-409a-8987-432246740d49">

<img src="https://github.com/user-attachments/assets/c7604385-07ac-415e-9b55-077cf13edcfa">

## 'intial codex run (needs to be debugged)' and 'full wheel of fortune game'
In commits `c3e4504` and `1bfb2fb`, I focused on building and integrating the full Level 5 mini-game loop. My key changes were:
- Added a new `WheelOfFortune` game manager class for the Level 5 challenge UI and gameplay flow.
- Refactored Level 5 to use the wheel mini-game as the gating challenge.
- Improved the in-level interaction marker and visual emphasis for the wheel interaction point.

Key files changed:
- `_projects/games/mansionGame/levels/WheelOfFortune.js`
- `_projects/games/mansionGame/levels/mansionLevel5.js`

## 'asset switch' and 'wordbank + word formatting fix'
In commits `347f8bb` and `33ca2e6`, I focused on polish and usability improvements to make the mini-game clearer and more replayable. My key changes were:
- Switched the table interaction indicator asset to a clearer key-based marker.
- Added a phrase bank so Wheel of Fortune can choose from multiple phrases.
- Improved puzzle word layout formatting so phrase display is easier to read word-by-word.

Key files changed:
- `_projects/games/mansionGame/levels/mansionLevel5.js`
- `_projects/games/mansionGame/levels/WheelOfFortune.js`

## 'fix the level returning' and 'Potential fix for pull request finding'
In commits `674421d` and `c1863e9`, I focused on transition stability and cleanup after Level 5 completion. My key changes were:
- Updated Level 5 completion flow to return to `MansionLevelMain` instead of routing to Level 6.
- Updated door dialogue and interaction text to match the return-to-main-world behavior.
- Cleaned up wheel initialization data to simplify the implementation and address pull-request feedback.

Key files changed:
- `_projects/games/mansionGame/levels/mansionLevel5.js`
