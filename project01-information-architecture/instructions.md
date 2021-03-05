# Project 1: Information Architected Website

*Due: Friday, March 12, 2021*

*Due: Friday, March 5, 2021 (fast track, extra credit)*

**NOTICE: regular track vs. "Fast Track"** For all students, Project 1 does *not need to be started* until next Friday, March 5 ...after Assignment 4 is completed.  But note that, both Assignment 4 and Project 1 *<u>can be</u> done as a single week-long activity* for students who have more programming and web development experience.  

- If you complete **Assignment 4** sometime this week - before Friday, March 5, and...
- You can find at two other team members, who have also completed Assignment 4 early, and...
- You feel you have the ability to finish **Project 1** BEFORE March 5 then...

...by all means, get an early start on it.  If you can do both Assignment 4 and Project 1 before March 5 then you'll get ***extra credit on Project 1***, and you'll be on your way to free-up time so you can join some technical workshops later in the semester.

<hr>

**The goal** of this project is to work as a team to pick an *information architecture definition* (from Assignment 4), implement it as a FOUR-page website (using content from Assignment 3), and then deploy it on UR Digital Scholar.

**The purpose** of this assignment is to demonstrate everything we've covered so far in DMS 290:

- Team collaboration using GitHub and Slack
- Website construction using an Information Architecture

## Step 1: Join a Team

