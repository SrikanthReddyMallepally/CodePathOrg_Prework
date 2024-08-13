# WEB102 Prework - _Sea Monster Crowdfunding_

Submitted by: **Srikanth Reddy Mallepally**

**Sea Monster Crowdfunding** is a website for the company Sea Monster Crowdfunding that displays information about the games they have funded.

Time spent: **20** hours spent in total

## Required Features

The following **required** functionality is completed:

- [x] The introduction section explains the background of the company and how many games remain unfunded.
- [x] The Stats section includes information about the total contributions and dollars raised as well as the top two most funded games.
- [x] Our Games section initially displays all games funded by Sea Monster Crowdfunding
- [x] Our Games section has three buttons that allow the user to display only unfunded games, only funded games, or all games.

The following **optional** features are implemented:

- [x] search functionality is added to website to filter the games based on search keyword.
- [x] Hover effect animation for the buttons.

## Video Walkthrough

Here's a walkthrough of implemented features:

<img src='https://github.com/SrikanthReddyMallepally/CodePathOrg_Prework/blob/main/Animation.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

<!-- Replace this with whatever GIF tool you used! -->

GIF created with

- [x] ScreenToGif

## Notes

    Features

    1. button hover animation involves a button with an :after pseudo-element that creates a dynamic background effect when hovered. Initially, the pseudo-element is positioned far to the left and slightly upward, with a 45-degree clockwise rotation. On hover, it smoothly shifts horizontally closer to the button's center while maintaining its vertical position and rotation. This movement is animated over 0.5 seconds, using an ease-in-out timing function, resulting in a subtle yet engaging visual transition as the background element slides into view.

    2. The JavaScript code snippet sets up a search functionality for an HTML input field (searchBox). As the user types in the search box, an event listener triggers a real-time filter on a list of games (GAMES_JSON). It compares the input keyword with the names of the games, filtering out those that don't match. The filtered results are then dynamically updated on the webpage by clearing the current content (gamesContainer) and displaying the matching games using the addGamesToPage function. This provides an interactive, instant search experience based on the user's input.

## License

    Copyright [2024] [Srikanth Reddy Mallepally]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
