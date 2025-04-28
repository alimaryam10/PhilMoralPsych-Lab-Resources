---
layout: default
title: Creating Questions
parent: Getting Started
nav_order: 3
---

# Creating Questions

## 🚨 Things to Remember Throughout 🚨
> * Group questions into meaningful blocks, considering randomization requirements later on.
> * After any change you make do not forget to click **PUBLISH** on the top right corner.

## Block & Question Naming Conventions
* Your **blocks and questions** should have meaningful, short names that use camel case or snake case (Attention_Check, AttentionCheck)
   * Meaningful short names (like Attention_Check) will be helpful when you download your data, since question names will be column names in your data sheet (e.g., Excel).
   * Do not leave spaces or use special characters (other than '_') in the names since R will have a hard time reading these[^1].
   * You might benefit from creating a document that indexes how each question is labeled on Qualtrics if multiple colleagues are working on the data analysis separately[^2].
 
🚨**Recode Values**🚨
* Make sure to check how Qualtrics coded the values/ choices in your question by clicking “recode values”
* If you forget to do this, always make sure to check what the values were coded as after you download your data set

 
     [^1]: Spaces and special characters are the mortal enemies of R.
     [^2]: This will rescue you from playing "What on earth is variable XG_45b??" six months from now.


