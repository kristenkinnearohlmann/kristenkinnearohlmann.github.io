---
layout: post
title:      "Idea Pool - A Sinatra project that meets a need"
date:       2021-04-09 02:03:36 +0000
permalink:  idea_pool_-_a_sinatra_project_that_meets_a_need
---


## Ideation

As I worked through the Sinatra lessons, I was already thinking about what project I could complete that would both leverage what I had learned as well as serve a purpose. Always present in my mind is the "blank page" problem - how do you decide what to create when you're asked to create something? This is an important problem to me now, with several more projects to go and a short time to complete them, as well as when I am asked to ideate for hackathons, to practice a new skill, or looking for an open source project to contribute to.

This was the genesis for **Idea Pool**, a tool where people who are bursting with ideas - they do exist! - could do a service to those of us that freeze up when the "blank page" is shoved in front of them. It would also allow people to store an idea when it occurred to them, either publicly or privately, for later development. Finally, by connecting projects developed from these ideas, people could further develop or create new ideas. It was nice to have a concept that was so near and dear to my heart!

## Technical Challenges

Although I had completed the Windows environment setup, I was still a bit leery about actually being able to run a project on WSL (Windows Subsystem for Linux) successfully. I had taken cover during the lesson portion inside the IDE, where I knew things would run smoothly. I didn't have any worries about setting up the framework - that was covered well in the lessons and one of Avi's videos - I just didn't know if it would work!

I'm glad **be scrappy** was part of the advice for the project. I found myself diving into technical challenge after technical challenge, problem-solving on a thin margin of Windows-related resources on Google. I ultimately found that I had to:
- Be more explicit in how I specified `bcrypt` in my Gemfile
- Use `require` instead of `require_relative` in `config.ru` to allow `tux` and `rake console` to run properly (thanks obscure issue on a [Flatiron lab repo](https://github.com/learn-co-curriculum/sinatra-complex-forms-associations/issues/29))
- Remove `thin` from my Gemfile to avoid a bootstrap error (3 hours on that one and FINALLY found another obscure reference to the fix in the original repo for the [Sinatra CRUD lab](https://github.com/learn-co-curriculum/sinatra-ar-crud-lab/issues/60)); I had to create a whole sample app aside from my project app to verify!

## So Much Learning

I learned so much from this project and enjoyed even the ugly, hard parts. My CSS game was on-point, I found myself muttering about protecting routes and new-ing up objects, checking my params and session for things and even creating an additional helper function. I was able to get a word of advice from study group sessions (shout out to Dustin!) and understand and implement Sinatra Flash and dependencies in models quickly.

Going to study group ahead of starting the project really helped. It allowed me to hear other students talk through work, follow their thought patterns, and learn from their mistakes AND their successes.

## This App Isn't Done

Well...it **IS** done for submission and project review! It meets the requirements laid out for the project and does so in a stylish and comprehensive manner. 

If I didn't need to get moving on my June 30 deadline, there's a number of stretch features I would enjoy adding!

- Implementing HTML encoding and escaping for input/output to the application
- The ability to archive ideas and projects
- Strengthening the associations, validations and potentially using aliases to make more robust the database models
- Converting to using a PostgreSQL database and deploying to Heroku for wider audience use
- Identifying open source opportunities and advertising them to people seeking the experience

I definitely belive **Idea Pool** is a resource and starting point for the creative and development communities. I plan to continue building out the application for the future!
