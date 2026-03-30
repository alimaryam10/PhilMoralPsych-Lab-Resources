---
layout: default
title: Preregistration
parent: Post Setup Instructions
nav_order: 2
---
# Why make a pre-registration?
Pre-registrations are time-stamped, publicly documented plans that outline how a study will be conducted. They typically include information on your research questions, hypotheses, materials, methodology, and planned analyses. The point of pre-registrations is to reduce questionable research practices (QRPs) like HARKing (hypothesising after results are known) and p-hacking (testing multiple analyses until statistically significant results are found). To learn more about the why and how of pre-registrations, have a read of [this article](https://myscp.onlinelibrary.wiley.com/doi/10.1002/jcpy.1208). 

# How to make a pre-registration?

## Types of Pre-registration
There are two main types of pre-registrations:
* **Exploratory pre-registrations:** appropriate when your study is relatively novel and you are not yet in a position to make firm directional predictions. These can still be valuable — committing to your design, measures, and analysis plan in advance reduces researcher degrees of freedom even without specific hypotheses (as long as you are transparent about this in the write-up). Don't feel pressure to over-constrain yourself here: a minimally constraining exploratory pre-registration is better than none at all. 
* **Directional pre-registrations:** more appropriate when prior literature is sufficient to justify specific, directional hypotheses — for instance, predicting not just that two conditions will differ, but which will yield higher ratings on a DV item. These are generally considered more rigorous, because they commit you to a predicted direction in advance and make it harder to reframe a null or unexpected result as consistent with your hypothesis after the fact.

## Platforms
The lab uses two main platforms for uploading pre-registrations. They are
1. [The Open Science Framework (OSF)](https://osf.io)
* OSF is typically preferred since it's more widely used and gives you more options (e.g., more pre-registration templates, more freedom with how you organise your materials and files)
* [This page](https://help.osf.io/article/330-welcome-to-registrations) gives step-by-step instructions for navigating the platform, creating, and uploading a pre-registration
* Note that there are many pre-registration templates available on the OSF. We've typically used the As.Predicted template, as it is only 9 questions and relatively straightforward and well-suited to a vignette survey study. Visit the following links for some example pre-registrations Joanna has written using this template https://osf.io/pcr8j/overview, https://osf.io/r8mjh/overview.
* If you have a study design that isn't particularly well-suited to this template (e.g., a systematic review/ secondary data analysis), you can visit [this guide](https://www.cos.io/blog/choosing-preregistration-template-guide-for-researchers) on how to find the right OSF pre-registration template.
* During the final submission stage, select "enter the registration under embargo" and set the embargo period to four years — the maximum OSF allows. This creates a timestamped record proving you pre-registered before data collection but keeps your pre-registration privately hidden until you choose to make it public or the embargo expires. The main reason for doing this is that when you're ready to submit for peer review, you can generate a view-only link that gives reviewers access to the pre-registration while preserving your anonymity during blind review.
Even if you're unsure whether you'll publish, it's worth going through this process at least once, both to understand how it works and to have the record in place if you later decide you want to publish.

2. [AsPredicted](https://aspredicted.org)
* As.Predicted is another great, but comparatively limited site. It only provides one pre-registration template.
* You can share your data and code on the site by creating a ResearchBox, which automatically organises your files into a standardized "Bingo table" (see an example [here](https://researchbox.org/15)) 
* As.Predicted keeps your pre-registration private by default for however long you want until you choose to make it public, rather than imposing a 4-year limit like the OSF. It also allows you to automatically generate a link to an anonymised PDF version of your pre-registration for reviewers.

## FAQs

### Do pilots need to be pre-registered?
One thing to remember is that the purpose of a pilot study is to assess the feasibility of your study, not to scope whether you will find an effect. Provided this is the purpose of your pilot, you do not need to pre-register it. If your pilot returns interesting data that you wish to include in your study, make sure to transparently state that your pilot was not pre-regsitered.

### What if I need to deviate from my pre-registration?
It's not uncommon for people to deviate from their pre-registration (their pre-registered analyses in particular). [This article](https://online.ucpress.edu/collabra/article/10/1/117094/200749) by Daniel Lakens describes how to ensure you are deviating for principled reasons and how to explain these deviations. Aside from noting deviations as footnotes in your thesis and/or publication, you can also transparently document deviations on whichever repository system you decide to use. If using OSF, you can use their "update" feature to make notes on your pre-registration regarding your deviations. If using a different repository system, you can also upload a document detailing your deviations and justifications for them. 

## Some advice on pre-registering your analyses
The planned analyses section of your pre-registration is especially important. Because many statistical methods can test the same hypothesis and return a range of different results, failing to plan your approach in advance opens the door to p-hacking, even unintentionally.
That said, pre-registering analyses is genuinely difficult. Researchers vary widely in how much detail they include, and the goal is to strike a balance: too much detail risks committing yourself to decisions that won't make sense once you see the data; too little defeats the purpose. A few things to consider:

**1. Be precise about how your analysis method will help you answer your hypothesis.**
Don't just name the test, explain what inferences you hope to draw from it. For example, if you include a manipulation check, specify what values would constitute a successful manipulation and how you'll handle cases where the check fails. Let's take for example, a study where I'm manipulating an AI agent to be more anthropomorphic to assess its subsequent effects on trust and include a manipulation check to assess whether participants in the anthropomorphic condition did in fact see the agent as more humanlike than those in the control condition.

❌ "I will run a t-test to assess whether participants in the anthropomorphic condition found the AI agent more humanlike than participants in the control condition." <br>
✅ "I will run an independent-samples t-test comparing humanlikeness ratings between the anthropomorphic and control conditions. I will consider the manipulation successful if participants in the anthropomorphic condition rate the agent as significantly more humanlike (p < .05), with at least a small-to-medium effect size (d ≥ 0.3), consistent with previous anthropomorphism manipulations (e.g., Złotowski et al., 2015)."

**2. (Where possible) Specify anticipated effect sizes, not just significance thresholds.**
Where possible, include an estimated effect size (e.g., d = 0.4) alongside your hypothesis. If you’re not already familiar with what effect sizes represent—and why they add more value than significance testing alone, it's worth reading up on them [here](https://www.simplypsychology.org/effect-size.html) first. That said, this is only appropriate when you have sufficient justification for an estimate. If your study closely replicates prior work, is grounded in a body of similar studies, or follows a pilot study, you are in a strong position to specify an anticipated effect size and in those cases, you should. Specifying one also forces you to think carefully about statistical power. Without a target effect size, you cannot meaningfully determine whether your sample is large enough to detect the effect you're looking for.

**3. (Where possible) Write your cleaning and analysis script before collecting data.**
This is one of the best ways to anticipate whether a certain analysis approach makes sense for your data structure. There are two practical ways to do this. If you have pilot data, use it. If not, Qualtrics allows you to generate simulated responses (see [instructions here](https://www.qualtrics.com/support/survey-platform/survey-module/survey-tools/generating-test-responses/)]), export the data, and use it to write your cleaning and analysis scripts in full.
It's important to note that this may be impractical for timing reasons and not every analysis lends itself to this approach — for more complex models such as mixed-effects models, pre-specifying every parameter may be impractical since you may run into convergence issues later which will require you to drop certain terms. In those cases, try to find pre-registrations that others have written using similar analysis methods. 

**For more on how to (properly) pre-register your study, read [this excellent article](http://datacolada.org/64)**
  
## 💡 Tips
* When preregistering a sample size, consider adding a 10-15% buffer in anticipation of exclusions to meet your sample size.
  >* Here's an example of how to phrase this: *"Anticipating exclusions, we'll recruit 400 (or 100 participants per condition)."*
* Be detailed - for example, when describing your DVs, include the full items and rating scale.
* Don't forget to set your alpha - we conventionally set this to .05 for Null Hypothesis Significance Testing (NHST).



