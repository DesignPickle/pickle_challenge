# Design Pickle Code Challenge

Thanks for applying to Design Pickle!

We'd love to learn about how you work / write code, but we value your time and understand that you probably have to complete many coding challenges, so we'll try to keep this brief. 

We ask that you spend a few hours (no more than 5) on the following challenge. We want you to be able to show your skills and commitment to writing great code in a pressure-free setting (just like you will be doing for Design Pickle!). The goal of this is NOT to have a production-ready application. There are multiple ways you can show us your skills, as you will see below, all based on the Github API. Be sure to take into consideration how long it will take to complete your solution. Remember, this is about quality, not quantity, and we don't want you spending a whole day on this.

- Please use Ruby version 2.6.0. It makes our job a million times easier. Thank you!
- Please use Ruby on Rails 5 or 6 for this project. We DO expect the final product to be a webpage (not just a console application).

# The Challenge

Use the [Public Github API](https://developer.github.com/v3) to build a rudimentary service to query the [Github Rails repository](https://github.com/rails/rails) issues and filter them.

# Requirements

Grab only the *open* and *unassigned* issues.

## Filter by Components
In the repository, the Rails team uses labels to define the components of the stack the issues relate to. We'd like you to create an interface where a user can filter the results (issues) by the following components:

- ActionCable
- ActionMailer
- ActionPack
- ActionView
- ActiveJob
- ActiveModel
- ActiveRecord
- ActiveStorage
- ActiveSupport
- Asset Pipeline

## Order the results 
Allow users to order the results by comment count (ascending and descending).

# Preparing to submit
- Write a README - this should explain what you implemented (high level). Mention if you'd add anything else to this project to make it better.
- Include a `.ruby-version` file in your Rails root folder.
- Please don't put your solution on Github. We don't want our candidates to be able to see each other's work and the history of the project. Please take your entire directory, and zip or tarball it for submission.
- Please include your name on the name of the compressed file. It will help us out a lot!

# What's next?
After you submit your solution, we'll review your code to see what you implemented and how you did it. We will use this to gauge your coding abilities and as a starting point for the next interview - a pairing session with our lead engineer - where we'll have you walk us through your implemented solution.

For the pairing session, be prepared to:

- Talk about any of the complex parts of your solution, why you solved things a certain way, and what challenges you faced.
- Modify your code as a pair and screenshare a functional local version of your app
- Go through your resumé and answer questions about your career path

# FAQ

These are some of the frequently asked questions we've received in the past about the pickle challenge.

### Does this need to be a single page app or a vanilla server rendered page Rails app?

A normal server rendered page Rails app is fine unless you really want to build a single page app.

### How well do you want the issues to be presented?

We’re not expecting a pro graphic designer / front-end css expert (it's awesome if you are though!). Keep it simple, yet presentable.

### Rails is overkill for this, can I use something lighter?

Please use Ruby on Rails as our main product at Design Pickle is built on Rails.