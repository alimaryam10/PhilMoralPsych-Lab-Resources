---
layout: default
title: Data Cleaning 101
parent: Data Analysis Using R
nav_order: 2
---

# Sample Cleaning Script

# Data cleaning checklist

- [ ] Preview/test responses have been removed
- [ ] Participants who were ineligible (because they did not consent or were not old enough to participate) have been removed

  > Note: Normally, we program our surveys to direct participants to the end if they are not eligible, and Prolific does not allow participation if you are not 18, so you won't really have to do anything for this unless you did not program your survey this way or did not use Prolific.

- [ ] Incomplete/partial responses removed (according to what you deemed as "enough" responses in your pre-reg)

  > Note: Normally, we program survey responses to be Force Response, but give people the option to indicate "Prefer not to say" for demographic questions. If you've done things this way, it's unlikely you will have any "incomplete" responses. 

- [ ] Duplicate participants removed (e.g., by Prolific ID — people occasionally complete a study twice)

  > Note: Normally, we would select "Prevent Multiple Submissions" on Prolific, which would avoid this issue. However, if you collected data through social media, this is worth checking.

- [ ] Data has been anonymised, anonymised raw data has been written into a .csv file
- [ ] Qualtrics identifying/metadata columns (e.g., "LocationLatitude", "LocationLongitude") have been removed
- [ ] Column headers renamed to be interpretable
- [ ] 'Prefer not to say' responses coded as NAs
- [ ] Variables have been appropriately coded — categorical variables as factors, numeric variables as numeric
- [ ] Participants who failed attention checks have been removed
- [ ] Sample size before and after exclusions recorded, along with how many exclusions can be attributed to each step
- [ ] Any reverse-coding of items that is required has been done
- [ ] Clean data has been written into a .csv file
