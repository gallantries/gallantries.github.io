---
layout: handbook
title: Handbook to organize a Gallantries event
---

We're thrilled you've choosen to run a Gallantries event!

We hope this guide will help you navigate the logistics of the event organization. If anything is unclear or you have more questions, feel free to add comments in [GitHub]({{ site.github.repository_url }}/issues/new), or reach out to us [on Gitter](https://gitter.im/galaxy-carpentries/community). We're here to help!

# What is a Gallantries event?

Several recent surveys highlight the need and demand from early-stage researchers for training in management and analysis of their High Throughput Sequencing (HTS) data. Given the gap in the education currently offered by traditional providers, there is a distinct push to create and provide high quality, decentralized, accessible, scalable, and practical training in bioinformatics.

The Gallantries team aims to address this gap by preparing training material for the computational analysis of HTS data, starting from the raw data and leading up to the development of publication ready visualizations of the analyzed results, using the Galaxy platform as the underlying infrastructure. This is a representative training scenario as it covers themes and practices common in the vast majority of data analysis pipelines in life sciences:

1. **User-friendly data analysis in Galaxy**, from the raw sequencing data to the downstream count tables
2. **Downstream analysis & visualisation in Rstudio** with manipulation and visualization of the results within R, including an introduction to R using RStudio

Beyond the curriculum, Gallantries team aims to address the scalability of training delivery via **hybrid training events**, i.e. pairing-up on-site helpers with remote instructors across multiple sites simultaneously:

![Hybrid training diagram, a single remote instructor broadcasts training to multiple sites](assets/images/handbook/hybrid_training.png)

With this model, we aim to bring training events to the trainees while reducing the environmental impact of instructor travel.

# A typical Gallantries hybrid training event

*To illustrate a typical Gallantries event and the different roles (1 person can have several roles), we have decided to share a story with several fictional characters*

**Max** is a training coordinator of an international research consortium. They recently surveyed researchers in the consortium on their need in HTS data analysis. The results were overwhelming: over 60 scientists at the several locations would like to learn how to analyze their own RNA-seq data. To fulfill this demand, Max decided to organize a Gallantries event: a 3-days workshop with 4 different locations simultaneously (Greece, Estonia, France and Spain). Max is the **global organizer** of this event, in charge of finding the date, contact and coordinate with the local hosts, advertize the event, find the instructors, etc. After the event, Max will aggregate all feedback from participants, helpers and hosts and share them.

Max first contacted 4 **local hosts** (1 on each site) One of them is **Imani** based in Greece. Imani is in charge of finding a suitable room (preferably with computers), check the local setup, recruit local helpers, advertize the event locally to participants, organize the local catering and social event. Imani will also make the introduction and wrap-up on each day, and collect feedback from participants.

Imani recruited 2 **local helpers** for each day. One of the helpers, **Casey**,  has some previous experience with RNA-seq data analysis and Galaxy. Before the workshop, they went through the training material and tested it. They help participants during the workshop when they are stuck or get different results than the instructors. They also give direct feedback to the instructor about the pace, possible local issues etc.

Max also recruited 4 **instructors** whose **Farah**. Farah is trained bioinformaticians and experienced instructors giving regularly training to scientists on HTS data analysis. They will teach the morning of the 2nd day (introduction and the frist steps of RNA-seq data analysis). Farah is located in Germany and teaches from a room at their institute in front of their computer. During this teaching morning, they adapt their pace given the feedback they got from the local helpers, check the status of participants job on a dedicated page and also answer questions from participants written on chat.

**Alex** is a PhD student in molecular biology based in Greece. They would like to learn about RNA-seq data analysis to be able to analyze the data they generated. They heard about the workshop and join one site for the workshop close to their institute. As **participant**, Alex actively participates to the workshop by running their first RNA-seq data analysis given the instructor's instructions, asks for help to local helpers when stucks, raises their questions on the participant chat and gives feedback using sticky notes and dedicated feedback forms.

# Curriculum and schedule for an event

A typical Gallantries event covers the computational analysis of HTS data from the raw data to the development of publication ready visualizations of the analyzed results within **3 days** with hands-on training:

- The first day is usually an introduction to Galaxy, quality control and (if time allow it) mapping.
- On the second day, the training covers HTS data analysis, e.g. reference based RNA-seq analysis from raw sequences to differential expression analysis.
- The third day is dedicated to downstream analysis & visualisation of generated results with Rstudio in Galaxy, after an introduction to R.

Every day the workshop usually run from **8:30-10:00** to **17:00-18:30** (give or take, depending on questions at the end). A typical schedule could be:

Time | Topic | Material | Speaker
 --- | --- | --- | ---
**1st day** | |  |
9:00 - 9:30 | General introduction: introduction round, explanation of sticky notes and hybrid training |[slides](https://training.galaxyproject.org/training-material/topics/instructors/tutorials/workshop-intro/slides.html)
9:30 - 10:00  | Introduction to Galaxy | [slides](https://training.galaxyproject.org/training-material/topics/introduction/slides/introduction.html#1) | Local hosts
10:00 - 12:30 | Galaxy 101 | [tutorial](https://training.galaxyproject.org/training-material/topics/introduction/tutorials/galaxy-intro-101/tutorial.html) | One instructor
12:30 - 13:30 | Lunch | |
13:30 - 15:30 | Quality control | [slides](https://training.galaxyproject.org/training-material/topics/sequence-analysis/tutorials/quality-control/slides.html#1), [tutorial](https://training.galaxyproject.org/training-material/topics/sequence-analysis/tutorials/quality-control/tutorial.html) | One instructor
15:30 - 17:00 | Mapping | [slides](https://training.galaxyproject.org/training-material/topics/sequence-analysis/tutorials/mapping/slides.html#1), [tutorial](https://training.galaxyproject.org/training-material/topics/sequence-analysis/tutorials/mapping/tutorial.html) | One instructor
17:00 - 17:30 | Recap of the day | | Local hosts
**2nd day** | |  |
9:00 - 9:30 | Recap of the previous day | | Local hosts
9:30 - 10:00 | Introduction to RNA-Seq | [slides](https://training.galaxyproject.org/training-material/topics/transcriptomics/slides/introduction.html#1) | One instructor
10:00 - 12:30 | Reference-based RNA-seq, part I (QC + mapping) | [tutorial](https://training.galaxyproject.org/training-material/topics/transcriptomics/tutorials/ref-based/tutorial.html) | One instructor
12:30 - 13:30 | Lunch | |
13:30 - 17:00 | Reference-based RNA-seq, part II (Differentail expression analysis) | [tutorial](https://training.galaxyproject.org/training-material/topics/transcriptomics/tutorials/ref-based/tutorial.html) | One instructor
17:00 - 17:30 | Recap of the workshop + feedbacks | | Local hosts
Evening | Social Dinner | | All sites
**3rd day** | |  |
9:00 - 9:30 | Recap of the previous day | | Local hosts
9:30 - 10:30 | Introduction to RStudio in Galaxy | [tutorial](TODO) | One instructor
10:30 - 12:30 | Introduction to R programming| [tutorial](TODO) | One instructor
12:30 - 13:30 | Lunch | |
13:30 - 17:00 | Post-processing RNA-seq data using R | [tutorial](TODO) | One instructor
17:00 - 17:30 | Recap of the workshop + feedbacks | | Local hosts
{:.table.table-striped}

**Breaks** (10-15 minutes, with ideally drinks and snacks) are recommanded every hour to help participants to stay focus and let instructors to rest a bit. Breaks are difficult to pre-schedule, but could be done while a tool is running or if there is any technical issues.

Different time zones

# Cost of an event

With hybrid training model, the cost to organize and participate to workshop are minimized: the instructors do not need to travel to the venue and the event can be the closest as possible to participants (e.g. in their institute).

We recommend to the local hosts to organize drinks and coffee for the breaks and if possible lunch. This will be the main costs of such event.

To cover them, local hosts could ask for a small participation fee. This will also increase the number of registered participants showing up.

# Workshop Checklists

To help you organize a Gallantries event, we have created some checklists, by timing but also [by role](#checklists-by-role). Most of the items in these checklists are not specific to Gallantries events.

## Before the workshop

### Global organizers

{% include handbook/organizer-before.md %}

### Local hosts

{% include handbook/host-before.md %}

### Local helpers

{% include handbook/helper-before.md %}

### Instructors

{% include handbook/instructor-before.md %}

## During the workshop

Templates for chat
How chat works
emphasize communication between helpers
put sticky notes there quickly

### Global organizers

{% include handbook/organizer-during.md %}

### Local hosts

{% include handbook/host-during.md %}

### Local helpers

{% include handbook/helper-during.md %}

### Instructors

{% include handbook/instructor-during.md %}

## After the workshop

Debrief
    Sticky notes collection from sites
    share experience back: feedback from sites (extract form from issue in github)
    form feedback from instructors + helpers

### Global organizers

{% include handbook/organizer-after.md %}

### Local hosts

{% include handbook/host-after.md %}

### Local helpers

{% include handbook/helper-after.md %}

### Instructors

{% include handbook/instructor-after.md %}

# Checklists by role

## Global organizers

### Before the workshop

{% include handbook/organizer-before.md %}

### During the workshop

{% include handbook/organizer-during.md %}

### After the workshop

{% include handbook/organizer-after.md %}

## Local hosts

### Before the workshop

{% include handbook/host-before.md %}

### During the workshop

{% include handbook/host-during.md %}

### After the workshop

{% include handbook/host-after.md %}

## Local helpers

### Before the workshop

{% include handbook/helper-before.md %}

### During the workshop

{% include handbook/helper-during.md %}

### After the workshop

{% include handbook/helper-after.md %}

## Instructors

### Before the workshop

{% include handbook/instructor-before.md %}

### During the workshop

{% include handbook/instructor-during.md %}

### After the workshop

{% include handbook/instructor-after.md %}

# Templates

- [Event webpage](https://github.com/galaxy-carpentries/workshop-template)
- [Registration form](https://docs.google.com/forms/d/1mWl34vyXyhO-M9rwrrF0I-Kb2clSW0QHOiFTauweWv8)
- [Certificates](https://docs.google.com/document/d/1SxvGyST4o5vevosj9H7s3EFnaJwl3Q1up9xPUZRu3r4/edit?usp=sharing)
- Starting slides
- [Collaborative document to collect questions from participants and document answers](https://drive.google.com/open?id=1tN247JWpkpPl7FvEN9gsBcmVlZfRF_B0gnEWb5L3tMc)
- [Instructors - Helpers Chat](https://docs.google.com/document/d/1X8V_frzVd5N87zaZ7PDCvtSZozaj8XnrYj9K6Ux9i_0/edit?usp=sharing)
- Wrap up slides for daily recap
- Wrap up slides for the end of the workshop
- Feedback form for participants
- Feedback form for helpers, hosts, instructors

# Conclusion

We hope this guide gave you an overview of how to organize a Gallantries event, and will help you manage the logistics of the event organization.

# References

The checklists has been adapted and extended from [Galaxy](https://training.galaxyproject.org/training-material/topics/instructors/tutorials/organize-workshop/tutorial.html) and [The Carpentries](https://docs.carpentries.org/topic_folders/hosts_instructors/hosts_instructors_checklist.html) workshop checklists.