- **Everyone:** go to [this shared Google Sheet](https://docs.google.com/spreadsheets/d/17hWZWyvZobvzQhYiwNjiSP8E1cHAMDaDE1f0p8tx7zs/edit#gid=0) and **copy** (not move) your name from Assignment 3 to a *new* city-team and choose a new role for yourself
  - Leave the city names (row 8) as-is; it's you who's moving!  Think of it like getting a new job in a new city.
  - It's suggested to take-on a new role and work with new people every time you move; you'll get more out of DMS 290 if you do, but it isn't required
  - Note: **Information Architecture is a big deal in Project 1** so everyone on the team will have to help out; whoever take the role of IA will, in effect, be the leader and need to coordinate with the team members to get the job done

- **Technician:** create a new *private* channel in Slack, and then invite the other members
- **Technician:** create a new *public* repository in GitHub for Project 1 
  - Add the other members as collaborators to the new repo
  - Make sure everyone on your team is setup and sync'd with the repo on GitHub

##Step 2: Flesh-out an Information Architecture in HTML

- **Everyone:** decide among your team members who's Information Architecture from Assignment 4 you will use for Project 1
  - You have to pick one from the three of you (you can't pick one from someone else in the class)
  - Assumptively you'll pick one that got a good grade; pick one that you feel you'll be able to implement based on the content available: individual webpages from Assignment 3

- **Information Architect (IA):** create an HTML scaffolding based on the Information Architecture
  
  - In a single HTML document, create a **document structure** and **document outline** using the appropriate HTML structure tags (MAIN, ARTICLEs, ASIDES, SECTIONS, etc.) and within the structure, create placeholders for the heading tags (H2s, H3s, etc.)
  - **THIS IS CRITICAL: do not build the structure and outline arbitrarily!**  Follow the Information Architecture definition that the team picked!  The result must clearly demonstrate the intent of the **ontology**, **taxonomy**, and **choreography**.
  - Note: you only have to represent the *intent* of the architecture; you do not have to follow it exactly. For instance, if the architecture specifies there be a section called "History", you don't necessarily have to create `<h2>History</h2>` in the HTML.  You have some artistic license - maybe change it to `<h2>Early Days in ...</h2>` ...but whatever you do for one city, you have to be consistent across ALL the cities
- **Information Architect (IA):** working with your team, flesh-out the content of the website

  *The following is a lot of work; get your team members to help; if they don't help, make a note of it;  and if you think it might negatively impact your grade, let the professor know privately*

  - Make three copies of the original HTML scaffolding; you'll end-up with four webpages - one for each of the four cities you'll pick
  - Direct the team to the Assignment 3 webpages to get content and restructure it into the HTML documents

  NOTE: obviously the content you gather from the Assignment 3 webpages won't fit into your document structure without considerable alterations.  That's the challenge of this project.  Just remember: YOU OWN THIS CONTENT!  

  - You can **cut** it, **add** to it, **edit** it - whatever it takes - to make the content fit within the architecture
  - Just make sure that, at the end of this project, all the content makes sense ...no placeholders, gibberish, or sections that don't logically flow from one to another.  I.e. all the content has to look and read like a normal website about four cities.
  - If you need to go out to the web and get more/different text content and images (most likely), then do so.  Just remember where you got it from and add it to the list of sources.

### Hints & Tips

- Reminder: the goal here is to have four perfectly aligned webpages that all have the same flow, not only top-to-bottom, but have identical structure and outline from page-to-page
- Make sure the content within sections are more-or-less the same length too!  It would be incorrect to have a very long, detailed section, say "History" on one city's page, and on another page it's very short.  They need to be balanced among all the pages.  That includes data tables too.  If one city has a table, then they all need to have the same kind of table, in the same place with about the same amount of data.
- Make sure the images are also similar in both size/dimensions, but also in terms of their content/subject matter.  (It's okay to tweak, including crop the image files.  You OWN the content - do whatever you need to do.)

#### Regarding a Homepage and Navigation

- NOTICE this website will *not* have a homepage (index); we'll create that in a later project.  However there needs to be an identical navigation element on each of the four city webpages, and there needs to be an order to the links, based on whatever was decided in the defined choreography of the architecture.  Make sure the navigation reflects the correct order.

## Step 3: Add Styles to the Website

As we haven't covered website design in DMS 290 yet, the bar is still low in terms of the use of CSS.  Still though, it is required that the website is readable and legible.

- **The Visual Designer** is required to implement a design on the four page website using CSS (JavaScript optional)
- **The Visual Designer** may re-purpose existing CSS from any of the Assignment 3 websites, and/or write their own
- Whatever is implemented, the design must be consistent from page-to-page and follow subjectively reasonable design standards commonly seen on websites these days
- **EXTRA CREDIT (20 points)** will be assigned to the Visual Designer for exceptional design and use of CSS

## Step 4: Deploy the Website

**Technician:** note that the use of PHP includes or a JavaScript-powered current page highlighter is NOT required for this assignment, but if your team is okay with it the feel free to use those things

- The **Technician** is required to make sure all the code (HTML, CSS, and optionally PHP and/or JavaScript) is coded correctly, works correctly and meets *most* industry standards and best practices *within reason*
  - Although the professor will check both the HTML and CSS against the W3C validators, only really, *really* sloppy code with mistakes that cause the website to not render correctly will lose points; other than that, the bar is (still) very low in DMS 290 from a technical standpoint

- **EXTRA CREDIT (20 points)** will be assigned to the Technician for full HTML/CSS validation, use of PHP Includes, and a properly working *current page highlighter*

- **Technician**: install the website on UR Digital Scholar in a folder named **project01**

## Step 5: Turn-in the Project for Credit

NOTE: unlike Assignment 3, **everyone** needs to create a submission in Blackboard

- **Everyone:** in Blackboard, in the **Assignments/Projects Turn-in** area, in **Project 1: Information Architected Website**, write in the **Write Submission** area (*not* the comments box):
  - **Your city-team name**
  - A list of **everyone's name** in your team (including your own) and the **role everyone performed** in this project: IA, Designer; or Technician
  - A **link to your team's website** on the class web server
  - A **link to your team's repository** (which should be set to public)
  - Optional: in your submission in Blackboard, you can report any concerns you had about the development work, how things turned-out, or everyone's contribution to the project; whatever you write will be private and the professor won't take any action on it without discussing it with you first