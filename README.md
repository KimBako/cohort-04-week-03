# Cohort 4, Week 3

## Contents <!-- omit in toc -->

- [Blah Blah Just Tell Me What To Do](#Blah-Blah-Just-Tell-Me-What-To-Do)
- [Theme: Prep For Capstone](#Theme-Prep-For-Capstone)
  - [Removing Roadblocks](#Removing-Roadblocks)
- [Practice Opportunities — Back-End & Front-End](#Practice-Opportunities--Back-End--Front-End)
  - [Programming Fundamentals via JavaScript](#Programming-Fundamentals-via-JavaScript)
- [Practice Opportunities — Front-End](#Practice-Opportunities--Front-End)
- [Practice Opportunities — Back-End](#Practice-Opportunities--Back-End)
  - [Command-Line Projects](#Command-Line-Projects)
  - [Web Applications](#Web-Applications)

## Blah Blah Just Tell Me What To Do

By Thursday morning...

Read:

1. [Git Instructions][git-instructions]

Do:

1. [Git Pull Request Exercise][curriculum-pull-request]

Do:

1. [JavaScript Crash Course][curriculum-intro]
1. [JavaScript Fundamentals][curriculum-fundamentals]

Then:

1. [Express Sandbox][curriculum-express-sandbox]

If you want feedback, submit a pull request and tag an instructor. If you don't know what that sentence means then ask.

## Theme: Prep For Capstone

Next week is entirely about the capstone project. We want to maximize everyone's chance of success.

There are two "tracks" to web development: front-end and back-end.

Front-end is all the HTML and CSS. It's what the user sees. User interface design, user experience, graphic design, typography, etc. all play the biggest roles there. It's mostly about getting HTML/CSS to create the designs you want and adding what JavaScript you need to make it interactive.

Back-end is something we haven't talked much about, but this is how we create webpages that contain user-supplied data. The back-end is a program — written in any programming language, including JavaScript — which generates HTML documents populated by data from some kind of database. When a user clicks a link, submits a form, etc. the back-end can store that information in a way that makes it available between visits to the same page.

We use Node to run JavaScript outside of the browser and power the back-end. You should decide now which aspect you'd like to focus on during your capstone.

### Removing Roadblocks

Right now there are a few roadblocks to building what you want:

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

Since we only have one week, it's not feasible to dive deep on all of these.

## Practice Opportunities — Back-End & Front-End

### Programming Fundamentals via JavaScript

You'll use `node` to do these exercises, but what you learn translates to the browser.

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
1. If you *really* want, go through the [JavaScript Milestones][milestones-js].

## Practice Opportunities — Front-End

At this point, everyone knows enough HTML, CSS, and JavaScript to dive into almost any front-end topic they want. Here are some suggestions:

1. Become familiar with a CSS framework like [Bootstrap](https://getbootstrap.com/docs/4.5/getting-started/introduction/) or [Bulma](https://bulma.io/)
1. Build something with a graphing library like [Chart.js](https://www.chartjs.org/)
1.

## Practice Opportunities — Back-End

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
[milestones-js]: https://github.com/jfarmer/milestones-js
[curriculum-textalyze]: https://github.com/jfarmer/project-js-textalyze
[curriculum-static-photo-gallery]: https://github.com/jfarmer/project-js-static-photo-gallery
[examples-javascript]: https://github.com/jfarmer/examples-javascript
[curriculum-express-sandbox]: https://github.com/jfarmer/exercises-js-express-sandbox
[curriculum-social-wall]: https://github.com/jfarmer/project-js-social-wall
[curriculum-sql-queries]: https://github.com/jfarmer/sql-queries
[git-instructions]: https://gist.github.com/jfarmer/d9b18b38728d4621d1b2b849f1140fb5
[curriculum-pull-request]: https://github.com/jfarmer/exercises-git-pull-request
