# Cohort 4, Week 3

## Contents <!-- omit in toc -->

- [Theme: Prep For Capstone](#Theme-Prep-For-Capstone)
- [Practice Opportunities](#Practice-Opportunities)
  - [Programming Fundamentals via JavaScript](#Programming-Fundamentals-via-JavaScript)
  - [Command-Line Projects](#Command-Line-Projects)
  - [Web Applications](#Web-Applications)

## Theme: Prep For Capstone

Next week is entirely about the capstone project. We want to maximize everyone's chance of success.

Right now there are a few hurdles to building what you want:

1. Persisting user-supplied information between page views and visitors, e.g.,
   - Keeping track of which user performed which action(s)
   - User #453 uploads a photo and every other user can see it
   - If User #72 liked Post #98, show Icon #10, otherwise show Icon #8.
   - etc.
1. Finding, fetching, and interacting with data from external services and websites
   - User enters a few genre preferences and we generate a list of songs on Spotify for them to play
   - Pull data from the Animal Crossing Wiki to make a birthday-matching website
   - etc.
1. More interactive browser experiences
   - Games
   - Data visualizations and graphing libraries
   - etc.

The deeper your understanding of JavaScript and programming fundamentals the more straightforward learning all of the above will be.

Since we only have one week, it's not feasible to dive deep on all of these.

## Practice Opportunities

### Programming Fundamentals via JavaScript

1. Do the exercises in [Basic Syntax][curriculum-basic-syntax] even if you have prior experience. You don't have to do *all* of them, but you should do 4-5 at least. Once you get the rules down, each one should only take a few minutes.
1. Skim through the [JavaScript Crash Course][curriculum-intro] to build familiarity with the concepts involved. **Do not** try to read it line-by-line and understand everything up front. It won't work and you'll get frustrated.
1. Start on the [JavaScript Fundamentals][curriculum-fundamentals]

   You'll be tempted to do all the exercises from start to finished as they're organized. That is a mistake. Each section is related to a particular concept. It's better to do try the first 3-4 in each section. If it takes more than 30-40 minutes to make forward progress on an exercise, try another one.

   We recommend the following process:

   1. Pick an exercise
   1. If you're stuck, refer back to the related section(s) in the [JavaScript Crash Course][curriculum-intro]
   1. Re-read the related section(s) for examples and clarification on the underlying concepts
   1. You probably re-read the related section(s) too quickly. Go sentence by sentence this time, no skimming. Read the examples. Read the explanations of what the examples are.
   1. Make sure you can do the problem "by hand" (i.e., without code) using pen, paper, index cards, sticky notes, or whatever else. Get your head out of the syntax.
   1. Try the exercise again

### Command-Line Projects

Make use of the [JavaScript Examples][examples-javascript].

1. [Text Analysis][curriculum-textalyze] — Good first project. Prints out statistics about the letters in a text file, but can be adapted to calculate + display other statistics.
1. [Static Photo Gallery][curriculum-static-photo-gallery] — Rather than writing HTML by hand, write a program to write it for you! You give this program the name of a directory containing multiple images and it produces an HTML photo gallery containing those images (ready to deploy to surge)

### Web Applications

1. [Express Sandbox][curriculum-express-sandbox] — Explore the difference between a statically-generated web page and a dynamically-generated web page
1. [Social Wall][curriculum-social-wall] — A fully-featured but simple web application. This contains 90% of the concepts you'll need to build any web application.

[curriculum-basic-syntax]: https://github.com/jfarmer/exercises-js-basic-syntax
[curriculum-intro]: https://github.com/jfarmer/intro-javascript
[curriculum-fundamentals]: https://github.com/jfarmer/exercises-js-fundamentals
[curriculum-textalyze]: https://github.com/jfarmer/project-js-textalyze
[curriculum-static-photo-gallery]: https://github.com/jfarmer/project-js-static-photo-gallery
[examples-javascript]: https://github.com/jfarmer/examples-javascript
[curriculum-express-sandbox]: https://github.com/jfarmer/exercises-js-express-sandbox
[curriculum-social-wall]: https://github.com/jfarmer/project-js-social-wall
[curriculum-sql-queries]: https://github.com/jfarmer/sql-queries
