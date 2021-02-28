# Assignment 4: Information Architecture Definition

*Due: Friday, March 5, 2021*

NOTE: this is an *individual assignment* - you will work on this assignment by yourself and turn it in on Blackboard for your own grade.  In this case, collaboration would be considered plagiarism!

**The goal** of this assignment is to practice creating an **information architecture definition** based on a set of existing content; also, this assignment involves practice using the markdown style of document writing

**The purpose** of this assignment is to define an information architecture that you will use to create a website later (the website you create later will be your Project 1)

## Step 1: Review content

You need to have some content to look at when building an information architecture definition.  We will use our city websites from the previous assignments.   Don't belabor this step - you just need to **familiarize yourself with the full set of content** we've been using so far in DMS 290.

- Review all the individual cities in all the websites from Assignment 3 in [our shared City-Teams Google Sheet](https://docs.google.com/spreadsheets/d/17hWZWyvZobvzQhYiwNjiSP8E1cHAMDaDE1f0p8tx7zs/edit#gid=0) (click the links on Line 6)

- Look for content that looks consistent from city to city - not necessarily within the same website; look for similarities:

  - Do they have similar sections compared to other cities?  Notice the headings.
  - Do they have similar types of photos?  Notice the subject matter - skylines, neighborhoods, other subjects.  Also look at the sizes of the images, the dimensions and the quality of the images.  All that matters.  
  - Do they have paragraphs of text that seem to be written in a similar way compared to other cities - from both a quality and quantity standpoint?  Pay attention, not only writing style, but amount of text too.  Size (amount) matters!

  - Remember: you're looking at similarities in the CONTENT; obviously visual styles within a website will be similar *but forget about that for now*.  Style is not important for this assignment; stay focused on the content only and compare cities across websites; look for commonality.  

## Step 2: Define an Information Architecture

Remember: the purpose of this assignment is to **define an information architecture** which you will use to build a website LATER (when you work on Project 1).  For this step you only need to create a document using **GitHub Flavored Markdown (GFM)** - you're not actually building a website this time

- Create a plain text document named **assignment04.md**
  - Suggestion: find an editor that helps writing and formatting markdown; the professor uses Typora ([https://typora.io/](https://typora.io/)), but there are lots to choose from, including online editors (no software to install) ...just Google it
  - Suggestion: find a good editor?  Share it in our #chatter channel in Slack
- Format the document as you write, creating logical headings, paragraphs, lists, etc. 
  - Note: you'll get a grade on your ability to use markdown so do try to make it a nicely formatted document
  - At the top of the document you need to include regular pieces of meta information like your name, the date, the name of the assignment ...typical college-level elements for any assignment you need to turn-in for a grade
  - Spelling and grammar is also important although a mistake here and there won't be counted against you unless it's so bad that it makes the document difficult to read or understand

*The following is the hard part of this assignment: working alone you need to decide on a new information architecture for a website about several cities, and define it in terms of the three IA frameworks: ontology; taxonomy; and choreography*

### Define an Ontology

In your markdown document, create a heading (hint: "Ontology") and under it make a list of "triples"

Based on the collection of content we have in DMS 290 (our city websites)...

1. Identify your classes and create your **triples**

   - Hint: you're working with CITIES; they all have names, locations, and other typical pieces of information you'd usually associate with a city ...so make a list of these things; it doesn't have to be a long list
   - Don't forget non-text information; like photos - you decide what kind of photos a city should have
   - Create your triples; most of these will be simple like:<br>City has a name<br>City has a skyline photo<br>Country (or state, or province?) has a city<br>...stuff like that
   - Expand your triples to include anything you want.  Here are some examples (below) but please don't just use these examples - try to be original.  Also remember that ALL the cities that you use later in Project 1 will be based on the previous assignments we've done in DMS 290, so they must have the pieces of content you choose<br>City has an official flower<br>City has a major industry ...or is known for... (just be consistent)<br>City has a population (a number) ...or some other sets of data...<br>...BTW, you'll notice that just about all your triples will be centered around the "city", but that doesn't have to be so! Try to think of other classes to act as the *Subject*-side of each triple


### Define a Taxonomy

This next step *should be* relatively easy if you have a good ontology.  You just need to decide how to label everything consistently.

*Something to keep in mind: since we're building websites, that means that later, when you work on Project 1, you will use the taxonomy you created to build a  **document structure** and **document outline** using HTML tags.*

- In your markdown document, create another heading (hint: "Taxonomy") and under it make a multi-level list, i.e. bullets and indented bullets

  - ...like this...
    - ...et cetera

- Define the taxonomy that you'll use to structure your city content

  - Hint: for us web developers, this is easy!  Just think *document outline* written in heading tags (don't actually use heading tags now; just use bullet-points and indented bullets)

- The result: should be a hierarchical list of terms (words or short phrases) that represents the information from the ontology, example:

  - City Name

    - Silhouetted Skyline (a photo)

    - Local Customs

      - Yearly Events
      - Official Flower

    - Economy

      - Primary Export

        ...et cetera

  *Note: you do not have to follow your ontology exactly.  You can (and probably should) create new groupings of related topics as you see fit to create a deeper hierarchy*

### Define a Choreography

The order of things matters.  You need to decide.  Although you've kinda already decided the order of things when you created the taxonomy, you need to re-examine it, and make a few more decisions.

- In your markdown document, create another heading (hint: "Choreography")
- Describe (in words) the methodology for the order of the content you will use when you build your Project 1 website.  
  - Remember the LATCH framework (among others).  Although you have very little content to work with, how should any of it be grouped?  Location; Alphabet; Time; Category; Hierarchy ...or any other logical method that makes sense for your content.  Whatever you can come up with helps (and will be graded).
  - As you're working on the choreography, if you come up with something that makes sense but wasn't reflected in the hierarchy of the taxonomy, then go back to the taxonomy and add it or move things around accordingly.
- In addition to defining the order of the content for (what will be) each city, also describe in this section: the order of cities!  What city should be shown first?  Second?  Et cetera, ...and why.  

*Note: when deciding how the cities will be ordered, the worst/lamest but still valid reason can be "alphabetical" ...which is technically correct (and barely acceptable) but you can do better than that!*

## Step 3: Turn-in the Markdown Document

To get credit for your work:

- In Blackboard, upload the **assignment04.md** file into the **Assignment 4: Information Architecture Definition** assignment