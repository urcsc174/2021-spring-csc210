# Assignment 3: Collaboration

*Due: Friday, February 26, 2021*

**The goal** of this assignment is to get up-and-running with GitHub quickly and **experiment with collaborating** on a simple website to see how it works.

**The purpose** of this assignment is to demonstrate how working with a team of web developers is better than working alone using these common industry tools:

- <s>**Localhost** - to work independently</s> *...optional for Assignment 3*
- **GitHub** - to sync your independent work with the rest of the team
- **Slack** - to communicate with each other remotely and asynchronously

## Step 1: Join a Team

- **Everyone:** go to [this shared Google Sheet](https://docs.google.com/spreadsheets/d/17hWZWyvZobvzQhYiwNjiSP8E1cHAMDaDE1f0p8tx7zs/edit#gid=0) and **move** (cut & paste, or drag) your name from the "Pick list" to any "City-team" and choose a role for yourself
  - At the end of this exercise, at the very least each team must have two members (no teams of one!) and someone must take the role of Technician
  - Note: not everyone will be able to get what they want; good luck!
- **Technician:** create a *private* channel in Slack, and then invite the other members
  - You will use your private channel to coordinate with the other team members
  - This will be a temporary channel that you can delete after this assignment is complete
- **Technician:** amongst your team, decide on the name of a city somewhere in the world, and back in the Google Sheet, change your city-team name (column header) from **Team #** to your city's name

## Step 2: Set-up a GitHub repository

- **Everyone:** In your team's private channel in Slack, share your GitHub user names with each other
- **Technician:** create a new GitHub repository for Assignment 3; IMPORTANT: make it "Public"
- **Technician:** in the new repository go into **Settings** and then **Manage access** and then click the **Invite a collaborator** button, and then invite the other members of your team

## Step 3: Setup GitHub Desktop

Note: use of a WAMP or MAMP stack is not required for this assignment, but you can decide as a team - if everyone is comfortable with it - to use it or not.  

- Use the desktop software to **Clone a repository** 
  - In the **Clone a Repository** dialog box, select the new repository from GitHub.com
  - BE CAREFUL HERE: don't click the Clone button too quickly!  Read the next step...
- In the **Clone a Repository** dialog box, *change* the **Local Path** to a location on your own computer where you want to put it
  - You can change the name of the folder (the end of the path) to whatever you want (e.g. assignment03)
  - If you're using a stack like WAMP or MAMP, save the folder in the document root (a.k.a. web root) of your localhost, e.g. **.../www/assignment03**

## Step 4: Build a Website together

The intent here is for your team to take ANY FOUR **Assignment 2** website files from Columns H and I in the [DMS 290 Assignment 2: GitHub (Google Sheet)](https://docs.google.com/spreadsheets/d/1rAZzYDRKwMR2A0Kp43eG-GwvD_hC88srLtbNwXHsvtM/edit#gid=0), and cobble them together into a cohesive website that meets the following requirements

### Requirements

- The website must have FOUR web pages, each with information about a city (one city per page)

- There must be a new homepage (a file named index.html) that acts an entry point to the four city pages

- There must be an identical navigation element on each page that allows the user to navigate to each of the five pages

- The repository used by the team for collaboration must be full of meaningful commits from all members of the entire team

- The website must be hosted on UR Digital Scholar without major, glaring mistakes

  - The website must be located in a folder name **assignment03** on the Technician's UR Digital Scholar account

  - The navigation system must work as expected

  - There must be no broken images or links, etc.

    ...note: other quality standards from CSC 170, like HTML and CSS validation, would be nice but not required for this assignment

### Suggested Steps

    1. Technician: repo; slack channel
    2. IA: HTML scaffolding (placeholders)
    3. Visual Designer: Layout (CSS)
    4. Everyone - make decisions and build-out the site; comment, commit, and sync often
    5. Technician: check, fix, and host

### Hints & Tips

- **Information Architect (IA):** After the team picks four websites by looking at them from Column H in the Google Sheet, go to their associated repositories (Column I), and then in GitHub click the green Code button to download the ZIP files, one at a time (you don't have to Fork these repositories)
  - Note: do NOT put the four websites into your web root for Assignment 3, nor share them in GitHub!  They are not part of the new website.  Keep them separate on your own computer.
- **Information Architect (IA):** based on however you want to build-out the new Assignment 3 website, quickly create an HTML "scaffolding" - just the HTML tags with some placeholder content and FPO images at first, and sync the four webpages plus the new index page (five HTML documents) to the team's repository - this will give the Visual Designer and Technician the ability to start their work
  - Suggestion: typically, the "content" pages (the city pages) have the same HTML structure, so create one HTML document first to represent one city.  That will be your template that you will use to make three copies - one for each city.  Separately, create the homepage which can have a different structure than the content pages.
- **Visual Designer:** start building the CSS to apply to the entire website
  - Suggestion: start with the page layout for the four content pages first; embellish with fonts, colors, backgrounds, etc. later.  Layout and style the homepage separately.
  - If you can't figure out how to layout or style anything you have in mind, ask for help in our Slack #help channel!
- **Information Architect (IA):** as you replace your placeholders with real content, note that you do NOT have to use all the content! It's more important that you fashion the content to be balanced across the four webpages by editing (moving around, deleting, and even adding!) content as you see fit to make a cohesive, sensible web experience
  - Suggestion: work on fleshing-out the four content pages first; the index page last
- **Technician:** note that the use of PHP includes or a JavaScript-powered current page highlighter is NOT required for this assignment, but if your team is okay with it the feel free to use those things
  - Note: if you're going to frack your website into multiple PHP Includes, ask the professor for hints & tips on how to do that while collaborating.  There's a trick to it!  If you do it wrong the repository might turn into a mess.

## Submit the Lab

To get credit for your work:

- **Technician:** submit a link to your website in Blackboard, in: **Assignment 3: Collaboration**
- Along with your link write in the **Write Submission** area (*not* the comments box):
  - **Your city-team name**
  - A list of **everyone's name** in your team (including your own)
  - A **link to your team's website** on the class web server
  - A **link to your team's repository** (which should be set to public)

