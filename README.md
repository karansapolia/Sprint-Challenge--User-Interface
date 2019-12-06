# Sprint Challenge: User Interface and Git - Multi-Page Website

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in a concrete project. This Sprint explored User Interface and Git. During this Sprint, you studied Semantic HTML, CSS Fundamentals, CSS Flexbox Module, and Git. In your challenge this week, you will demonstrate proficiency by creating a multi page website that has some missing HTML elements as well as CSS specificity problems that need to be solved.  You will also create an additional web page that will be linked to from a navigation you will build.

## Instructions

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the Sprint Challenge. However, you are encouraged to follow the twenty-minute rule and seek support from your TL if you need direction. Your work reflects your proficiency in user interface and your command of the concepts and techniques in semantic HTML, CSS fundamentals, CSS flexbox module, and git.

You have three hours to complete this challenge. Plan your time accordingly.

## Commits

Commit your code regularly and meaningfully. This helps both you (in case you ever need to return to old code for any number of reasons and your project manager.

## Description

In this challenge, you build a missing header (navigation and image) on the home page, update some CSS styling on the home page, and create an additional page (About) which will link from the navigation you created.

In meeting the minimum viable product (MVP) specifications listed below, your web page should look like the solution screen shots of the home and about pages:

[Click here for the home page example](https://tk-assets.lambdaschool.com/39a49225-8ac9-43da-aa90-514fd60ae99a_sprint-challenge-ui-home-example.png)

[Click here for the about page example](https://tk-assets.lambdaschool.com/ede1bb1a-63ff-4801-8c02-3efa2f603190_sprint-challenge-ui-about-example.png)

## Self-Study Questions

Demonstrate your understanding of this week's concepts by answering the following free-form questions.

Edit this document to include your answers after each question. Make sure to leave a blank line above and below your answer so it is clear and easy to read by your project manager

1. If you were to describe semantic HTML to the next cohort of students, what would you say?

- Ans. Semantic HTML are HTML tags which give more meaning to an HTML document than using plain divs for everything. Semantic HTML markup conveys the underlying meaning of a webpage’s content. It makes the document more readable for search engines, screen readers and developers.
For example, nesting a page within a number of ```<div></div>``` tags and breaking sections using it is less readable than using one ```<article></article>``` for the complete document and many ```<section></section>``` tags for various sections of the document.

2. Name two big differences between ```display: block;``` and ```display: inline;```.

- Ans. ```display: block``` makes the element it is applied to have a line break before and after the element. It takes up the full width available to it. And allows setting the height and width properties on the element.

```display: inline``` stays on the same line. It does not break into a new line. It only takes as much space as needed by the element content. You cannot set height and width properties on an inline element.

3. What are the 4 areas of the box model?

- Ans. The four areas of a box model, beginning from inside are:
  - Content – This is where the text, images or any content of the tag are displayed.
  - Padding – The transparent separation space between the content and the border.
  - Border – This is the border of the element. It can be styled and increased/decreased as required.
  - Margin – The transparent region outside the border which can be used for formatting and spacing.

4. While using flexbox, what axis does the following property work on: ```align-items: center```?

- Ans. The ```align-items: center;``` property works on the cross-axis on the element. 
With ```flex-direction: row``` or ```flex-direction: row-reverse```, the cross-axis is the vertical axis.
With ```flex-direction: column``` or ```flex-direction: column-reverse```, the cross-axis is the horizontal axis.

5. Explain why git is valuable to a team of developers.

- Ans. Git helps maintain and save multiple versions of files / folders without creating conflicting copies of them. It saves multiple versions of the files according to timestamps and calls it the git history. All the versions are saved in the .git directory that is created.
It helps multiple people work on the same file simultaneously and keeps track of all the changes made to it and helps in merging the changes and undoing or redoing any changes as and when desired. This is also what any other version control system does.
It provides us the option to work on different versions of the same file by using the concept of branches, and then merge whatever version we desire to.
Git also maintains a log of the changes made with their timestamp and exact version number. We can travel to and use exact older versions of the file by using the hash of the git commit we view in a git log.
All these features of git help make it a valuable system for a team of developers.

You are expected to be able to answer all these questions. Your responses contribute to your Sprint Challenge grade. Skipping this section *will* prevent you from passing this challenge.

## Project Set Up

- [ ] Create a forked copy of this project.
- [ ] Add your project manager as collaborator on Github.
- [ ] Clone your OWN version of the repository (Not Lambda's by mistake!).
- [ ] Create a new branch: git checkout -b `<firstName-lastName>`.
- [ ] Implement the project on your newly created `<firstName-lastName>` branch, committing changes regularly.
- [ ] Push commits: git push origin `<firstName-lastName>`.
 
Follow these steps for completing your project.

- [ ] Submit a Pull-Request to merge <firstName-lastName> Branch into master (student's  Repo). **Please don't merge your own pull request**
- [ ] Add your project manager as a reviewer on the pull-request
- [ ] Your project manager will count the project as complete by merging the branch back into master.
 


## Minimum Viable Product

Your finished project must include all of the following requirements:

### Home Page

[Review the provided design file for the home page](design-files/home.png).  Notice the navigation and header images are missing.

* [ ] Build the HTML and CSS to create the missing navigation and header.
* [ ] Link the `About` navigation item to the [about.html](about.html) page

You will also notice there are 10 boxes on the home page that need background colors.  Use this list below to correctly style each box:

* [ ] box1: `teal`
* [ ] box2: `gold`
* [ ] box3: `cadetblue`
* [ ] box4: `coral`
* [ ] box5: `crimson`
* [ ] box6: `forestgreen`
* [ ] box7: `darkorchid`
* [ ] box8: `hotpink`
* [ ] box9: `indigo`
* [ ] box10: `dodgerblue`

### About Page

[Review the provided design file for the about page](design-files/about.png). You have been provided the HTML wrapper, footer, and page content for the about page. Create the rest of the missing HTML and CSS to match the design file.

* [ ] Copy and paste your home page navigation and header into the about page
* [ ] Update the header image with the about page image
* [ ] Link the `Home` navigation item back to the `index.html` page.
* [ ] Build the rest of the about page layout to match the design

In your solution, it is essential that you follow best practices and produce clean and professional results. Schedule time to review, refine, and assess your work and perform basic professional polishing including spell-checking and grammar-checking on your work. It is better to submit a challenge that meets MVP than one that attempts too much and does not.

## Stretch Problems

After finishing your required elements, you can push your work further. These goals may or may not be things you have learned in this module but they build on the material you just studied. Time allowing, stretch your limits and see if you can deliver on the following optional goals:

* [ ] Build a page of your choosing from the navigation items.  Come up with content and images that fit the theme.  
* [ ] Introduce CSS animations to your site.
* [ ] Build a contact page and create a form with several inputs of your choosing
* [ ] Add responsive breakpoints to your code by using media queries
