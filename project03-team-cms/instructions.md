# Project 3: Team Content Management System

*Due: Friday, April 16, 2021 ...plus extra time if you need it, within reason*

**The goal** of this project is to work as a team to create and publish a WordPress website with lots of content and features.

**The purpose** of this assignment is to develop experience working on a content management system in a team of web developers.

## Step 1: Join a Team

The focus of Project 3 is equally distributed among all three roles: Information Architect; Visual Designer; and Technician

- **Everyone:** go to [our shared **DMS 290 City-Teams** Google Sheet](https://docs.google.com/spreadsheets/d/17hWZWyvZobvzQhYiwNjiSP8E1cHAMDaDE1f0p8tx7zs/edit#gid=0) and **copy** (not move) your name from "Project 2" to a *new* city-team and choose a new role for yourself
  - Leave the city names (row 21) as-is: "tbd" (stands for "to be determined")
  - Note: it's suggested to take-on a new role compared to Projects 1 and 2, and work with new people; you'll get more out of DMS 290 if you do, but it isn't required

- **Technician:** create a new *private* channel in Slack, and then invite the other members
  - Note: you'll need a temporary name for your private channel; you'll have a permanent city-name later in the process and you can change your private channel's name at that time
  - Also note: no GitHub repository needed for this project
    - Although it's typical in the industry to have everyone in the team build their own local copy of the CMS (files *and* database!) using their own *localhost*, and then sync their work with the team using GitHub, that's a level of complexity we don't need in DMS 290
    - So for this project, we'll all be working directly on the class web server (UR Digital Scholar).  It's a little slower - a little more clunky - but the website you'll be building is not big enough to justify the time that it would take to set all that up

## Step 2: Create a New Instance of WordPress

- **Technician:** in your UR Digital Scholar account, setup a new WordPress website

  - Use the location: **project03**
  - Set the Administrator Username: **dms290**
  - Set the Administrator Password: **coffee1N**

  ...Important! Setting the Administrator Username and Password exactly like this is required so your Project can be graded

- **Technician:** in the new Project 3 WordPress website, in the *Dashboard*, go to the **Users** area and add your team members as New Users
  - Set their **Role** as *Administrator*
  - Make sure everyone on your team is able to access and login to your new WordPress website

## Step 3: Choose a Project 2 Website

- **Everyone:** referring to [our shared **DMS 290 City-Teams** Google Sheet](https://docs.google.com/spreadsheets/d/17hWZWyvZobvzQhYiwNjiSP8E1cHAMDaDE1f0p8tx7zs/edit#gid=0), you'll need to decide among your team members which Project 2 website you'd like to COPY as a basis for your Project 3
  - It's okay to pick a website on which you worked before
  - IMPORTANT: just like before, each Project 2 website can be selected by only one team - so it's **first-come, first-serve**!
  - **Follow the instructions below** to see how to "squat" on a Project 2 website and claim it for your team...

*When your team is ready to make a Project 2 selection:*

- The Project 2 website information must *not* be RED - which would indicate another team has already selected it
- Change your team's name (row 22) from "tbd" to the city-name of whichever Project 2 website you're selecting
- Change the *background color* of the Project 2 team information (rows 15-20) to RED to indicate to other teams that that Project 2 has been selected and no one else can choose it

- **Technician:** change the name of your private Slack channel to the name of your new city-team.

## Step 4: Customize the Website Settings

- **Technician:** in the Project 3 WordPress website, in the *Dashboard*, go to the **Settings** area and in **General**, change the *Site Title* and *Tagline* to something appropriate based on the Project 2 content that the team selected

*Note: the following requirements assume you are familiar with the basic operations of WordPress based on your experience from Assignment 8 and the CMS-related videos in Panopto*

- **Technician:** create and *Publish* a new **Page** - call it "Home"
- **Technician:** create and *Publish* another new **Page** - call it "Travel Blog"
- **Technician:** back in the **Settings** area, in the **Reading** section, set *Your homepage displays* to "A static page (select below)", and...
  - Set *Homepage* to "Home"
  - Set *Posts page* to "Travel Blog"
- **Technician:** on the *front-end* of the website, make sure a navigation system (menu) exists to allow the user to navigate to and from the homepage and the Travel Blog; if not, you need to create it
  - Also, as the rest of the website is constructed, it'll be the Technician's responsibility to make sure that each "Page" appears in the navigation system
  - Hint: under **Appearance**, you'll need to *Create* a menu then *Add menu items* (click View All and read the screens carefully)

## Step 5: Build the Website

*Note: the following requirements do not have to be done in order; actually, the point of a CMS like WordPress is that multiple people can work on setting-up different parts simultaneously*

- **Information Architect:** create new "Pages" and install the content from your Project 2 website
  - Hint: focus on the city pages only at first - not the homepage at first because that'll change a lot when the Technician installs some plugins; and don't worry about the "Travel Blog" yet either
  - Hint: do not try to format the content at this point; the Visual Designer will be applying a "Theme" which may change or interfere with manual styling
- **Visual Designer:** find and install a suitable Theme for the website - something that will support the type of content in the website
  - Note: the Visual Designer will also need to go into each Page and manually style the content using the design tools provided by WordPress
- **Technician:** if the Theme selected by the Visual Designer doesn't already come with a homepage slideshow (sometimes called a Gallery; sometimes called a Jumbotron), then find an install a suitable Plugin that'll provide that functionality
  - Note: although the IA will provide content for the slideshow, it is the Technician's responsibility to learn how to use the slideshow and install the content so it works and displays correctly

*Note: the following list of requirements describe what needs to be the RESULT of your team's work.  It's expected that each team member will focus on the work that's associated with their own role, with help from the other team members as needed*

### Website Requirements

Your team's website will be graded against the following requirements

- The homepage of the website must host an **auto-playing slideshow** that shows appropriate images for the website
- The presentation of the homepage must ***approximate* a Z-pattern**
  - The z-ness of the design will be dependent on the types of Themes that are available, so when graded, there will be a lot of "flexibility" in terms of how well the webpage follows the Gutenberg Rule
  - Bottom line: just try! ...but if it's not a perfect Z, you won't lose points for it
- There must be **four content sub-pages** - one for each city from Project 2
  - It would be great if the design of the sub-pages followed an F-pattern, but most likely you won't find a Theme that supports it
  - Still though, if you find one and use it correctly that'd be great!  Else, do what you can to format the content into an F-pattern using the design tools provided by WordPress
  - If it's too hard to force the content into an F-pattern, or if it doesn't look right - forget about it.  It's more important that that content looks subjectively well than to force it into an F ...but do try!
- The Blog page of the website must host **a number of blog posts** (three or four, written by the team) and comments must be enabled
  - The requirement is to make the Posts and Comments section look a little *lived in*, so we have something to look at
- The **navigation system** must exist and it must allow users to go from page to page (as one would expect)

### Other Notes About Roles and Responsibilities

- The **Information Architect** is responsible for gathering and installing content, which may include finding or creating NEW content; e.g. if more images are needed for the slideshow, the IA needs to obtain those images (and the Technician will install them)
- **Visual Designer:** in addition to finding an installing a suitable Theme, the Designer needs to work with the content (as provided by the IA) and make sure it displays correctly/normally, and to the degree possible, format it into the appropriate Z- and F-patterns where applicable
  - Also note, in addition to page layout principles the Visual Designer must consider the other principles of page design too: C.R.A.P.; and typography ...although the bar is fairly low for DMS 290,  objectively bad choices and blatant disregard for the design principles we've learned this semester will result in a low grade

## Step 6: EVERYONE - Turn-in the Project for Credit

NOTE: just like with Projects 1 and 2, **everyone** needs to create a submission in Blackboard

- **Everyone:** in Blackboard, in the **Assignments/Projects Turn-in** area, in **Project 3: Team Content Management System**, write in the **Write Submission** area (*not* the comments box):
  - **Your city-team name**
  - A list of **everyone's name** in your team (including your own) and the **role everyone performed** in this project: IA, Designer; or Technician
  - A **link to your team's website** on the class web server

*Optional: since everyone is reporting in Blackboard individually, in your submission in Blackboard, you can report any concerns you had about the development work, how things turned-out, or everyone's contribution to the project; whatever you write will be private and the professor won't take any action on it without discussing it with you first*