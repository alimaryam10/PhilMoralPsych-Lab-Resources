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
  > Note: Normally, we program our surveys to direct participants to the end if they are not eligible, and Prolific does not allow participation if you are not 18, so there's little manual work here. But it's worth checking, just in case this wasn't how your study was conducted.
- [ ] Incomplete/partial responses removed (according to what you deemed as "enough" responses in your pre-reg)
- [ ] Duplicate participants removed (e.g., by Prolific ID — people occasionally complete a study twice)
- [ ] Data has been anonymised, anonymised data has been written into a .csv file
- [ ] Qualtrics identifying/metadata columns (e.g., "LocationLatitude", "LocationLongitude") have been removed
- [ ] Column headers renamed to be interpretable
- [ ] 'Prefer not to say' responses coded as NAs
- [ ] Out-of-range/impossible values checked (e.g., an 8 on a 1–7 scale, implausible ages)
- [ ] Variables have been appropriately coded — categorical variables as factors, numeric variables as numeric
- [ ] Participants who failed attention checks have been removed
- [ ] Any reverse-coding of items that is required has been done
- [ ] Missing data pattern checked (systematic vs random), and how it will be handled downstream decided
- [ ] Raw/original data file kept untouched and separate from the cleaned file
- [ ] Clean data has been written into a .csv file
- [ ] Sample size before and after exclusions recorded, along with how many exclusions can be attributed to each step
