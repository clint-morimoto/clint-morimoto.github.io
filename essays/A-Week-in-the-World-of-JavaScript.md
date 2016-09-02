---
layout: essay
type: essay
title: A Week in the World of JavaScript Coding
date: 2016-09-01
labels:
  - JavaScript
---

<img class="ui medium right spaced image" src="../images/E09_JS.jpg">

JavaScript: Not the first programming language most coders learn, myself included.  Yet it's possible that may change in the future, with JavaScript's [increasing popularity](http://thenewstack.io/javascript-popularity-surpasses-java-php-stack-overflow-developer-survey/) as a language for both front-end and back-end web application development.  With that wonderful motivation for getting well-versed in JavaScript, what's not to like?  It's perhaps too early to tell, but after spending a week going through an [introductory JavaScript module](http://courses.ics.hawaii.edu/ics314f16/modules/javascript-1/) for Software Engineering I at UH Manoa, early returns are both interesting and promising.

## Second Go-Round Already Different from the First

This is my second encounter with JavaScript in about a year's time, and surprisingly I have already come across a big fundamental change in a standard: the use of *let* and *const* instead of *var* for creating variables.  It is a seemingly simple, yet striking change, as one of the most common sights in any program's code is the declaration of variables.  Now that let and const have replaced var, it almost feels like a whole new language even though the rules for using them in place of var appear simple enough; use let for variables whose values will, or might, be changed, and use const for variables that will contain constant values.  The reason for this change is not something I have completely wrapped my head around, but my understanding of it is that the way var worked allowed its value to be changed outside of the block of code where it was declared, while let and const are block-scoped, only allowing their value to be changed inside the code block of their declaration.  This allows JS code to be safer and more stable.

## Three Little Letters can be Scary

Taking Software Engineering I at UH Manoa also includes a pretty unique learning experience, at least from my experience studying computer programming, with the use of [WODs](http://courses.ics.hawaii.edu/ics314f16/morea/introduction/reading-athletic-software-engineering.html).  The acronym stands for Workout Of the Day, and the workout part is no joke as far as I'm concerned!  The main aspect of these academic workouts that are rather challenging, and possibly highly stressful, is the combination of these tests being timed, and, given the caveat that if they are not 100% functional according to the guidelines of the WOD, you receive zero credit.  While I may question the origin of newly gray or missing hair on my head after this semester, I cannot deny that this has a lot of potential to boost my engagement with learning how to code in JavaScript effectively and efficiently.