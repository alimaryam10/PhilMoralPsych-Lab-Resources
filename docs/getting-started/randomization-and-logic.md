---
layout: default
title: Randomization & Branch Logic
parent: Getting Started
nav_order: 4
---

# Randomization and Logic Setup 🎲

> **What is randomization?**
>- The randomization function in Qualtrics (or 'randomizer') allows you to randomly present question blocks, embedded data, and other aspects of your survey such as branches.

## Setting Up Randomization
Proper randomization is crucial for your experiment's validity. Here's how to do it step by step - but you can find a more detailed guide [here](https://www.qualtrics.com/support/survey-platform/survey-module/survey-flow/standard-elements/randomizer/):

### Randomizing Question Blocks or Study Conditions
1. Navigate to the "Survey Flow" tab on Qualtrics
2. Add a Randomizer element
3. Select "Evenly Present Elements"
4. Add your condition blocks under the randomizer
5. Set presentation numbers:
   - For single condition per participant: "Randomly present 1 of the following elements"
   - For multiple conditions: "Randomly present X of the following elements"

> 🔄 **Remember**: If you add more blocks later, you'll need to update your randomizer numbers!

## Branch Logic

> **What is branch logic?**
>- Branch logic in your survey flow lets you create different paths for people taking your survey. They work like forks in a road, they let you:
 - Send people to different questions based on how they answer
 - Create personalized survey experiences
 - Skip irrelevant sections automatically
 - Show special questions only to certain people
   
### Setting Up Branches
1. Identify branching points
2. Set up clear conditions
3. Test all possible paths
4. Verify end points

### Common Use Cases
- Consent form branching
- Attention check routing
- Condition-specific questions
- Early exit paths

> 💡 **Pro Tip**: Draw out your logic flow on paper first - it helps spot potential issues before building!
> ❓You can also explore different kinds of logic functions, such as [skip logic](https://www.qualtrics.com/support/survey-platform/survey-module/question-options/skip-logic/) and [display logic](https://www.qualtrics.com/support/survey-platform/survey-module/question-options/display-logic/) to help you design your survey
