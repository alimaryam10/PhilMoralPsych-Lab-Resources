---
layout: default
title: Creating Your Survey
parent: Getting Started
nav_order: 2
---

# Creating Your Survey: The Essentials 

## 🎯 Quick Tips Before You Start
- **Always hit PUBLISH** after making changes (yes, every single time).
- Ctrl + z to undo errors does **not work** with Qualtrics, however, you can recover previous versions to undo mistakes.
- Group questions into meaningful blocks, considering randomization requirements later on.	
- You might benefit from adding a [CAPTCHA](https://www.qualtrics.com/support/survey-platform/survey-module/editing-questions/question-types-guide/advanced/captcha-verification/) or other **Bot Checks**.

## 🔑 Essential Setup Steps

### 1. Participant Information (PI) & Consent Forms

> 💡 **Critical!** These *must* be added to your survey.
> **Note** Consent, debrief and demographic questions have been added to the lab's Qualtrics Library. Simply navigate to the library from the tab on the top left and go to 'XPhi Lab'. Remember to check the template to see how to properly set up early exit options.


1. Adding the consent form:
   - The consent form on Qualtrics should be the most updated one
   - **However**, if you submitted an ethics application for your study, the consent form might need to be updated to include your application code (check with your PI or lab manager)
   
2. Set up consent questions:
   - Always enable "Force Response"
   - Check that your consent questions include both "I consent" and "I do not consent" answer options
   - Ensure that there is an age verification question (18+) 
   - Set up branching logic (see section on randomization and logic) to exit if:
     - Participant **doesn't** consent
     - Participant is under 18
   
   > 🚨 Check the template to see how to properly set up early exit options (e.g., for non-consenting participants).

### 2. Organizing Your Questions

Tips for block organization:
- Consider how you want the order of your blocks to be
> You can group similar questions together, or set up specific blocks to be randomized.
- Use clear block names as they'll show up in your data - refer to the **creating blocks & questions** page for tips.

> 🥸 **The best tip we can give you**: Good organization now means less drama during data analysis later!

## 📝 Remember!
1. Click PUBLISH after any changes!
2. Check the template for examples
3. Do not put spaces or special characters in names (except `_`)
4. Force response for consent questions
5. Test your exit logic (e.g., for non-consenting participants) to ensure that it works

Need help? Don't suffer in silence - ask your lab manager! They've seen every Qualtrics quirk in the book (challenge: you could surprise them with a new one 🏆) 
