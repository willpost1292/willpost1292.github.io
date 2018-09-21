---
layout: essay
type: essay
title: Keeping Code Clean
# All dates must be YYYY-MM-DD format!
date: 2018-09-20
labels:
  - Web Developement
---

<img class = "ui medium right floated image" src="../images/house.jpg">

# Keeping Code Clean

Have you ever heard of the broken window theory? 
The broken window theory is the idea that visible signs of disorder like vandalism encourage more serious crimes. 
And it makes sense right? Whenever you ever go into a impeccably clean house (certainly not mine), a sensation overcomes you 
that you need be extra careful not to mess anything up. The software equivalent of keeping one’s house in order is the 
following of coding standards. Software projects need strong coding standards in order to be successful. Luckily, 
there is a ton of automated tools that help ensure everyone's code is following a standard, such as linters.
But project standards need to go beyond linters. More conceptual coding standards like naming conventions also need to be 
decided on before starting a project, so that everyone is on the same page and can work cohesively.

## Linters

Linters are awesome tools that analyze your code for styling errors in order to keep everyone's source code consistent.
Any IDE worth it’s salt allows for integration with linters, so there is really no excuse for developers not to be using 
a linter to keep their code clean. The IDE I use, IntelliJ IDEA, won’t even let me make commits with out flagging me 
with all the coding rules I’m violating. Linters also go beyond just making sure your using correct line spacing.
Linters also help keep your code bug free by catching bugs that your compiler won’t, as well as  keeping your code 
fast by making sure your not defining things your not using. Linters are also customizable, so developers can all agree 
on a linting standard that everyone should abide by. 


## Beyond linting

Syntax rules are only be a small part of a development standard. There are other standards that developers should agree on,
such as naming convention, documentation, namespacing, and directory organization. Team members need to be on same page 
with these concepts so everyone can easily understand each other's code. If you have ever worked on a project where these 
standards aren't in place, you know how frustrating it can be to read source code littered with one letter variables and 
uncommented code. These details must be decided on before development to keep everyone sane.

##
Deciding on these standards may seen meticulous. But code dystrophy is a very real and scary thing. When source code needs 
to be refactored, and it will be, the last thing project members should be worried about is navigating poorly styled and 
poorly organized code. Keeping strong unified coding standards is vital for a project to be a success. So follow a strong 
standard and keep your house clean!
