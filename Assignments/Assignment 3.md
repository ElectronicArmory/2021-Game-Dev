# Game Dev Assignment 3 - Due Tuesday, June 1

## Base Requirements
Develop another, new 3D top down, first person, or third person crawler game and have some kind of win and lose condition.

1. Custom modeled mesh for main character
   1. Animated with 2 different animations/actions
   2. Have at least 10 bones and the root bone (total of 11)
   3. Animation Blueprint with state machine
   4. At least 2 materials
2. 3D top down, first person, or third person crawler game using the Character class (a subclass of Pawn).
3. Keyboard input for movement and/or interaction ([Action Mappings](https://www.unrealengine.com/en-US/blog/input-action-and-axis-mappings-in-ue4)).
4. Mouse input that interacts with the environment and/or moves the camera or player.
5. 2 custom models for props that you make.
6. 3 modular level pieces (straight, turn and end piece).
7. 2 different pick up objects that require interaction to pick up ([see Blueprint example](https://blueprintue.com/blueprint/86idfukr/)). Can be a health kit, key, treasure or something else.
8. Include one puzzle, problem to solve, surprise or something to accomplish.
9. All visible objects need to have materials applied to them.
10. Add a Heads Up Display (HUD) for player feedback.
11. Add a level that contains a start screen and at least one menu item (start game).
12. Lose condition with new end game level or UI widget. Must provide ability to return to main menu or main game (restart).
13. Win condition with new game level or UI widget.
14. Add health, shield, energy, mana, fuel progress bars or equivalent in your game. Pickups or something else must be able to change these values.
15. Add variable light source.
16. Use a Timeline to move an object, affect lighting, or change some property over time.
17. Add a story via voice over or text. You can use a timer to change text.
18. Posted to Itch.io account as new game.
19. 2 Screenshots on Itch.io page.
20. Video on Itch.io page. Around 30-60 seconds or longer.
21. Developer Video posted on Itch.io. 2 minutes or more showing each point in the list

## Extra Requirements
1. Add torches or other lighting effect with particles. You can get these from the starter content. If your game is a space game, you might have a control panel that sparks when activated.
3. Add sound effects for various feedback such pick up, doors opening, walking, UI hover or clicks and more.
3. Character performs animation based on keyboard or mouse input
4. Include a Blend Space with three different animations (instead of a state machine)
5. Have a different idea? Let me know!


## Game Examples:
[Elder Scrolls 2: Daggerfall](https://elderscrolls.bethesda.net/en/daggerfall)

[Police Quest 3: Kindred](https://en.wikipedia.org/wiki/Police_Quest_III:_The_Kindred)

[Earthrise](https://en.wikipedia.org/wiki/Earthrise_(1990_video_game))

[Play Earthrise](https://www.myabandonware.com/game/earthrise-vz)


## Grading
Completing all Base Requirements fully will result in a grade of 80%. To get the additional 20%, complete at least 2 additional extra requirements of your choice.



## Submitting
Export your game from Unreal Engine:

- File -> Package Project -> Build Configuration -> Shipping
- File -> Package Project -> Windows and/or macOS
- Zip up the resulting files
- Upload zipped file to Itch.io
- Add a short description and at least 2 screenshots to Itch.io page.
- Add a video of gameplay (Voice over is your choice) to the Itch.io page.
- Publish and ensure page is visible.
- Post the link in #game-dev-submission in the Discord channel

