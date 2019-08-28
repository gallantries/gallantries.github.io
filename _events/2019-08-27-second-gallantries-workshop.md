---
layout: event
title: 'RNA-seq workshop for beginners: from sequences to visualization using Galaxy and R'
starts: 2019-10-07
ends: 2019-10-09
locations:
-
    name: Erasmuc MC
    street: Wytemaweg 80
    postal: 3015 CN
    city: Rotterdam
    country: The Netherlands
    geo:
        lat: 51.9108731
        lon: 4.4690001
-
    name: INAB-CERTH
    street: 6th km Charilaou - Thermis rd
    postal: 57001
    city: Thessaloniki
    country: Greece
    geo:
        lat: 40.567925
        lon: 22.997542
---

The [Gallantries team]({{ site.baseurl }}{% link team.md %}) is offering its second RNA-seq workshop for beginners on October 7-9th.

This workshop will cover:
- Galaxy introduction
- Introduction to High-Throughput Sequencing and Quality Control
- Reference-based RNA-seq data analysis
- Basics of R programming
- Post-processing of RNA-seq data using R and Rstudio

It will be delivered simultaneously at multiple locations across Europe ([Rotterdam, NL; Thessaloniki, GR; TODO](#venues)).

# Registration

To register, please fill in the [following form](https://forms.gle/K5SXtzg88iug1RgB9).

Each location offers 15 places. First come, first serve.

# Program

Every day the workshop will run from 9:00-17:00 (give or take, depending on questions at the end). If the times will change, it will be announced during the workshop.


**Monday October 7**

Time | Topic | Material | Speaker
 --- | --- | --- | ---
9:00 - 9:30 | General introduction: introduction round, explaination of sticky notes and hybrid training |[slides](https://training.galaxyproject.org/training-material/topics/instructors/tutorials/workshop-intro/slides.html) | 1 person on each site
9:30 - 10:00 | Introduction to Galaxy | [slides](https://training.galaxyproject.org/training-material/topics/introduction/slides/introduction.html#1) | Helena
10:00 - 12:30 | Galaxy 101 | [tutorial](https://training.galaxyproject.org/training-material/topics/introduction/tutorials/galaxy-intro-101/tutorial.html) | Helena
12:30 - 13:30 | Lunch | | Everybody
13:30 - 15:30 | Quality control | [slides](https://training.galaxyproject.org/training-material/topics/sequence-analysis/tutorials/quality-control/slides.html#1), [tutorial](https://training.galaxyproject.org/training-material/topics/sequence-analysis/tutorials/quality-control/tutorial.html) | Saskia
15:30 - 17:00 | Mapping | [slides](https://training.galaxyproject.org/training-material/topics/sequence-analysis/tutorials/mapping/slides.html#1), [tutorial](https://training.galaxyproject.org/training-material/topics/sequence-analysis/tutorials/mapping/tutorial.html) | Saskia
17:00 - 17:30 | Recap of the day | | 1 person on each site
{:.table.table-striped}

**Tuesday October 8**

Time | Topic | Material |  Speaker
--- | --- | --- | ---
9:00 - 9:30 | Recap of the previous day | | 1 person on each site
9:30 - 10:00 | Introduction to RNA-Seq | [slides](https://training.galaxyproject.org/training-material/topics/transcriptomics/slides/introduction.html#1) | Fotis
10:00 - 12:30 | Reference-based RNA-seq, part I (QC + mapping) | [tutorial](https://training.galaxyproject.org/training-material/topics/transcriptomics/tutorials/ref-based/tutorial.html) | Fotis & Bérénice
12:30 - 13:30 | Lunch | | Everybody
13:30 - 16:30 | Reference-based RNA-seq, part II | [tutorial](https://training.galaxyproject.org/training-material/topics/transcriptomics/tutorials/ref-based/tutorial.html) | Bérénice
17:00 - 17:30 | Recap of the workshop + feedbacks | | 1 person on each site
Evening | Social Dinner | | All sites
{:.table.table-striped}


**Wednesday October 9**

Time | Topic | Material |  Speaker
--- | --- | --- | ---
9:00 - 9:30 | Recap of the previous day | | 1 person on each site
9:30 - 12:30 | Introduction to R programming| [tutorial](TODO) | Mateusz
12:30 - 13:30 | Lunch | | Everybody
13:30 - 16:30 | Post-processing RNA-seq data using R | [tutorial](TODO) | Fotis
17:00 - 17:30 | Recap of the workshop + feedbacks | | 1 person on each site
{:.table.table-striped}


# Important notes

The workshop is free of charge and covers:

- 3 days of training
- Coffee and tea over the days
- Lunch

No stipends for travel or accommodation are available.

Desktop computers will be available. You can also bring your *own notebook* if you prefer . Eduroam is available, ask your institute how to connect.

A **social dinner** will be organised at each site on Tuesday October 8th. This dinner will be at your own cost, but we would love to have a chat with you after the workshop!

# Workshop Format

This will be a **hybrid training**. This means the instructors will teach in front of a camera, and this video feed is live-streamed to multiple locations around the world. Each location will have several other instructors and helpers on site to answer questions and who can take over teaching in case this is needed.

We will use [this collaborative document](http://bit.ly/gallantries-chat) for asking and answering questions during the workshop. This document also contains links to all other materials you will need during the course.

# Preparation

The workshop will use the [European Galaxy server](https://usegalaxy.eu) to perform all data analysis. Please register there ahead of time to streamline the training.

You must go through two Galaxy interactive tours before beginning the training.
These interactive tours guide you stepwise through the Galaxy user interface
and the history. They will help you to follow the Galaxy introduction, and
ensure everyone has a basic understanding of how Galaxy works.

- [Galaxy UI](https://usegalaxy.eu/tours/core.galaxy_ui)
- [History Introduction](https://usegalaxy.eu/tours/core.history)

# Venues

This workshop will be offered in parallel in multiple locations (Rotterdam, NL; Thessaloniki, GR and TODO).

## Rotterdam

{% assign loc = page.locations | where:"city", "Rotterdam" | first %}
{% include map.html location=loc showmap=true zoomlevel=15 hidepopup=true %}

The workhop will be held in room 1528 on the 15th floor of the Ee building. Computers are provided in this room. To enter the building you will need to pick up a visitors pass that will be waiting for you at the reception of the Ee building (3rd floor).

## Thessaloniki

{% assign loc = page.locations | where:"city", "Thessaloniki" | first %}
{% include map.html location=loc showmap=true zoomlevel=15 hidepopup=true %}

The workshop will take place at the Conference room on the 1st floor of the Institute of Applied Biosciences building. Computers will **not** be available in this room, so you need to bring your own laptop. WiFi access (including `eduroam`) will be available.


# Organizers, instructors and helpers

This event is organized by the [Gallantries team]({{ site.baseurl }}{% link team.md %}):

- Saskia Hiltemann
- Helena Rasche
- Mateusz Kuzak
- Fotis Psomopoulos
- Bérénice Batut

The team will be also instructors and helpers there, in addition to local helpers.

# Sponsors

This event is made possible thanks to our supporting partners:

- [de.NBI](https://www.denbi.de/)
- [Netherlands eScience Center](https://www.esciencecenter.nl)
- [Dutch Techcenter for Life Sciences](https://www.dtls.nl/)
- [INAB CERTH](http://inab.certh.gr)
- [Erasmus Medical Center](https://www.erasmusmc.nl)
- [Mozilla foundation](https://foundation.mozilla.org/en/), via a [Mozilla Open Science Mini-Grants](https://foundation.mozilla.org/en/awards/)

