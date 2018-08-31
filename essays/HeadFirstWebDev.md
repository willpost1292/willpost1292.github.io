---
layout: essay
type: essay
title: Head First Web Developement
# All dates must be YYYY-MM-DD format!
date: 2018-08-30
labels:
  - Web Developement
  - Learning Experience
---

<img class = "ui medium left floated image" src="../images/Diving-Board.jpg">

# Head First Web Developement:
## How the quickest (and scariest) way to learn something is to dive right in.

  It was the summer of 2018, and I was looking at a mind numbing three months of waiting tables and cruising at the beach. As a computer science major, of course I had a list of technologies to learn and projects to complete, but when school is out and the weather's nice, it’s hard to dive into a 2000+ page book on C++. My productive outlook this summer looked grim until one day, on a whim, I asked  Joe, my restaurant manager, if there was any projects I could work on for the restaurant. Lucky for me, he was had an idea for a web project that would provide online training services for restaurant employees. The project would not only be used by employees of the restaurant I worked at, but all of it's sister restaurants as well (five in total). It was looking like I found a project for the summer.

  Joe and I started ironing out the details of the site. The project was gonna be bigger than I thought. Alot bigger. We are talking an admin page, a database, dynamically generated html, the works. This lead to two realizations. First, we needed to use a solid web framework. We decided on the Django framework because I have a pretty good understanding of the Python programming language, and Django seemed like a one stop shop as far as frameworks go. Second, I was gonna need help. My good friend Chris immediately came to mind. He was the hardest worker I knew, and a fast learner. There was only one issue. As a sophomore Electrical Engineering major, his programming skills was limited. But it’s like they say: “no time like the present to learn web development!”. We took a week to learn as much as we could about Django, Python, HTML, CSS, and JavaScript, and then began to work on a minimum viable product that Joe was gonna use to pitch to the company. We were given a deadline of three weeks. Bright eyed and bushy tailed, we embarked on a journey that would that teach us more about programming than any class we could ever take.

  Now before we started working, we developed strong guiding principles that we promised to follow so that our project would be successful. One: Our project would correctly use version control via git and GitHub. Two: all features would be tested thoroughly before being pushed to the server. Three: we would write code using good software practices, like not violating DRY (Don’t Repeat Yourself), and keeping things modular. We ended up breaking each of these principles repeatedly and horribly, but the resulting pain was an invaluable learning lesson. 

## Correctly Using Version Control

  Our process for version control was well thought out. Each feature would be it's own branch. Each branch would be worked on using a home machine, tested thoroughly, and be reviewed by the other partner before pushing the branch to the server. No code would be written directly on the server. We failed hard at version control. At first, we followed these steps perfectly. But as a deadline for a minimum viable product quickly approached, things went eschew. In the begining, branches had names like “homepages-models”, or “menu-base-css”. But by the day before we pitched, the branch were more like “Wed”, “dumb-fix”, or worst of all: “FINAL PUSH”, which like the name implies, included a ton of changes at once. These branches were near impossible to manage and introduced a ton of bugs. This brings us to our next epic fail: Testing.

## Testing

  We knew that if we were going to be successful, we needed to test everything. But because we needed to make a pitch soon, we went from writing tests before pushing to the server, to "code now, test later". We ended up wasting a ton of time looking for bugs that would seem to randomly pop up, simply because there were no unit tests to catch them when we made the changes that caused them. The greatest example of this is that “FINAL PUSH” branch I mentioned earlier. We realized that the way our database was structured had to be completely redone, which we did on the night before our big pitch. We made a ton of changes on one branch, which seemed to work on our home machines, and pushed to the server. These changes completely broke the project and the database, and it took up hours and hours to patch up all the bugs. Also, because we stopped having testing in mind, we didn’t write easy to test code, which made going back and writing the tests an enormous pain. Which brings us to the final fail, good coding practices.

## Good Coding Practices

  Under the pressures of the pitch deadline, code became ugly. I am ashamed to admit it, but we ended up having a lot of copy and pasted code. For instance, the different menu item types and all the different restaurants all had individual written database models instead of using inheritance. Instead of stopping and taking the time to properly plan and structure our code, we decided to push ahead to the pitch and refactor later. But tons of small changes needed to be made before the deadline, and each change became painful. We also wrote a lot of code that was tightly coupled, so a change in one file might break something that should have been interdependent. By the time we reached the pitch deadline, we had hundreds of lines of code that needed to be refactored.

  These failures made us refactor a ton of code, and write unit tests till our eyes bled. But these mis-steps also taught us how important good software development practices are. we ended up getting the job, but even if we didn’t it still would have been worth it. We learned so much about software development, and reaffirmed our love for programming. Chris even changed majors the following semester to Computer Engineering! The most valuable lesson we learned is that the best way to learn a technology isn't to comb over a textbook or an online tutorial. The best way to learn something is to dive right in. 
