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

## 📋 Naming Your Questions & Blocks

### The Golden Rules of Naming
Think of question names like pet names - they'll stick around forever in your data, so choose wisely.

Use either:
- `snake_case` (attention_check)
- `camelCase` (attentionCheck)

✅ Good names:
- `moral_dilemma_1`
- `consentResponse`
- `age_check`

❌ Bad names (will make R cry):
- `Moral Dilemma 1`
- `consent response!!`
- `age.check.#1`

> 💡 **Pro Tip**: Create a question name index in Word if multiple people will analyze the data. Your future self will thank you!

## 🔑 Essential Setup Steps

### 1. Participant Information (PI) & Consent Forms

> 💡 **Critical!** These *must* be added to your survey. **Note** Consent, debrief and demographic questions have been added to the lab's Qualtrics Library. Simply navigate to the library from the tab on the top left and go to 'XPhi Lab'. Remember to check the template to see how to properly set up early exit options.
> 


1. Get the latest forms:
   - Ask your lab manager for current PI form
   - Get the most recent consent form template
   
2. Set up consent questions:
   - Always enable "Force Response" (we really need these answers!)
   - Add age verification question (18+)
   - Set up branching logic (see section on randomizetion and logic) to exit if:
     - Participant doesn't consent
     - Participant is under 18
   
   > 🚨 **Critical!** Check the template to see how to properly set up early exit options

### 2. Organizing Your Questions

Tips for block organization:
- Group similar questions together
- Consider future randomization needs
- Use clear block names (they'll show up in your data)

> 🎭 **Fun fact**: Good organization now means less drama during data analysis later.

## 📝 Remember!
1. PUBLISH after changes (yes, we're saying it again!)
2. Check the template for examples
3. No spaces or special characters in names (except `_` and `.`)
4. Force response for consent questions
5. Test your early exit logic

Need help? Don't suffer in silence - ask your lab manager! They've seen every Qualtrics quirk in the book (challenge: you could surprise them with a new one 🏆) 
