---
layout: project
type: project
image: images/micromouse.jpg
title: HCR Online Training
permalink: projects/hcronlinetraining
# All dates must be YYYY-MM-DD format!
date: 2018-07-14
labels:
  - Django
  - Python 3
  - Linux
  - Apache
  - JavaScript
  - HTML
  - CSS
summary: My partner and I created a web application used to train employees for a restaurant ownership group.
---
<div class="ui small rounded images">
  <img class="ui image" src="../images/micromouse-robot.png">
  <img class="ui image" src="../images/micromouse-robot-2.jpg">
  <img class="ui image" src="../images/micromouse.jpg">
  <img class="ui image" src="../images/micromouse-circuit.png">
</div>

HCR Online Training is a web application used to train new and existing employees that are employed at any of the restaurants owned and operated by the Handcrafted Restaurant Group (HCR), which is comprised of five high volume restaurants. Nearly all  components of the project's web pages are custimizable via an admin page.The project is implemented using  the Django web framework, and is written in Python, HTML, CSS, and JavaSript. The project is hosted on an Appache http server provided by DreamHost. The project's datebase schema is implemented using MySQL.

Under the Django framework paridigm, the project's components are broken down into "apps". The following apps for this project include:

Homepages - A restaurants landing page where employees can view the current running food and drink specials and updates.

Menus - Where employees can learn in detail about food and beverage menu items. 

training - Provides position specific study material for new employees to pass hiring exams. 

HCR items - A repository for comanpany specific items, such as recipes.

Each app has a corresponding admin and database interface. 
 


```js
byte ADCRead(byte ch)
{
    word value;
    ADC1SC1 = ch;
    while (ADC1SC1_COCO != 1)
    {   // wait until ADC conversion is completed   
    }
    return ADC1RL;  // lower 8-bit value out of 10-bit data from the ADC
}
```

You can learn more at the [UH Micromouse Website](http://www-ee.eng.hawaii.edu/~mmouse/about.html).



