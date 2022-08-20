
Social Network API
=========================

By Edgardo Lopez
-------------------------
## Table of Contents
==============================
*   [The Purpose](#the-purpose)
*   [Critera](#criteria)
*   [Installation](#installation)
*   [Usage](#usage)
*   [The Process](#the-process)
*   [What Was Done Differently](#differently)
*   [Built With](#built-with)
*   [Contributing](#contributing)
*   [Project Status](#project-status)
*   [Disclaimer](#disclaimer)
*   [Website](#website)
==============================

#   [The Purpose](#the-purpose)

To be able to apply the budget spent or saved and reflecting it on the graph itself for a visual update on one's status.  This also needs to be available offline and it'll update if it is offline.

#   [Critera](#criteria)

User Story
AS AN avid traveler
I WANT to be able to track my withdrawals and deposits with or without a data/internet connection
SO THAT my account balance is accurate when I am traveling 

Acceptance Criteria
GIVEN a budget tracker without an internet connection
WHEN the user inputs an expense or deposit
THEN they will receive a notification that they have added an expense or deposit
WHEN the user reestablishes an internet connection
THEN the deposits or expenses added while they were offline are added to their transaction history and their totals are updated

#   [Installation](#installation)

Head on over to the GitHub:

When you have a folder location, issue the command:  

```bash
git clone {link of the project}
```
Remember to use a program such as Powershell and have a program like Visual Studio Code to be able to open and edit the project.

#   [Usage](#usage)

For this, once you have cloned the folder, issue the command:
```
npm run start
```
This will then cause the program to deploy and you'll be able to see the site itself.  IN it, it'll consist the name of the budget, how much it was spent or saved, and an apply so that it'll be then transferred over to the chart itself.  You'll also need to save up on the cache using the tool that it is used when you hit "inspect" (Google Chrome).  It'll then store the information and as well as the icons/design when you are offline.

#   [The Process](#the-process)

This was more in inspecting the code that was given to us.  One of the few things that was also added was the "manifest.json" that has the information of the icons, theme color, background, start url (which is index.html), and the display.  In addition to this, we had a function with the const of "FILES_TO_CACHE" where that said information was stored in a cache so it'll be available online.  What was needed is to make sure that the files/routes match to what we need to save.  Then there are eventlisteners waiting for this information to be read while it is offline.

#  [What Was Done Differently](#differently)

Uploading it from Heroku/Atlas.  Thanks to the guidance, I was able to get it working right away.

Nothing else has been done differently outside of the last project.

#   [Built With](#built-with)

    *HTML
    *CSS

#  [Contributing](#contributing)
Made with ❤️ by [Edgardo Lopez]

#  [Project Status](#project-status)

As stated on the "What Was Done Differently", there are portions of the file that have been changed since assigned.  As I continue to grow as a developer, I'll be inputing additional of my work from GitHub on the portfolio as well as reconstructing the layout of the page (such as the previous change when using Grid instead of Flex).  Keep an eye out for any updates on the portfolio itself!

#  [Disclaimer](#disclaimer)

The project is open for anyone to use.  As stated on the purpose, it's to help out those that are starting in making a portfolio of their own.

#   [Website](#website)

https://budget-tracker-elopez08.herokuapp.com/
