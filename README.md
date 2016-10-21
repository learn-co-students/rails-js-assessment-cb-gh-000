# Build a Rails App with a jQuery Front End

## Overview

In this assessment your goal is to expand upon the rails assessment you did previously. The goal is to add dynamic features that are possible only through jQuery and a JSON Api for your app. **Do not use `remote: true` in this application`**

## Requirements

 1. Must render at least one index page (index resource - 'list of things') via jQuery and an Active Model Serialization JSON Backend. For example, in a blog domain with users and posts, you might display the index of the users posts on the users show page, fetching the posts via an AJAX GET request, with the backend rendering the posts in JSON format, and then appending the posts to the page.

 2. Must render at least one show page (show resource - 'one specific thing') via jQuery and an Active Model Serialization JSON Backend. For example, in the blog domain, you might allow a user to sift through the posts by clicking a 'Next' button on the posts show page, with the next post being fetched and rendered via JQuery/AJAX.

 3. The rails API must reveal at least one `has-many` relationship in the JSON that is then rendered to the page. For example if each of those posts has many comments, you could render those comments as well on that show page.

 4. Must use your Rails API and a form to create a resource and render the response without a page refresh. For example, a user might be able to add a comment to a post, and the comment would be serialized, and submitted via an AJAX POST request, with the response being the new object in JSON and then appending that new comment to the DOM.

 6. Must translate the JSON responses into Javascript Model Objects. The Model Objects must have at least one method on the prototype. Formatters work really well for this.
 Borrowing from the previous example, instead of plainly taking the JSON response of the newly created comment and appending it to the DOM, you would create a Comment prototype object and add a function to that prototype to perhaps concatenate (format) the comments authors first and last name. You would then use the object to append the comment information to the DOM.

## Instructions

1. Make the changes to your existing Rails assessment repo.
2. Add the spec-js.md file from this repo to the root directory of the project, commit it to Git and push it up to GitHub.
3. Submit that repo to the assessment immediately.
4. Build your app there. Make sure to commit early and commit often. Commit messages should be meaningful (clearly describe what you're doing in the commit) and accurate (there should be nothing in the commit that doesn't match the description in the commit message). Good rule of thumb is to commit every 3-7 mins of actual coding time. Most of your commits should have under 15 lines of code and a 2 line commit is perfectly acceptable. **This is important and you'll be graded on this**.
6. Record at least a 30 min coding session. During the session, either think out loud or not. It's up to you. You don't need to submit it, but we may ask for it at a later time.
7. Submit a video of how a user would interact with your working application.
8. Make sure to check each box in your spec.md (replace the space between the square braces with an x) and explain next to each one how you've met the requirement *before* you submit your project.
9. Submit the url to your github project
10. Write a blog post about the project and process.

Unlike the rest of the curriculum, if you have any questions about your assessment or need help with it, please *don’t* use the Ask New Question feature. Rather than working with Learn Experts, please reach out to the Learn Instructor responsible for this section instead - Mendel / mendel@flatironschool.com / learn-co slack: mendel.

## If you're a Learn-Verified Premium student:

We should reach out to you soon to schedule a pairing process. If you don't hear from us in 48 hours after submission, reach out to us on Slack!

### Be Prepared to:

1. Explain your code from execution point to exit point. We're making sure you wrote it and understand how it works, nothing else. 5-10 minutes
2. Write tests together. You'll be responsible for making tests pass, not writing test code. However, you'll be expected to provide expected return data of methods. You'll need to know how your code should work, not rspec or testing. 20-30 minutes
3. Refactor code. 20-30 minutes
4. Extend the application with a new feature, more data, a different domain etc. 20-30 minutes
5. Submit an improved version.
6. Write a README.md.

### What to expect from the pairing session

- Use the best vocabulary you can. Technical terms allow for you to be more precise which makes conversations about code much easier.
- If you make a mistake, correct yourself! We all make mistakes, I promise.
- Trust yourself
- Trust us
- Think on your feet. Feel free to look things up while you're pairing with us. You'll be asked to expand on concepts you implemented and you will be pushed to the edge of your knowledge.
- Explain the details. We're curious!
- You're going to learn a ton. We will give pointers and show you ways to improve your code. This isn't telling you that your code is wrong, it's simply us teaching. Whatever you don't quite understand will be explained

### What won't happen:

- You won't be told you're ever wrong
- You won't be yelled at, belittled, or scolded
- You won't be put on the spot without support
- There's nothing you can do to instantly fail or blow it.

## Video Review Resources- AJAX and Rail s

* [Loading Comments via GET AJAX](https://www.youtube.com/watch?v=E8TJmwW5ayQ)
* [Rails and AJAX, Submitting a Form](https://www.youtube.com/watch?v=XxzayZma5Ew)
* [Adding Form Fields via AJAX](https://www.youtube.com/watch?v=BcGtDkydAug)
* [Handlebars and JS Prototypes](https://www.youtube.com/watch?v=PT_C2211_QE) 


<p class='util--hide'>View <a href='https://learn.co/lessons/rails-js-assessment'>Rails App with a jQuery Front End</a> on Learn.co and start learning to code for free.</p>
