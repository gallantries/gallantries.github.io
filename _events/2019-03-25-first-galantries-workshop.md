---
layout: event
title: 'RNA-seq workshop for beginners: from sequences to visualization using Galaxy and R'
starts: 2019-05-06
ends: 2019-05-08
locations:
- 
    name: Erasmuc MC
    street: Wytemaweg 80
    postal: 3015 CN
    city: Rotterdam
    country: The Netherlands
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

The [Gallantries team]({% link team.md %}) is offering its first RNA-seq workshop for beginners on May, 6-8th.

This workshop will cover:
- Galaxy introduction
- Introduction to High-Throughput sequencing and quality control
- Reference-based RNA-seq data analysis
- Introduction to R
- Manipulation and visualization of the RNA-seq data using R

It will be offered in parallel in 2 [locations (Rotterdam, NL and Freiburg, DE)](#venues).

# Registration

To register, please fill in the [following form](https://forms.gle/K5SXtzg88iug1RgB9).

Each location offers 15 places in total. First come, first serve.

# Program

Every day the workshop will run from 9:00-17:00 (give or take, depending on questions at the end). If the times will change, it will be announced during the workshop.

Day | Topics
--- | ---
Monday  | Galaxy introduction, Introduction to High-Throughput sequencing and quality control
Tuesday | Reference-based RNA-seq data analysis
 | **Evening**: social dinner
Wednesday | Introduction to R, Manipulation and visualization of the RNA-seq data using R
{:.table.table-striped}

# Important notes

The workshop is free of charge and covers:

- 3 days of training
- Coffee and tea over the days
- Lunch

No stipends for travel or accommodation are available.

Desktop computers will be available. You can also bring your *own notebook* if you prefer . Eduroam is available, ask your institute for how to login.

# Preparation

The workshop will be performed on the [European Galaxy server](https://usegalaxy.eu) to perform the analysis. Please register there.

You must go through two Galaxy interactive tours before beginning the training.
These interactive tours guide you stepwise through the Galaxy user interface
and the history. They will help you to follow the Galaxy introduction, and
ensure everyone has a basic understanding of how Galaxy works.

- [Galaxy UI](https://usegalaxy.eu/tours/core.galaxy_ui)
- [History Introduction](https://usegalaxy.eu/tours/core.history)

# Venues

This workshop will be offered in parallel in 2 locations (Rotterdam, NL and Freiburg, DE).

## In Rotterdam

{% assign loc = page.locations | where:"city", "Rotterdam" | first %}
{% include map.html location=loc showmap=true zoomlevel=15 hidepopup=true %}

### Travel

### Accomodations

## In Freiburg

{% assign loc = page.locations | where:"city", "Freiburg" | first %}
{% include map.html location=loc showmap=true zoomlevel=15 hidepopup=true %}

### Travel

Freiburg is easy to reach by train.

From Basel airport to Freiburg, you should take the airport shuttle bus to Freiburg Hauptbahnhof ([Timetable](https://www.freiburger-reisedienst.de/en/airportbus/timetable.php)).

The venue is close to the main station: 10 min walk. Otherwise, you can also use local public transport ([VAG](https://www.vag-freiburg.de/))

### Accomodations

Some suggestions for hotels (please check portals such as HRS, booking, etc.)

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

This event is organized by the [Gallantries team]({% link team.md %}):

- Saskia Hiltemann
- Helena Rasche
- Mateusz Kuzak
- Fotis Psomopoulos
- Bérénice Batut

The team will be also instructors and helpers there, in addition to local helpers.

# Sponsors

This event is made possible thanks to our supporting partners:

- [de.NBI](https://www.denbi.de/)
- [DTL](https://www.dtls.nl/)
- INAB|CERTH
- EMC
- [Mozilla foundation](https://foundation.mozilla.org/en/), via a [Mozilla Open Science Mini-Grants](https://foundation.mozilla.org/en/awards/)

