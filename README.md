# WEB102 Prework - *Game Time!*

Submitted by: **Kimberly Ticlavilca**

**Game Time!** is a website for the company Sea Monster Crowdfunding that displays information about the games they have funded.

Time spent: **5** hours spent in total

## Required Features

The following **required** functionality is completed:

* [ ] The introduction section explains the background of the company and how many games remain unfunded.
* [ ] The Stats section includes information about the total contributions and dollars raised as well as the top two most funded games.
* [ ] The Our Games section initially displays all games funded by Sea Monster Crowdfunding
* [ ] The Our Games section has three buttons that allow the user to display only unfunded games, only funded games, or all games.

The following **optional** features are implemented:

* [ ] List anything else that you can get done to improve the app functionality!
* [ ] Dynamic introduction string that uses the ternary operator to adjust grammar depending on the number of unfunded games.
* [ ] Numbers formatted using toLocaleString() for readability (e.g., 100000 → 100,000).
* [ ] Sorting of games by pledged amount to highlight top-funded games.
* [ ] Could implement search functionality or hover effects on game cards for visual improvements.

## Video Walkthrough

Here's a walkthrough of implemented features:

<img src='http://i.imgur.com/link/to/your/gif/file.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

<!-- Replace this with whatever GIF tool you used! -->
GIF created with ...  
<!-- Recommended tools:
[Kap](https://getkap.co/) for macOS
[ScreenToGif](https://www.screentogif.com/) for Windows
[peek](https://github.com/phw/peek) for Linux. -->

## Notes

- Keeping the DOM dynamically updated when filtering games. This required using a deleteChildElements() function to remove old game cards before adding new ones.
- Ensuring the stats section updates dynamically with correct formatting and grammar using reduce(), filter(), and ternary operators.
- Sorting games by pledged amount and grabbing the top two games using destructuring and the spread operator.
- Ensuring images display correctly from local assets (./assets/...) and match each game object.

## License

    Copyright [2026] [Kimberly Ticlavilca]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
