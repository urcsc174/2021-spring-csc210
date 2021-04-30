# Project 4b: Customized Website with a CSS Framework (Website Construction)

Continuing on from [Part 1: Project Plan](../project04a-customized-website-with-a-css-framework/instructions.md)

*Part 0 "Setup" due: Wednesday, April 28*

*Part 1 "Project Plan" due: Friday, April 30*

*Part 2 "Website Construction" due: Friday, May 7 (last day of classes*)

## Part 2: Website Construction

*Part 2 due: Friday, May 7*

For this part of the project, you will work with your teammate using the GitHub repository created in Part 1.

- Note: you will be graded on the quantity and type of commits you make to the repository!

## Step 1: Content

This step must be lead by the Information Architect, however it's assumed that the Visual Designer will be involved because it's a lot of work.  

Regardless of who does what, remember: after each activity (which is whatever you decide it is), stop! and create a GitHub commit to document what you did and then push it to the repository.

***Procedure***

- **Technician:** (anyone) Create a **readme.md** file that will reside in your GitHub repository
  - At the top of the readme, add basic website information: typical things like your names, roles, a description of the website
  - Note: the readme file (as well as any other markdown files) is not actually part of the website so when you install it on UR Digital Scholar, make sure it does *not* end up on the web server
- **Information Architect (IA):** create an HTML **scaffolding** (a single HTML file) based on the Information Architecture from Part 1 (your Project Plan)
  - In HTML, using your Information Architecture as a guide, create a **document structure** and **document outline** using the appropriate HTML structure tags (MAIN, ARTICLEs, ASIDES, SECTIONS, etc.) and within the structure, create placeholders for the heading tags (H2s, H3s, etc.)
  - **THIS IS CRITICAL: do not build the structure and outline arbitrarily!**  Follow the Information Architecture definition that you wrote!  The result must clearly demonstrate the intent of the **ontology**, **taxonomy**, and **choreography**.
  - Note: you can deviate from the architecture you defined in Part 1, but if you do explain the changes in the **readme.md** file
  - Remember: in this first step you're just creating one HTML file with only a structure - no real content yet.  
  - Regarding: *how many webpages do you need to build-out?*<br>How you build your website - one long scrolly page, or multiple pages - is up to you.  You're the architect - it's your decision.  Just make sure whatever you decide makes sense for the content you're presenting.  (Hint: generally, repeating content structure suggests multiple webpages with similar document structure)

- **Information Architect (IA):** working with your teammate, flesh-out the content of the website

  - Make copies of the original HTML scaffolding - as many as you'll need for your architecture

  *Note: following is a lot of work; get your teammate to help. The commits in your GitHub repository will indicate the level of work each teammate provided.*

  - Direct your teammate to help you get content and feed it into the HTML documents


### Hints & Tips

- Reminder: the goal here is to have perfectly aligned webpages that all have the same flow, not only top-to-bottom, but have identical structure and outline from page-to-page
- Make sure the content within sections are more-or-less the same length too!  It would be incorrect to have a very long, detailed section on one page, and on another similar page, it's very short.  They need to be balanced among all the pages.  That includes data tables too.  If one has a data table, then they all need to have the same kind of table, in the same place with about the same amount of data.
- Make sure the images are also similar in both size/dimensions, but also in terms of their content/subject matter.

#### Regarding a Homepage and Navigation

- NOTICE this website will need a homepage (index); typically, the homepage is not part of the defined architecture - it's usually a visual, attention grabbing introduction (hint: z-pattern, maybe with a JS-powered slide show!  And/or maybe "wells" to lead the user into the rest of the website)
- And of course the website will need a persistent menu on each page; it will need to follow typical navigation conventions that you're familiar with

## Step 2: Visual Design

This step must be lead by the Visual Designer, however it's assumed that the Information Architect will be involved because it's a lot of work.  

Regardless of who does what, remember: after each activity (which is whatever you decide it is), stop! and create a GitHub commit to document what you did and then push it to the repository.

This step must be done in two sections: 

