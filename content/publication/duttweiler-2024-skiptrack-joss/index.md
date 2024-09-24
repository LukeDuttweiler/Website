---
title: 'skipTrack: An R package for Identifying Skips in Self-Tracked Mobile Menstrual
  Cycle Data'
authors:
- Luke Duttweiler
- Shruthi Mahalingaiah
- Brent Coull
date: '2024-09-16'
publishDate: '2024-09-24T16:25:37.578108Z'
publication_types:
- article-journal
publication: '*Journal of Open Source Software*'
abstract: Mobile apps that allow users to self-track menstrual cycle lengths and symptoms are now widely available and frequently used. Multiple studies have taken advantage of these uniquely large data sets to gain insight on characteristics of the menstrual cycle, which is an important vital sign. Due to the self-reported nature of the gathered data, recorded cycle lengths may be inflated if users skip tracking any cycle related bleeding events in the app. A non-trivial number of incorrectly inflated cycle lengths in a data set will be damaging to the reliability and reproducibility of analysis results. Current solutions to this problem of non-adherence (skipped tracking) in cycle length reporting include removing implausibly long cycles that exhibit no user-app interaction, identifying possibly inaccurate cycles based on user-specific average cycle lengths, or *ad hoc* removal of cycles based on well-established menstrual cycle characteristics such as average cycle length or cycle length difference. The 'skipTrack' package implements a Bayesian hierarchical model that is the first to explicitly use information on both an individual's cycle length **and** regularity to identify errors in recorded cycle lengths that arise from user non-adherence in logging one or more bleeding events.
---
