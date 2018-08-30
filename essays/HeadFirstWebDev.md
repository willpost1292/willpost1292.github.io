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

<img class="ui tiny right spaced image" src="../images/Diving-Board.jpg">
<h1>Head First Web Developement</h1>
<h3>How the quickest (and scariest) way to learn something is to dive right in.</h3>

  It was the summer of 2018, and I was looking at a mind numbing three months of waiting tables and cruising at the beach. As a computer science major, of course I had a list of technologies to learn and projects to compete, but when school is out and the weather's nice, it’s hard to dive into a 2000+ page book on C++. My productive outlook this summer looked grim until one day, on a whim, I asked my manager, Joe, if he had any programming work for me. Lucky for me, he did. He was working on a web project for the restaurants and it’s sister restaurants. The project would be used to train new and existing employees. It looked like I had found a summer project.

  Joe and I started ironing out the details of the site. The  project was gonna be bigger than I thought. Alot bigger. We are talking an admin page, a database, dynamically generated html, the works. This lead to two realizations. First, we needed to use a solid web framework. We decided on the Django framework because I have a pretty good understanding of the Python programming language, and Django seemed like a one stop shop as far as frameworks go. Second, I was gonna need help. My good friend Chris immediately came to mind. He was the hardest worker I knew, and a fast learner. There was only one issue. As a sophomore Electrical Engineering major, his programming skills was limited. But it’s like they say: “no time like the present to learn web development!”. We took a week to learn as much as we could about Django, Python, HTML, CSS, and JavaScript, and then embarked on a journey that would that teach us more about programming than any class we could ever take.
  
  Every step we took with this project was a learning experience. We poured countless hours working and learning about http requests, database design, caching, and way more. But while we were working, we had a strong guiding principles that we we promised to follow so that our project would be successful. One: Our project would correctly use version control via GitHub. Two: all features would be tested thoroughly before being pushed to the server. Three: We would code using good software practices, like not violating DRY (Don’t Repeat Yourself) and keeping things modular. We ended up breaking each of these principles horribly, but the resulting pain was an invaluable learning lesson. 


## Correctly Using Version Control

  Our process for version control was well thought out. Each feature would be a branch. Each branch would be worked on using a home machine, tested thoroughly, and be reviewed by the other partner before pushing the branch to the server. No code would be written directly on the server. We failed hard at version control. At first, we followed these steps perfectly. But as a deadline for a minimum viable product quickly approached, things went eschew. When the names became indecipherable, It became impossible to manage who was working on what, and in fact a lot of work ended up being wasted. This degeneration of branches is made clear from our branch names. First the names were “homepages-models”, or “menu-base-css”. But by the day before we pitched, the branch names became “Wed”, “dumb-fix”, or worst of all: “FINAL PUSH”. Which brings to the next epic fail, Testing.

## Testing

  We knew that if we were going to be successful, we needed to test everything. But because we needed to make a pitch soon, we change our policy from writing tests before pushing to server to code now test later. We ended up wasting a ton of time looking for bugs that would seem to randomly pop up, simply because there were no unit tests to catch them when we made the change that caused them. The greatest example of this is that “FINAL PUSH” branch I mentioned earlier. We realized that the way our database was structured had to be completely redone, which we did on the night before our big pitch. We made a ton of changes on one branch, which seemed to work on our home machines, and pushed to the server. These changes completely broke the project and the database, and it took up hours and hours to patch up all the bugs. Also, because we stopped having testing in mind, we didn’t write easy to test code, which made going back and writing the test an enormous pain. Which brings us to the final fail, good software practices.


## Good Coding practices

  Under the pressures of the pitch deadline, code became ugly. I am ashamed to admit it, but we ended up having a lot of copy and pasted code, for instance, the different menu item types and all the different restaurants all had individual written database models instead of using inheritance. We thought we would just refactor after pitching. But a little change here and there that needed to be made became painful, and all the while we knew that this code was gonna be refactored anyway. We also wrote a lot of code that was tightly coupled, so a change in file might break something that should have been interdependent.

  All these failures did two things for us. First, It made us refactor a ton of code. And second, it taught us how important good software development practices are. After we told Joe we finished the pitch, the company higher-ups didn’t actually see what we finished until a month later! But we ended up getting the job, and even if we didn’t it still would have definitely been worth it. We learned so much about software development, and it enthused us even more to the field. Chris even changed majors the following semester to Computer Engineering! (He couldn’t switch to C.S because of the G.I bill). The most valuable lessoned we learned is that the best way to learn a technology isn't to comb over a textbook or an online tutorial. The best way to learn something is to dive right in. Just make sure you don't drown like we almost did!

