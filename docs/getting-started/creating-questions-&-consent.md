---
layout: default
title: Creating Questions & Consent
parent: Getting Started
nav_order: 3
---

# Creating Questions & Consent 📝

## 🚨 Things to Remember Throughout 🚨
> * Group questions into meaningful blocks, considering randomization requirements later on.
> * After any change you make do not forget to click **PUBLISH** on the top right corner.


## Block & Question Naming Conventions
* Your **blocks and questions** should have meaningful, short names that use camel case or snake case (Attention_Check, AttentionCheck)
   * Meaningful short names (like Attention_Check) will be helpful when you download your data, since question names will be column names in your data sheet (e.g., Excel).
   * Do not leave spaces or use special characters (other than . or _) in the names since R will have a hard time reading these[^1].
   * You might benefit from creating a document that indexes how each question is labeled on Qualtrics if multiple colleagues are working on the data analysis separately[^2].
 
     [^1]: Spaces and special characters are the mortal enemies of R.
     [^2]: This will rescue you from playing "What on earth is variable XG_45b??" six months from now.

## Consent Forms Setup

* Start by creating a question for the participant information sheet and consent form
  
  > 🚨 **PLEASE NOTE**: The information sheet may need to change for your study (for example, if you submit a new ethics application for it). Please ask your lab manager for the most recent version of the PI form and consent form.
     
* Consent questions and similar should always have ["Force Response"](https://www.qualtrics.com/support/survey-platform/survey-module/editing-questions/validation/) turned on.
* Make sure the **participant leaves the study early** if they do not select "yes I agree" to consent or "yes I am 18 years old" (see template, and check the randomization and logic section of this guide).

 > 💡 See Template for Examples
> 
 > The lab Qualtrics template contains examples of properly formatted questions and consent forms that you can use as a reference when building your study.
> 
 >📍Simply go to Qualtrics (login using the lab credentials), and navigate to the 'Projects' tab in the menu on the top left (next to the XM logo). From here, you'll find a folder called "Projects and Programs" - click that to find the study templates.

