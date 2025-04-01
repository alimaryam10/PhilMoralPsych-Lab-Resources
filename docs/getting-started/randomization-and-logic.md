---
layout: default
title: Randomization and Logic
parent: Getting Started
nav_order: 4
---

# Randomization and Logic Setup 🎲

## Setting Up Randomization
Proper randomization is crucial for your experiment's validity. Here's how to do it step by step:

### Creating Randomized Blocks
1. Navigate to the "Survey Flow" tab
2. Add a Randomizer element
3. Select "Evenly Present Elements"
4. Add your condition blocks under the randomizer
5. Set presentation numbers:
   - For single condition per participant: "Randomly present 1 of the following elements"
   - For multiple conditions: "Randomly present X of the following elements"

> 🔄 **Remember**: If you add more blocks later, you'll need to update your randomizer numbers!

## Survey Flow Logic

### Setting Up Display Logic
1. Click the question options menu
2. Select "Add Display Logic"
3. Choose your conditions:
   - Based on previous responses
   - Based on embedded data
   - Based on randomizer assignment

### Common Logic Patterns
✅ Good practices:
- Use clear, simple conditions
- Test all logic paths
- Document complex logic flows

❌ Avoid:
- Circular logic
- Overcomplicated conditions
- Untested logic paths

> 🚨 **Warning**: Always test your logic flow with the Preview tool - what makes sense on paper might not work in practice!

## Branch Logic

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
