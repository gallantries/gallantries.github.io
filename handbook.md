---
layout: handbook
title: Handbook to organize a Gallantries event
---

We're thrilled you choose to run a Gallantries event.

We hope this guide will help you navigate the logistics of the event organization. If anything is unclear or you have more questions, feel free to add comments in [GitHub]({{ site.github.repository_url }}/issues/new), or reach out to us at [{{ site.email|replace:'@','[at]' }}](mailto:{{ site.email }}) directly. We're here to help!

# What is a Gallantries event?

Several recent surveys highlight the need and demand from early-stage researchers for training in management and analysis of their High Throughput Sequencing (HTS) data. Given the gap in the education currently offered by traditional providers, there is a distinct push to create and provide high quality, decentralized, accessible, scalable and practical training in bioinformatics.

The Gallantries team aims to address this gap by preparing training material for the computational analysis of HTS data, starting from the raw data and leading up to the development of publication ready visualizations of the analyzed results, using the Galaxy platform as the underlying infrastructure. This is a representative training scenario as it covers themes and practices common in the vast majority of data analysis pipelines in life sciences: 

1. **User-friendly data analysis in Galaxy**, from the raw sequencing data to the downstream count tables
2. **Downstream analysis & visualisation using Rstudio in Galaxy** with manipulation and visualization of the results within R, including an introduction to R using RStudio

Beyond the curriculum, Gallantries tema aims to address the scalability of training delivery via **hybrid training events**, i.e. pairing-up on-site helpers with remote instructors across multiple sites simultaneously:

![](assets/images/handbook/hybrid_training.png)

# A typical Gallantries hybrid training event

*To illustrate a typical Gallantries event and the different roles (1 person can have several roles), we decided to share a story with personna*

**Max** is a training coordinator of an international research consortium. They recently surveyed researchers in the consortium on their need in HTS data analysis. The results were overwhelming: over 60 scientists on several locations would like to learn how to analyze their own RNA-seq data. To fulfill this demand, Max decided to organize a Gallantries event: a 3-days workshop with 4 different locations simultaneously (Greece, Estonia, France and Spain). Max is the **global organizer** of this event, in charge to find the date, contact and coordinate with the local hosts, advertize the event, find the instructors, etc. After the event, Max will aggregate all feedback from participants, helpers and hosts and share them.

Max first contacted 4 **local hosts** (1 on each site) whose **Imani** in Greece. Imani is in charge to find a fitting room (preferably with computers), check the local setup, recruite local helpers, advertize the event locally for participants, organize the local catering and social event. Imani will also make the introduction and wrap-up each days, collect feedback from participants.

Imani recruited 2 **local helpers** per day whose **Casey**. **Casey** has some previous experience with RNA-seq data analysis and Galaxy. Before the workshop, they went through the training material and tested it. They helps participants during the workshop when they are blocked or got different results than the instructors. They also gives direct feedback to the instructor about the pace, the possible local issues, etc.

Max also recruited 4 **instructors** whose **Farah**. Farah is trained bioinformaticians and experienced instructors giving regularly training to scientists on HTS data analysis. They will teach the morning of the 2nd day (introduction and the frist steps of RNA-seq data analysis). Farah is located in Germany and teaches from a room at their institute in front of their computer. During this morning, they adapt their pace given the feedback they got from the local helpers, check the status of participants job on a dedicated page and also answer questions from participants written on chat.

**Alex** is a PhD student in molecular biology based in Greece. They would like to learn about RNA-seq data analysis to be able to analyze the data they generated. They heard about the workshop and join one site for the workshop close to their institute. As **participant**, Alex actively participates to the workshop by running their first RNA-seq data analysis given the instructor's instructions, asks for help to local helpers when stucks, raises their questions on the participant chat and gives feedback using sticky notes and dedicated feedback forms.

# Curriculum for an event

Example of a schedule

# Organizing an event

*These checklists have been adapted and extended from [Galaxy](https://training.galaxyproject.org/training-material/topics/instructors/tutorials/organize-workshop/tutorial.html) and [The Carpentries](https://docs.carpentries.org/topic_folders/hosts_instructors/hosts_instructors_checklist.html) workshop checklists (see the referen

## Before the workshop

Different viewpoints
Instructor + helpers should meet ahead of time (local)
testing technical infrastructure
audio issues (full vs empty room), hearable at 75% volume (so room to go up if need be)
tiaas
a11y:
    HoH issues (we've had people bring a listener/signer, ask if they need extra chair etc)
    not so concerned with visual a11y, we're dependent on galaxy for that, we can improve GTM but if you can't use galaxy after, it is pointless
    inclusivity (CoC)
dietary requirements for lunch
    Introduction (motivation, why hybrid, etc)
        Note from Orgainser + contact
        Introducer the hats with some characters for: Participant / Instructor / Helper / Presenters / Organiser
        the information hierarchy (hybrid organiser talks to site organisers + instructors, insturctors to local helpers)

### Global organizers

{% include handbook/organizer-before.md %}

### Local hosts

{% include handbook/host-before.md %}

### Local helpers

{% include handbook/helper-before.md %}

### Instructors

{% include handbook/instructor-before.md %}

## During the workshop

First day slides with CoC (maybe adapt from GTM ones)
Templates for chat
How chat works
Example detailed schedule
emphasize communication between helpers
start debrief doc on first day, put sticky notes there quickly
drinks / coffee is important

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

# Checklists for the different roles

## Global organizers

*These checklists have been adapted and extended from [Galaxy](https://training.galaxyproject.org/training-material/topics/instructors/tutorials/organize-workshop/tutorial.html) and [The Carpentries](https://docs.carpentries.org/topic_folders/hosts_instructors/hosts_instructors_checklist.html) workshop checklists (see the references)*

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

*This checklist has been adapted and extended from [Galaxy](https://training.galaxyproject.org/training-material/topics/instructors/tutorials/organize-workshop/tutorial.html) and [The Carpentries](https://docs.carpentries.org/topic_folders/hosts_instructors/hosts_instructors_checklist.html) workshop checklists (see the references)*

### Before the workshop

{% include handbook/instructor-before.md %}

### During the workshop

{% include handbook/instructor-during.md %}

### After the workshop

{% include handbook/instructor-after.md %}

# Templates

- feedback forms
- schedule (with 1 + 2 TZs, starting times depend on audience / if they travel.)
- wrap up slides (daily + overall (remind of gitter/help/etc.))
        5 minutes dedicated for filling the feedback + handing out certificates
- chat documents
- event on page (our way of phrasing etc)
    maybe template repo but better idea: just add to our gallantries repo, we give you website/templates/slides/etc.
- certificates
- general feedback of event for participants (e.g. the denbi one)

# Conclusion
