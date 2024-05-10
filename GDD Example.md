---
tags:
  - Literary
DocType: Literary Note
Created: 10 05 2024
Type:
---
# GDD Example <!Title>
---
# Table Of Content
- [[#Introduction]]
- [[#Game Summary]]
- [[#Inspiration]]
- [[#Player Experience]]
- [[#Development Software]]
- [[#Target Audience]]
- [[#Gameplay overview]]
- [[#Theme Interpretation]]
- [[#Primary Mechanics]]
- [[#Secondary Mechanics]]
- [[#Art]]
- [[#Theme Interpretation]]
- [[#Design]]
- [[#Audio]]
- [[#Music]]
- [[#Sound Effects]]
- [[#Game Experience]]
- [[#UI]]
- [[#Controls]]
- [[#Development Timeline]]

---
## <!Game Logo Pic>

>[!quote]- ## Introduction
>>[!quote]- ### Game Summary Pitch
> > Mass Flux is a tile based puzzle game about reducing or generally manipulating the shape of a mass of cell-blocks to navigate to a goal.
>
>>[!quote]- ### Inspiration! 
>>#### Snakebird
>><!Inspiration Pic>
>>
>>Snakebird provides the ingenuity for the player to control a body that isn't always helpful and will certainly get in the way more often than aid one’s plan. A long body in that game may be susceptible to support the player from falling but often can restrict and block certain movement making puzzle areas much harder  to navigate.  
 >>
>>
>>#### Baba Is You!
>><!Inspiration Pic>
>>
>>Baba is You is the main inspiration towards the style and mood of the game. Especially graphics-wise to fit the 2-bit graphical prompt, the minimalist art style will hold useful to act as a base. Otherwise, the gameplay also further provides inspiration towards level design as an abstract puzzle game.

---

>[!quote]- ## Player Experience
>In a single screen dungeon for each of the 15 levels, the player will solve a short but perhaps complex puzzle requiring planning and management. The player must learn and use their knowledge of the interactions between the player cells and various environmental items to understand how to pass through each level.
>
>>[!quote]- ### Platform
>>The game is developed to be released on windows PC
>
>>[!quote]- ### Development Software
>>- software 1
>
>>[!quote]- ### Genre
>>Single player, puzzle, casual
>
>>[!quote]- ### Target Audience
>>Without heavy or complicated ideas, and intuitive-to-grasp mechanics, this game is marketed to at least casual game players who are up for puzzling challenges as well as more veteran players up for solving complicated problems

---

>[!quote]- ## Concept
>>[!quote]- ### Gameplay overview
>>The player controls a mass of player cells, each with individual status, but moves as a collective. Individual cells may die or be created which influences the total shape of the mass. By navigating through each level, the player must strategically manipulate the shape of the mass to be able to pass around or through obstacles to reach the goal. 
>
>>[!quote]- ### Theme Interpretation (Sacrifice Is Strength)
>>‘Sacrifice’ interpretation - The player voluntarily offers something they would otherwise use to their benefit to then gain something else of use in its stead.
>
>Within the context of a puzzle game, rather than a sacrifice strictly being an optional upgrade of sorts, the timing, placement, and orientation a ‘sacrifice’ within this game instead occurs to allow the solution or progression of the puzzle. Only through careful planning of movement to remove parts of the player’s mass can the player make their way to the exit. One must often sacrifice a part of the player mass to pass through specific areas as they may be too large or encompass the wrong shape.

---
### Primary Mechanics

| Mechanic                                                                                                                                                                                    | Animated Mockup <br><br>(Art not necessarily final)                                                                                                                                                                                         |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Walls         a  <br>  <br><br>A stopping force to prevent a player too large to access a certain area. Otherwise to simply restrict movement.                                              | ![](https://lh7-us.googleusercontent.com/docsz/AD_4nXc9VB2FZyUzetAGvwgwtTw4tMc440V9aasUeKOsqUNss_DeZsIx_m0xb0hXzFySSG7jMsUPWSgg4WBF4pfEH1T-xyUdGPkaQiwPa1HPHExkPeRQd3YSdQGkVwOgyXkOJZAs77NkVcMu1mcrwLw3JpFjomzE?key=d7gir74Uz3A5l5Q8v8UZKg) |
| Spikes        a  <br>  <br><br>When a player cell walks on top of a spike, that cell will die and further simplify the player mass.                                                         | ![](https://lh7-us.googleusercontent.com/docsz/AD_4nXfmY-X6_7eO54oADINTaM17lqzjYtOutH6WHg7EB_NIEWNb5gmG5W7YwtmABhlUlwnt01xlakDaunmh5m_vo9XFn3N1l4aJ2MjfXghCeGLD7GZOtEkFbuobB3kHCklh9_NF5aN4jEZoPYzalzhzbPRUzsI?key=d7gir74Uz3A5l5Q8v8UZKg)  |
| Holes       a  <br>  <br><br>The player mass can walk freely over a hole as long as at least one cell is on a floor tile. If the entire mass is over the hole, the entire player mass dies. | ![](https://lh7-us.googleusercontent.com/docsz/AD_4nXcvjEkBxp_FcPpygM9PeV21brQWWkgOzgP3JPAwgXHTY1yn7VHM4mJD7_z9FOzghQ0GWvmI-ZuWzvtkkymMhv6v5SbLbLq_GBCnEbbZC1YLz5nOFaO4b-NqFwP4KkMsqIazXAFssMcLgPG8E0fNq488yEU?key=d7gir74Uz3A5l5Q8v8UZKg)  |
| Fruit       a  <br>  <br><br>If a player cell moves over a fruit, it will eat the fruit and generate a new cell on the opposite side of the mass it is a part of.                           | ![](https://lh7-us.googleusercontent.com/docsz/AD_4nXf7Fi249hxsWq3uLYInkR9WhnLxlcxQt6JuloVNqShRzk8u9EtX651YvQE4szhPLNtAToX73RZeR3XH51bzx3qKvxkrEB0YQ52iCCenEu08Es3W4COUiwhUOUHOaajeLtyMKSmkmE1_5M-sgpBu-VnYY4Bt?key=d7gir74Uz3A5l5Q8v8UZKg) |

### Secondary Mechanics

| Mechanic                                                                                                                                                                                                                           | Animated Mockup <br><br>(Art not necessarily final)                                                                                                                                                                                         |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Independence        a  <br>  <br><br>If two player masses happen to separate, they will still move synchronously but interact with the environment independently. If then connected again, the two masses will join to act as one. | ![](https://lh7-us.googleusercontent.com/docsz/AD_4nXeLzXGcAtYs3X31XqRbixeMeN6-ztOoGsaIQoI6m1eLEfsazCnK86kCGuq1or2lmPzUjyujINXnZzTg5lGgbCSvoj1MgTYQG0KPEfohqfxjtx_Zcws4i_GLeG5EwT9h7Ef-PT0Z8uJuWJFPhIhxrhRT5SnJ?key=d7gir74Uz3A5l5Q8v8UZKg) |
| Set Spikes        a  <br>  <br><br>When a player cell walks on top of a set spike, after moving off of it, it will then become a regular spike trap                                                                                | ![](https://lh7-us.googleusercontent.com/docsz/AD_4nXcIvzeNafmE132dkLPQs5sh8Xkr7zcQ4bRREYR1WERDGc8GJOocKGhN73M5GG5zyrQLmkzNT5eqGhFBksxZu9Cz-6mfLI_9t1bKjPduT1D1l3nEkPiPxSZDN0hh-s8OIn9s_Ab5bz8h9PQSgMfZsClzHvZo?key=d7gir74Uz3A5l5Q8v8UZKg) |

>[!quote]- ## Art
>>[!quote]- ### Theme Interpretation
>>[!quote]- While maintaining the very limited color palette theme, the sole use of black in white seems way too common, and a bit harsh as a color scheme for a relaxing puzzle game. To circumvent this, a soft, dark blue color will act as the unique accent color as opposed to black with white being the primary, carrying color to base the sprites off of.![](https://lh7-us.googleusercontent.com/docsz/AD_4nXdg6_Ua9WqbEB2rtk6hqineHUz0UxDoatKSDZioSNArEXVwNr0PFE5l3HtJZT3zoNmzzCelF4tGg9QjyZ-SsiE5t938G5dVKKRjkTVaC7tnFvPDcxZMWu_7ZltqFcDpyafHGiDpEB1QBWJJJemPSiQnRmqp?key=d7gir74Uz3A5l5Q8v8UZKg)
>
>>[!quote]- ### Design
>>A very minimalistic approach will go into the design of the game, heavily relying on the severe contrast of the limited colors to provide detail. Though, the design still is clean and smooth in the sense that, the use of many shades of a color will not be as present to confront the retro style and pixel art.
>
><!Pic>
>
>*Not an actual puzzle/level, merely a full example of the tileset and art style*

---
>[!quote]- ## Audio
>>[!quote]- ### Music
>>To add to the overall theme and vibe of the game, there will be minimalism incorporated into the music. Heavy use of reverb and effects to fill space within the few instruments. Bass and drums will generally constitute the majority of tracks with accompanying softer sounds. Mainly through synthesized sounds rather than acoustic will further suggest the retro style.
>
>>[!quote]- ### Sound Effects
>>To add more flare and polish to the experience, a multitude of environmental sound effects will give weight and feedback to the player’s actions. Rather than foley, or otherwise realistic sounds, synthesized blips, bloops, and whooshes are used.

---
>[!quote]- ## Game Experience
>>[!quote]- ### UI
On top of the rigid pixel art constituting the rest of the art, a more smooth, higher definition style will be incorporated in the UI. Utilizing many shades of white and black allowed in the art restriction, anti-aliasing is used to further emphasize the UI.
>
>>[!quote]- ### Controls
>> - Keyboard
>> - Arrow keys / WASD  
>> - Gamepad
>> - Dpad

## Development Timeline
### MINIMUM VIABLE PRODUCT

|#|Assignment|Type|Status|Finish By|Notes|
|---|---|---|---|---|---|
|1|Design Document|Other|Finished|Jun 22, 2022||
|2|Create player and wall assets|Art|Finished|Jun 23, 2022|Prototype for GDD is done|
|3|Main menu theme|Audio|Finished|Jun 23, 2022|Can be really short, player won’t be on main menu for long|
|4|UI / Main menu|Coding|Finished|Jun 23, 2022|Button UI, screen transition, title screen|
|5|Level theme|Audio|Finished|Jun 24, 2022|Should be more substantial and not annoying|
|6|Simple player movement|Coding|Finished|Jun 23, 2022|Move single cells around and collide with walls|
|7|Complex player movement|Coding|Finished|Jun 24, 2022|Multi cell masses act together to collide with walls|
|8|Spikes and holes with player interactions|Coding|Finished|Jun 24, 2022|Implement spike and holes mechanics|
|9|Fruit interaction|Coding|Finished|Jun 25, 2022||
|10|Special effects|Art|Finished|Jun 25, 2022|Dust particles during movement|
|11|Player animation|Art|Finished|Jun 25, 2022|Idle blinks, movement polish|
|12|Sound effects|Audio|Finished|Jun 25, 2022|Player movement, UI interaction|
|13|Pause menu|Coding|Finished|Jun 26, 2022|Access to the main menu or resetting the level|
|14|Level select menu|Coding|Finished|Jun 26, 2022||
|15|Level design (1-7)|Other|Finished|Jun 27, 2022|Create levels 1 through 7|
|16|Level design (8-15)|Other|Finished|Jun 28, 2022|Create levels 7 through 15|
|17|Any extra polish|Other|Finished|Jun 29, 2022||
|18|SUBMIT|Other|Finished|Jun 29, 2022|Create Itch Page and upload|

### BEYOND (if ahead of schedule / extra time)

|   |   |   |   |
|---|---|---|---|
|Undo|Other|Not started|At any point, the player may undo their move, any movement, creation, or destruction of a player cell is reversed|
|Extra levels|Other|Not started||
|Settings Menu|Coding|Finished|Volume slider, fullscreen toggle|**



