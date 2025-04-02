---
layout: default
title: Question Behaviour
parent: Getting Started
nav_order: 7
---

# Question Behaviour

> *How your questions behave can be an important part of your study - for example, if you include 'request response',
> you can prompt participants to respond to quetions they might have missed. Similarly, consent questions must have a 'force response' because
> you cannot run an experiment without participants' consent*

## Response Requirements

After adding each question to your survey, consider whether to implement response requirements:

* Force Response: Makes answering the question mandatory. Participants cannot proceed until they provide an answer.
* Request Response: Shows a reminder when a participant attempts to skip a question, but allows them to proceed without answering if they choose to.

> 💡 **Best Practices:**
>* Choose response requirements based on your research ethics approval and experimental design needs.
>* **Do not** use Force Response or Request Response for attention check questions, as this defeats their purpose of identifying inattentive participants.
>* Consider participant fatigue and dropout rates when making questions mandatory.
>* For sensitive questions, include a "Prefer not to answer" option (e.g., for demographic questions).

## Page Breaks

* Preview question blocks regularly during survey design to check the flow and organization.
* Add necessary page breaks within question blocks to:
  >* Group related questions together
  >* Prevent overwhelming participants with too many questions on a single page
  >* Control the timing of question presentation
  >* Implement display logic that depends on page transitions

* If you intentionally want all questions to appear on one page, you can skip adding page breaks.

## Question Logic

* When implementing question logic (display logic, skip logic, branch logic, etc.):
  >* Triple-check that your logic works correctly for all experimental conditions.
* Ensure that your question logic isn't being overridden by:
  >* Block-level logic
  >* Survey flow conditions
  >* Quotas
  >* Other conflicting logic rules
* Test your survey with different response patterns to verify all logic paths work as expected.
* Document complex logic implementations for future reference.


