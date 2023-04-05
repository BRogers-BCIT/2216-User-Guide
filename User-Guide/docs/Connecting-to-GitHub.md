# Connecting a GitHub account to your JetBrains IDE

## Overview

This part of the guide will walk you through how to connect your GitHub account to your JetBrains IDE.
This is necessary to implement the GitHub version control features mentioned in the other parts of the guide. Once your account is connected you will automatically connect to it for any future version control operations.  

* [**Pushing a project to a new GitHub repository**](Pushing-a-project-to-GitHub.md)
* [**Cloning a GitHub project to your IDE**](Connecting-to-GitHub.md)

### &emsp; Goals

By the end of this guide you will have connected your GitHub account to your local IDE. You should be able to find the account name, user name, and profile picture of the connected account within your IDE's settings.

### &emsp; Prerequisites

Prior to connecting your account to your JetBrains IDE you will need:  

* **A GitHub account**
* **A JetBrains IDE (Intellij, CLion, Pycharm, etc.)**

## Connecting to your GitHub account

### &emsp;Preparation

1. ℹ️ Open your chosen JetBrains IDE

    &emsp;&emsp;&emsp;![JetBrains](img/linking%201.png)

    !!! info

        &emsp;**You should now see the either project navigation screen, or your last open project.**

        &emsp;&emsp;![Project Selection](img/linking%202.png)

        &emsp;&emsp;![Open Project](img/linking%203.png)

        &emsp; **The following instructions will work from either of these locations.**

### &emsp;Navigate to version control settings

2. ℹ️ Press _**ctrl** + **alt** + **s**_  to open the settings menu of the IDE.

    ✅ You should now see the settings menu for the IDE.

    > > ![Settings menu](img/linking%204.png)

3. ℹ️ Click the version control tab on the left of the screen to open the version control settings options.

    &emsp;&emsp;&emsp;![Version Control Settings](img/linking%205.png)

    !!! warning

        &emsp;**If you cannot see the version control option, Type _“version control”_ in the search bar to limit the available options.**

        &emsp;&emsp;&emsp;![Search "Version Control"](img/linking%206.png)

    ✅ You should now see the options for the version control settings.

    ![Version Control Menu](img/linking%207.png)

### &emsp;Connect IDE to GitHub account

4. ℹ️ Click on the GitHub option

    &emsp;&emsp;&emsp;![Github Version Control Settings](img/linking%208.png)

    ✅ You should now see a menu containing any linked GitHub accounts and three buttons in the top left corner.

    ![GitHub Settings Menu](img/linking%209.png)

5. ℹ️ Click the plus button to link a new account.

    &emsp;&emsp;&emsp;![Add Account Button](img/linking%2010.png)

    ✅ You should see two connection choices : _“Log in via GitHub”_ or _“Log in with Token”_

    ![Log In Choices](img/linking%2010.5.png)

    !!!question "**Chose your preferred login option.**"

        * &emsp;**For _"Log in via GitHub"_ continue with [_Log in with GitHub_](#log-in-through-github)**

        &emsp;&emsp;&emsp;![Log In GitHub](img/linking%2011.png)

        * &emsp;**For _“Log in with Token”_ continue with [_Log in through a GitHub Token_](#log-in-through-a-github-token)**

        &emsp;&emsp;&emsp;![Log In Token](img/linking%2019.png)

### &emsp;Log in through GitHub

5. ℹ️ Click the "Log in via GitHub" button to link a new account.

    &emsp;&emsp;&emsp;![Log In GitHub](img/linking%2011.png)

    ✅ You should be taken to a JetBrains page and prompted to Authorize in GitHub.

    ![JetBrains Authorization Page](img/linking%2012.png)

6. ℹ️ Click the “Authorize in GitHub” button to continue.

    &emsp;&emsp;&emsp;![Authorize in GitHub](img/linking%2013.png)

    !!! info

        **If your GitHub account is already linked to JetBrains website you will be prompted to return to your IDE.**

        * &emsp;**If so, skip to step 4.**

    ✅ You should now see a GitHub login page.

    ![GitHub Log in](img/linking%2014.png)

7. ℹ️ Enter your GitHub log in and select Sign in.

    &emsp;&emsp;&emsp;![Sign in](img/linking%2015.png)

    ✅ You should be returned to a JetBrains page and promoted to return to your IDE

    ![Successful Sign in](img/linking%2016.png)

8. ℹ️ Return to your IDE and [**Confirm the account is connected**](#confirm-the-account-is-connected).

    &emsp;&emsp;&emsp;![Connected Account](img/linking%2017.png)

### &emsp;Log in through a GitHub token

9. ℹ️ If you already have a token and wish to log in that way, select the “Log in with Token” option.

    &emsp;&emsp;&emsp;![Log in with Token](img/linking%2019.png)

    ✅ You should now see the server set to “github.com” and the option to enter your token.

    ![Enter Token Field](img/linking%2020.png)

10. ℹ️ Enter your GitHub login token and select add account.

    &emsp;&emsp;&emsp;![Add Account Button](img/linking%2021.png)

### &emsp;Confirm the account is connected

11. ℹ️ Go to the GitHub section of version control menu.

    &emsp;&emsp;&emsp;![Connected Account](img/linking%2017.png)

    ✅ You should now see your GitHub account within the IDE’s Version Control > GitHub section.

    ![Connected Account](img/linking%2018.png)

    👍 Congratulations! Your GitHub is now linked to your JetBrains IDE.

### Success

Now that your GitHub account is connected to your JetBrains IDE you are ready to begin using distributed version control in all your new projects. Every iteration of your work can be stored safely off your computer on GitHubs servers.  
To continue getting started with GitHub check out one of the other guides:

* [**Pushing a project to a new GitHub repository**](Pushing-a-project-to-GitHub.md)
* [**Cloning a GitHub project to your IDE**](Cloning-a-GitHub-project.md)

### Troubleshooting

In the event that you encountered any difficulties when following our guide, the troubleshooting section of our guide contains explanations and solutions for common issues.

* [**Troubleshooting**](TroubleShooting.md)
