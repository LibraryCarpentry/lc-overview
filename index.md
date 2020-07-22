---
layout: lesson
root: .  # Is the only page that don't follow the partner /:path/index.html
permalink: index.html  # Is the only page that don't follow the partner /:path/index.html
---

Library Carpentry aims to teach people working in library- and information-related roles how to automate tasks; create, maintain, and analyze sustainable and reusable data; work effectively with IT and systems colleagues; and better understand the use of software in research. Training takes place mainly in face-to-face workshops. To learn more about our workshops, see [The Carpentries Handbook](https://docs.carpentries.org/).

> ## Audience
>
> Library Carpentry lessons are for people working in library- and information-related roles. See [Our Audience](https://librarycarpentry.org/audience/) and [Our Learner Profiles (Draft)](https://github.com/LibraryCarpentry/lc-overview/blob/gh-pages/files/learner-profiles.md) for more information.
{: .prereq}

> ## Prerequisites & Tools
>
> There are no prerequisites, and the materials assume no prior knowledge about the tools.
{: .prereq}

> ## Data
> 
> The data used in this workshop include bibliographic metadata and text-based data. See each lesson for the specific datasets and sources used.
{: .prereq}

> ## License
> 
> Lesson materials are all available online, under a CC BY license, for self-directed study or for adaptation and re-use (as "Carpentries-based" training).
{: .prereq}

# Workshop Structure

## Parts vs Days
Feedback from the Library Carpentry community has highlighted the effectiveness of offering greater flexibility in the delivery of Library Carpentry training. Specifically, individuals in library- and information-related roles noted that it is often difficult to get two consecutive days off for training. To address this barrier to participation, Library Carpentry may be run in half-day blocks, rather than as a two-day contiguous training. This flexibility also supports collaborating with the community and host/organiser to best suit their situation. 

Instead of requiring “Days” like Data Carpentry or Software Carpentry, “Parts” are used to allow for the flexibility desired by the Library Carpentry community. If a standard workshop (which includes three of the four core lessons) cannot be held across two consecutive days, then alternatively, it can be run in parts across a number of days. As long as three of the four core lessons are taught, it makes no difference whether the workshop is run in one day, two days, or multiple days.

Based on the feedback from Library Carpentry (and the greater Carpentries) community, The Carpentries is doing more to include flexibility in the organisation of workshops. See [Upcoming Updated Forms for Workshops & Workshop Section of The Carpentries Website](https://carpentries.org/blog/2019/08/workshop-request-form-updates-teaser/).

## Curricula
In response to [strengthening the LC community](https://software.ac.uk/blog/2019-07-26-strengthening-library-carpentry-community), the Curriculum Advisory Committee has been exploring [the addition of new and popular curricula](https://github.com/LibraryCarpentry/governance/issues/14). The table below includes two new curricula beyond the standard workshop. As more lessons reach the stable status, we will include the new curricula in [The Carpentries workshop request form](https://amy.carpentries.org/forms/workshop/) and [LC lessons](https://librarycarpentry.org/lessons/).

Curriculum | Description | Lesson menu | Total time estimated
-- | -- | -- | --
Library Carpentry Standard Workshop | Core lessons | 1) [Introduction to Working with Data](https://librarycarpentry.org/lc-overview/), 2) [The Unix Shell](https://librarycarpentry.org/lc-shell/), 3) [Introduction to Git](https://librarycarpentry.org/lc-git/), 4) [OpenRefine](https://librarycarpentry.org/lc-open-refine/) Note: A standard workshop must include three of the four lessons | 2 days
Library Carpentry Introduction | A good combination for pilots and workshops connected with conferences and other events | 1) [Introduction to Library Carpentry](https://librarycarpentry.org/lc-overview/02-intro-to-library-carpentry/index.html), 2) [OpenRefine](https://librarycarpentry.org/lc-open-refine/) | Half day
Library Carpentry Data Analysis Core | An introduction to data analysis and good practices including versioning, cleaning, automation, manipulation, and structured queries | 1) [Introduction to Git](https://librarycarpentry.org/lc-git/), 2) [The Unix Shell](https://librarycarpentry.org/lc-shell/), 3) [OpenRefine](https://librarycarpentry.org/lc-open-refine/), 4) [SQL](https://librarycarpentry.org/lc-sql/) | 2 days
Custom | Design your own workshop to suit your local needs | Select from [https://librarycarpentry.org/lessons/](https://librarycarpentry.org/lessons/) | Estimate total time from lesson schedules e.g. [https://librarycarpentry.org/lc-shell/](https://librarycarpentry.org/lc-shell/)

## Core Lessons
For a standard Library Carpentry workshop, three of the four parts below must be taught in addition to having at least one certified Carpentries instructor teach the workshop. Alternatively, a Library Carpentry-based workshop can be considered, where part(s) of the core lessons are combined with the extended lessons to suit the needs of the community. 

### Part 1: Introduction to Working with Data

The lesson begins with a question and answer activity that allows participants to explore concepts or jargon around software development and data science. Then, the reasons behind why taking a computational approach is beneficial are covered. The latter half of the lesson explores regular expressions or pattern matching to find, manage, and transform data and files.

* [Jargon Busting](https://librarycarpentry.org/lc-overview/03-jargon-busting/index.html) [(GitHub Repository)](https://github.com/LibraryCarpentry/lc-overview)
* [A Computational Approach](https://librarycarpentry.org/lc-overview/04-computational-approach/index.html) [(GitHub Repository)](https://github.com/LibraryCarpentry/lc-overview)
* [Introduction to Working with Data (Regular Expressions)](https://librarycarpentry.github.io/lc-data-intro/) [(GitHub Repository)](https://github.com/LibraryCarpentry/lc-data-intro)
  
The following lesson episodes are optional:

* [Introduction to Library Carpentry](https://librarycarpentry.org/lc-overview/02-intro-to-library-carpentry/index.html) [(GitHub Repository)](https://github.com/LibraryCarpentry/lc-overview): For learners looking for an introduction to Library Carpentry and The Carpentries, for instance, as part of a shorter, pilot workshop (in connection with an event), or as a presentation at an event or to a community. 

* [Keyboard Shortcuts](https://librarycarpentry.org/lc-overview/05-keyboard-shortcuts/index.html) [(GitHub Repository)](https://github.com/LibraryCarpentry/lc-overview): Introduce learners to keyboard shortcuts that will be used in the lesson and other lessons while learning that keyboard shortcuts are useful in automating tasks. A question and answer exercise allows workshop participants to learn from each other about new keyboard shortcuts.

* [File Naming & Formatting](https://librarycarpentry.org/lc-overview/06-file-naming-formatting/index.html) [(GitHub Repository)](https://github.com/LibraryCarpentry/lc-overview): Introduce learners to good practices for file naming and organisation, open file formats such as Markdown, and open source software for working with open file formats. The Markdown exercise allows learners to gain experience using it ahead of lessons that include working with regular expressions and git. 

* [One Up, One Down](https://librarycarpentry.org/lc-overview/07-one-up-down/index.html) [(GitHub Repository)](https://github.com/LibraryCarpentry/lc-overview): Activity where the instructor alternates between each workshop participant asking them what they liked about the workshop or what needs improvement. Participants cannot repeat responses. Allows both instructors and participants an opportunity to reflect on the workshop (day).

* [Further Reading](https://librarycarpentry.org/lc-overview/08-further-reading/index.html) [(GitHub Repository)](https://github.com/LibraryCarpentry/lc-overview): Resources on computational approaches in libraries.

### Part 2: The UNIX Shell

This lesson includes information on navigating/working with files and directories, scripting, and finding things on the command line (shell).

  * [The UNIX Shell](https://librarycarpentry.github.io/lc-shell/) [(GitHub Repository)](https://github.com/LibraryCarpentry/lc-shell)

### Part 3: Introduction to Git

This lesson introduces git on the command line and moves to using GitHub to collaborate, manage, version, and share your project or repository work.

  * [Introduction to Git](https://librarycarpentry.github.io/lc-git/) [(GitHub Repository)](https://github.com/LibraryCarpentry/lc-git)

### Part 4: OpenRefine

This lesson introduces OpenRefine, a software program that helps with transforming, cleaning, filtering, and analysing data files.

  * [OpenRefine](https://librarycarpentry.github.io/lc-open-refine/) [(GitHub Repository)](https://github.com/LibraryCarpentry/lc-open-refine)

## Wrapping Up a Workshop

You might wish to include an activity to wrap up the workshop to improve learners' satisfaction and to help them set goals to use what they have learned. It can be especially helpful if they are tired after the challenges at the end of OpenRefine.

Some suggestions include:

1. **Think-pair-share**: Ask learners to think about what the most valuable thing they learned from the workshop, then share it with their neighbor. This only takes a few minutes but still provides a clear end-point to the event.
2. **Increasing likelihood**: Ask learners to set a goal, then ask how likely they are to undertake that goal (eg 50,70, 90%), and what would it take to make that likelihood 100%. Learners could start to identify their own behaviours and support from colleagues/supervisors that could help them towards achieving that goal.
3. **Now-next-later**: Ask learners to write some action plans for themselves, something they will do in the next two weeks, and/or something they will do in the next three months. This will give them some commitment to apply what they have learned in their job and continue embedding it into their practice. If learners share these with the room, the instructor can capture them in the Etherpad. 

# Beyond the Standard Workshop

When requesting a workshop from The Carpentries, staff will assist with the logistics surrounding a standard workshop (three of the four core lessons). Anything outside of the standard offering is a self-organised workshop, meaning, you are responsible for the organisation. This includes finding instructors (you can reach out to several venues listed under [Library Carpentry Contact](https://librarycarpentry.org/contact/) and the [Discuss Library Carpentry Topicbox](https://carpentries.topicbox.com/groups/discuss-library-carpentry) reaches the most people) and reimbursing their travel. You will also be responsible for setting up the [workshop website](https://github.com/carpentries/workshop-template), registration, and other items referenced in the [Handbook](https://docs.carpentries.org/).

Recently, the [Curriculum Advisory Committee (CAC)](https://librarycarpentry.org/cac/) voted to expand the standard workshop offering to include two new curricula beyond the standard workshop (please see the Curricula table above). As more lessons reach the stable status, we will include the new curricula in [The Carpentries workshop request form](https://amy.carpentries.org/forms/workshop/) and [LC lessons](https://librarycarpentry.org/lessons/).

# Extended Lessons

There are a number of extended Library Carpentry lessons, in alpha, beta, and stable form, that are used to supplement and tailor workshops to the local needs of the community being taught. The lessons include:

  * [SQL](https://librarycarpentry.github.io/lc-sql/) [(GitHub Repository)](https://github.com/LibraryCarpentry/lc-sql)
  * [Webscraping](https://librarycarpentry.github.io/lc-webscraping/) [(GitHub Repository)](https://github.com/LibraryCarpentry/lc-webscraping)
  * [Tidy Data](https://librarycarpentry.github.io/lc-spreadsheets/) [(GitHub Repository)](https://github.com/LibraryCarpentry/lc-spreadsheets)
  * [Introduction to Python](https://librarycarpentry.github.io/lc-python-intro/) [(GitHub Repository)](https://github.com/LibraryCarpentry/lc-python-intro)
  * [Introduction to Data (for Archivists)](https://librarycarpentry.github.io/lc-data-intro-archives/) [(GitHub Repository)](https://github.com/LibraryCarpentry/lc-data-intro-archives)
  * [Top 10 FAIR Data & Software Things](https://librarycarpentry.github.io/Top-10-FAIR/) [(GitHub Repository)](https://github.com/LibraryCarpentry/Top-10-FAIR)

# Conceptual Lessons

In addition, the following lessons are conceptual (pre-alpha) and still in a design phase where community members are discussing them and/or lesson development is still in an early phase:

  * [Wikidata](https://librarycarpentry.github.io/lc-wikidata/) [(GitHub Repository)](https://github.com/LibraryCarpentry/lc-wikidata)
  * [FAIR Data & Software](https://librarycarpentry.github.io/lc-research-data/) [(GitHub Repository)](https://github.com/LibraryCarpentry/lc-research-data)
  * [R](https://librarycarpentry.github.io/lc-r/) [(GitHub Repository)](https://github.com/LibraryCarpentry/lc-open-refine)
  * [MarcEdit](https://librarycarpentry.github.io/lc-marcedit/) [(GitHub Repository)](https://github.com/LibraryCarpentry/lc-marcedit)
  * [OCR/Text & Data Mining](https://librarycarpentry.github.io/lc-ocr/) [(GitHub Repository)](https://github.com/LibraryCarpentry/lc-ocr)
  
