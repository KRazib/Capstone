Capstone Final Project Submission
========================================================
author: Razib Ahamed Khan
date: 30-10-2019
autosize: true

1. SECTION A
========================================================

## 1.1 Assignment: Final Project Submission

**Instructions**

  The goal of this exercise is to create a product to highlight the prediction algorithm that you have built and to provide an interface that can be accessed by others. For this project you must submit:

  - A Shiny app that takes as input a phrase (multiple words) in a text box input and outputs a prediction of the next word.
  - A slide deck consisting of no more than 5 slides pitching your algorithm and app as if you were presenting to your boss or an investor.


1.2 Review criteria
========================================================
**Data Product**

  - Does the link lead to a Shiny app with a text input box that is running on shinyapps.io?
  - Does the app load to the point where it can accept input?
  - When you type a phrase in the input box do you get a prediction of a single word after pressing submit and/or a suitable delay for the model to compute the answer?
  - Put five phrases drawn from Twitter or news articles in English leaving out the last word. Did it give a prediction for every one?


1.3 Slide Deck
========================================================
  - Does the link lead to a 5 slide deck on R Pubs?
  - Does the slide deck contain a description of the algorithm used to make the prediction?
  - Does the slide deck describe the app, give instructions, and describe how it functions?
  - How would you describe the experience of using this app?
  - Does the app present a novel approach and/or is particularly well done?
  - Would you hire this person for your own data science startup company?
  
2. SECTION B
========================================================
## 2.1 Text-Mining

  In the shiny app, users can casually key in any character inside text box. The the system will auto appear the suggested next predictive words in table format by follow the most accurate in sequence. You can show/hide the author and source code link if you like.

## 2.2 Short Brief

  I am using `tm` and `RWeka` packages for previous assignments, but occassionaly noticed a new package `quanteda` which is more efficient and clean, clear and concise and text mining and n-grams words prediction. At the same time I am using [`shinyjs`](https://github.com/daattali/shinyjs) package to come out with better output and interactive. I've removed the graphs while you can refer to [Natural Language Analysis](https://beta.rstudioconnect.com/englianhu/Natural-Language-Analysis/) if you'ld like to.

  You are feel free to browse over the shiny app at [Final Project-Submission (Shiny App)](https://ronjubd.shinyapps.io/Capstone/).


3. SECTION C  
========================================================

  It's useful to record some information about how your file was created.
  
  - File creation date: 2019-10-10
  - File latest updated date: 2019-10-30
  - R version 3.6.1 (2019-07-05)
  - R version (short form): 3.6.1
  - [**revealjs** package](https://github.com/rstudio/revealjs) version: 0.9
  - File version: 1.0.0
  - Author Profile: [Razib Ahamed Khan]
  - GitHub: [Source Code](https://github.com/KRazib/Capstone)
  - Additional session information:

[1] "2019-10-30 17:54:42 +08"
 setting  value                       
 version  R version 3.6.1 (2019-07-05)
 os       Windows 7 x64 SP 1          
 system   x86_64, mingw32             
 ui       RTerm                       
 language (EN)                        
 collate  English_Malaysia.1252       
 ctype    English_Malaysia.1252       
 tz       Asia/Kuala_Lumpur           
 date     2019-10-30                  
                     sysname                      release 
                   "Windows"                      "7 x64" 
                     version                     nodename 
"build 7601, Service Pack 1"            "ISVPNKLT0000166" 
                     machine                        login 
                    "x86-64"                      "Razib" 
                        user               effective_user 
                     "Razib"                      "Razib" 