1. **Use Bootstrap first** - to add basic styles for layout, embellishments, and automatic styling of the most common website elements (this is why Bootstrap exists), then...
2. **Customize the visual design** by adding your own styles to supplement or *override* the Bootstrap styles so your website doesn't look like every other Bootstrap website

***Procedure***

- **Technician:** (anyone) install Bootstrap into the website (every page); both the CSS and the "Bundle" JavaScript plug-in

*Note: following is a lot of work; get your teammate to help. The commits in your GitHub repository will indicate the level of work each teammate provided.*

- **Visual Designer:** using your planning documents (sketches, wireframes, swatches, etc.) apply BOOTSTRAP STYLES to the content by editing the HTML only
  - Direct your teammate to help you apply Bootstrap classes to the content
  - The goal is to have Bootstrap do the work of styling the website according to your visual design plan as much as possible

Also note: the amount of Bootstrap styling you need to apply is not defined here in Project 4 because it will vary based on your visual design plan.  But generally, the professor will be looking for these typical uses of Bootstrap:

- The **heading** and **navigation** (what the professor usually refers to as "top part") should be laid-out and powered by Bootstrap
- The **overall page layout** - alignment of side-by-side elements etc. - should be laid-out by Bootstrap
- **Common containers** like: tables, lists, image containers (if used), etc., should be formatted by Bootstrap
- Optional: **JS-powered interactive elements** - like a slideshow on the homepage may be powered by Bootstrap

Not everything listed here^ needs to be powered by Bootstrap, but there should be an attempt to use it extensively.  (That's the reason Bootstrap exists: to do the basic stuff so you don't have to write the CSS yourself.)

***Next, customize the visual design***

- **Technician:** (anyone) create two CSS files in the website file system

  - **styles.css**
  - **override.css**

  ...and install them in the appropriate places in the code on every page

*Here too: the following is a lot of work; get your teammate to help. The commits in your GitHub repository will indicate the level of work each teammate provided.*

- Using your visual design planning document as a guide, add styles and/or override the Bootstrap styles to implement the design by writing CSS in the **styles.css** file, or as needed, in the **override.css** file

- Regarding: *how many alterations to the Bootstrap styles do you need to write?*<br>Keep in mind that your final website appearance will be measured against your visual design plan from Part 1 of this project.  So in effect, whatever Bootstrap doesn't do, you have to do, so the end result looks like what you planned.

Note: you can deviate from the design you defined in Part 1, but if you do explain the changes in the **readme.md** file

### Hints & Tips

- Reminder: the goal here is to have a website that does *not* just look like Bootstrap.  (The title of this project is: "Customized Website" ...meaning it does not look generic!)
- Bootstrap elements typically use bland/neutral colors.  That's on purpose because it's assumed that you will OVERRIDE and apply your own color pallet to those elements.  (Make it so!)
- When applying styles to webpages, it's every web designer's goal to *not* alter the structure of the content.  However, sometimes you have to do that to make things work - especially when working with a CSS Framework.  Go ahead and do so - with the Information Architect's approval - but try to keep it at a minimum.

#### Regarding the Homepage and Navigation

- If you did not plan a **homepage** in your visual design plan, it's okay to *wing it*, so long as the end result follows the *look & feel* of the rest of the website
- Regarding the **website navigation**, Bootstrap has a certain look & feel to it that you probably didn't incorporate into your visual design plan; that's okay.  You can go with Bootstrap's navigation style even if it's a lot different than what you had planned so long as you make note of the change in the **readme.md** file

## Step 3: Install the Updated Website and Turn It In

This is a little different than what we've been doing in DMS 290 previously...

- BOTH team members need to install the website on their own DR Digital Scholar account
  - Yes - they will be duplicates of each other
  - The intent here is to test everyone's ability to do so

To get credit for your work...

- FTP the updated website to a folder on your UR Digital Scholar account in a folder named **project04**
- In Blackboard, provide links to both your repo in GitHub and the Project 4 website on your UR Digital Scholar account