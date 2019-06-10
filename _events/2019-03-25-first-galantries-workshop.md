---
layout: event
title: 'RNA-seq workshop for beginners: from sequences to visualization using Galaxy'
starts: 2019-06-11
ends: 2019-06-12
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
    name: Rechenzentrum
    street: Hermann-Herder-Straße 10
    postal: 79104
    city: Freiburg
    country: Germany
    geo:
        lat: 48.003799
        lon: 7.848305
---

The [Gallantries team]({{ site.baseurl }}{% link team.md %}) is offering its first RNA-seq workshop for beginners on June, 11-12th.

This workshop will cover:
- Galaxy introduction
- Introduction to High-Throughput Sequencing and Quality Control
- Reference-based RNA-seq data analysis

It will be delivered simultaneously at two locations across Europe ([Rotterdam, NL and Freiburg, DE](#venues)).

# Registration

To register, please fill in the [following form](https://forms.gle/K5SXtzg88iug1RgB9).

Each location offers 15 places in total. First come, first serve.

# Program

Every day the workshop will run from 9:00-17:00 (give or take, depending on questions at the end). If the times will change, it will be announced during the workshop.


**Tuesday**

Time | Topic | Material | Speaker
 --- | --- | --- | ---
9:00 - 9:30 | General introduction: introduction round, explaination of sticky notes and hybrid training |[slides](https://training.galaxyproject.org/training-material/topics/instructors/tutorials/workshop-intro/slides.html) | 1 person on each site
9:30 - 10:00 | Introduction to Galaxy | [slides](https://training.galaxyproject.org/training-material/topics/introduction/slides/introduction.html#1) | Helena
10:00 - 12:30 | Galaxy 101 | [tutorial](https://training.galaxyproject.org/training-material/topics/introduction/tutorials/galaxy-intro-101/tutorial.html) | Helena
13:30 - 15:30 | Quality control | [slides](https://training.galaxyproject.org/training-material/topics/sequence-analysis/tutorials/quality-control/slides.html#1), [tutorial](https://training.galaxyproject.org/training-material/topics/sequence-analysis/tutorials/quality-control/tutorial.html) | Mateusz
15:30 - 17:00 | Mapping | [slides](https://training.galaxyproject.org/training-material/topics/sequence-analysis/tutorials/mapping/slides.html#1), [tutorial](https://training.galaxyproject.org/training-material/topics/sequence-analysis/tutorials/mapping/tutorial.html) | Saskia
17:00 - 17:30 | Recap of the day | | 1 person on each site
Evening | Social Dinner | | All sites
{:.table.table-striped}

**Wednesday**

Time | Topic | Material |  Speaker
--- | --- | --- | ---
9:00 - 9:30 | Recap of the previous day | | 1 person on each site
9:30 - 10:00 | Introduction to RNA-Seq | [slides](https://training.galaxyproject.org/training-material/topics/transcriptomics/slides/introduction.html#1) | Fotis
10:00 - 12:30 | Reference-based RNA-seq, part I (QC + mapping) | [tutorial](https://training.galaxyproject.org/training-material/topics/transcriptomics/tutorials/ref-based/tutorial.html) | Fotis
13:30 - 16:30 | Reference-based RNA-seq, part II | [tutorial](https://training.galaxyproject.org/training-material/topics/transcriptomics/tutorials/ref-based/tutorial.html) | Bérénice
17:00 - 17:30 | Recap of the workshop + feedbacks | | 1 person on each site
{:.table.table-striped}

# Important notes

The workshop is free of charge and covers:

- 2 days of training
- Coffee and tea over the days
- Lunch

No stipends for travel or accommodation are available.

Desktop computers will be available. You can also bring your *own notebook* if you prefer . Eduroam is available, ask your institute how to connect.

A **social dinner** will be organised at each site on Tuesday 11 June. This dinner will be at your own cost, but we would love to have a chat with you after the workshop!

# Preparation

The workshop will use the [European Galaxy server](https://usegalaxy.eu) to perform all data analysis. Please register there ahead of time to streamline the training.

You must go through two Galaxy interactive tours before beginning the training.
These interactive tours guide you stepwise through the Galaxy user interface
and the history. They will help you to follow the Galaxy introduction, and
ensure everyone has a basic understanding of how Galaxy works.

- [Galaxy UI](https://usegalaxy.eu/tours/core.galaxy_ui)
- [History Introduction](https://usegalaxy.eu/tours/core.history)

# Venues

This workshop will be offered in parallel in 2 locations (Rotterdam, NL and Freiburg, DE).

## Rotterdam

{% assign loc = page.locations | where:"city", "Rotterdam" | first %}
{% include map.html location=loc showmap=true zoomlevel=15 hidepopup=true %}

The workhop will be held in room 1528 on the 15th floor of the Ee building. Computers are provided in this room. To enter the building you will need to pick up a visitors pass that will be waiting for you at the reception (3rd floor).

## Freiburg

{% assign loc = page.locations | where:"city", "Freiburg" | first %}
{% include map.html location=loc showmap=true zoomlevel=15 hidepopup=true %}

### Travel

Freiburg is easy to reach by train.

From Basel airport to Freiburg, you should take the airport shuttle bus to Freiburg Hauptbahnhof ([Timetable](https://www.freiburger-reisedienst.de/en/airportbus/timetable.php)).

The venue is close to the main station: 10 min walk. Otherwise, you can also use local public transport ([VAG](https://www.vag-freiburg.de/))

### Accomodations

Some suggestions for hotels (please check portals such as [HRS](https://www.hrs.com), [booking](https://www.booking.com/), etc.)

Hotel                                         | Location           | Website
--------------------------------------------- | ------------------ | ----------
Hotel am Rathaus                              | Rathausgasse 4-8   | [Website](http://www.am-rathaus.de/)
Hotel Barbara                                 | Poststrasse 4      | [Website](http://www.hotel-barbara.de/)
Intercity Hotel Freiburg                      | Bismarckallee 3    | [Website](http://de.intercityhotel.com/Freiburg/InterCityHotel-Freiburg)
Stadthotel Freiburg Kolping Hotel & Gästehaus | Karlstr.7          | [Website](http://www.hotel-freiburg.de/)
Ibis Freiburg Süd (bit more far away)         | Bötzinger Str.76   | [Website](http://www.accorhotels.com/de/hotel-2656-ibis-budget-freiburg-sued/index.shtml)
StayInn Hostel und Gästehaus                  | Stühlinger Str.24a | [Website](http://www.stayinn-freiburg.de/hostel-und-gaestehaus/)
{:.table.table-striped}

Note: Sometimes when visiting Freiburg you have to pay an additional accommodation tax. For business trips, this tax does not need to be paid if your employer fills out [this form](http://www.freiburg.de/servicebw/UebernachtungSt_Arbeitgeberbescheinigung.pdf). You will need to show this form at the hotel.

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
- [Dutch Techcenter for Life Sciences](https://www.dtls.nl/)
- [INAB|CERTH](http://inab.certh.gr)
- [Erasmus Medical Center](https://www.erasmusmc.nl)
- [Mozilla foundation](https://foundation.mozilla.org/en/), via a [Mozilla Open Science Mini-Grants](https://foundation.mozilla.org/en/awards/)

