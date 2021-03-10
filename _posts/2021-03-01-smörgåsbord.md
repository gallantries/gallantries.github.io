---
layout: post
title: "GTN Smörgåsbord: A Global Galaxy Course"
toc: true
tags: [teaching, training, pandemic, remote-teaching, videos]
author: [shiltemann, hexylena]
---

The Gallantries has finished our first event: ["the GTN Smörgåsbord: A Global Galaxy Course"](https://shiltemann.github.io/global-galaxy-course/). We discussed our plans a bit in our previous post about the [Admin Training]({% link "2021-02-01-gat.md" }) which we were using as a testing ground for our methodology. We scaled that up in Smörgåsbord and it was absolutely incedible!

# About the Event

We had an unbelievable 1189 registrations from 76 different countries around the world. 583 of these joined Slack which we used to communicate during the event, surpassing our expectations.

We had been in the processing of planning a small, 20 person workshop in ErasmusMC when the COVID-19 pandemic struck. The workshop kept getting pushed back further and further and when we finally got around to planning it, we knew it would be online. A few of our collaborators got in touch saying they were interested in co-hosting this event and their communities were desperate for proteomics and mass spectometry training. So we said:

> Sure! We'll open this up to everyone. What could go wrong

With instructors and organisers from the CINECA and the Gallantries we developed a workable plan for an online, world-wide event. For this event we decided to go **fully asynchronous**. We would place *everything online* and students could follow along at their own pace, taking breaks whenever they liked. We identified this as a maximally productive solution: we can reach the widest audience with the very limited number of qualified instructors. We tested this at small scale and by the time it was our turn, the event had become huge. We knew that the methodology would work, we knew that the materials could be taught online and via self-study, thanks in part to the Gallantries work to ensure broadcast-friendliness.

So as a community we recorded **25 hours of video**, corrected the captions for it, and posted it online, free to the world.

## Logistics & Communications

The workshop was well publicised across Twitter, CINECA, ELIXIR< the Galaxyproject websites, recruiting a large number of participants.

<figure>
  <img src="/assets/images/smorg-country.png"
  alt="heatmap with world map showing registrations">
  <figcaption>We had registrations from across the world.</figcaption>
</figure>

<!--
Our students were quite varied:

<figure>
  <img src="/assets/images/gat-career-stage.png"
  alt="pie chart, it's ugly and hard to read.">
  <figcaption>Most of our students were Researchers/Staff (48.1%), followed by Post-docs (19.2%)</figcaption>
</figure>
-->

All participants received a [pre-event email with basic instructions.](https://github.com/galaxyproject/admin-training/blob/2021-online/communications/pre-training-email.md) The were directed to join the Slack we setup as the communication platform during the event.

<figure>
  <img src="/assets/images/smorg-slack.png"
  alt="screenshot of slack channels. There's one per topic (e.g. 1-1_galaxy_intro), an some other assorted channels: instructors (private), coordinators (private), and a number of social channels.">
  <figcaption>We setup Slack channels for each topic, some private channels for instructors, and a number of social channels for participants to engage in social activities.</figcaption>
</figure>

We additionally had <abbr title="Frequently Asked Questions">FAQ</abbr> documents per channel, something we've used heavily in the past. The students would collect questions in the FAQ and we would answer them. After the event we would take every question asked in the FAQ and integrate it into the training material in some way.

### Videos

The main, massive change with this event was the asynchronous nature. We created videos for as many topics as we could in advance and then placed all of these on YouTube for our students. Subtitles were a hard requirement for the videos, given the world-wide nature and number of non-native English speakers that would attend this event. Many of our instructors also have strong accents and we wanted the videos to be maximally accessible to our students. This is something we cannot achieve in real life that we can do *better* in an asynchronous event.

#### Video Production

Our instructors largely used Zoom for recording themselves doing the trainings which was quite effective. Zoom produces very small output files (~100 Mb for an hour of video) which significantly simplified sharing these and collecting them for upload. Once uploaded to YouTube, automatic captions were generated over the course of 8-24 hours. For 3 of the videos, the language was mis-detected as an incorrect language, and thus produced nonsense transcriptions. E.g. one Spanish native speaker, speaking English, was detected as German and the subtitles were the closest German words to what he spoke in English. Likewise, a Dutch speaker, speaking English, was detected as Dutch. Some of these were manually transcribed at great time cost before we discovered that AWS provides a transcription service wherein we could manually set the spoken language. This produced subtitles of a similar quality to YouTube's, different mistakes but same overall level of corrections required.

These captions were copied to a public Google Document where we invited members of the community to volunteer to caption videos in exchange for recognition on the video.

<figure>
  <img src="/assets/images/gat-caption.png"
  alt="screenshot of Google docs. A section reads 'Monitoring (Thursday)' and lists people who worked on the captions with their names in different colours. The video is linked below, before the rest of the contents highlighted in the colour of the first person.">
  <figcaption>This shared document for caption editing is a time tested process used in other online communities.</figcaption>
</figure>

YouTube has a nice feature where the entire contents of the video's captions can be edited, and they will take care of syncing the audio to the correct location for you. Thus we could edit the captions separate from their timings and this was very easy for volunteers to listen to a video and correct spellings and sentence ends.

Subtitles | Plays         | Watch time (hours)
--------- | -----         | ------------------
Total     | 7182          | 1549.7
off       | 4,178 (58.2%) | 837.2 (54.0%)
en        | 2,999 (41.8%) | 710.5 (45.9%)
{: .table.table-striped}

By watch time **45% of our users watched with subtitles**.

### Schedule

Each day presented with flexible schedule / ice breaker / tutorials / wrap-up/socialisation

<figure>
  <img src="/assets/images/smorg-schedule.png"
  alt="Screenshot of the schedule with numerous sections. TODO">
  <figcaption>TODO</figcaption>
</figure>

### Slack

The ice breakers turned out to be quite effective for getting students to interact and say hi. It let them share something and others comment on it, fostering discussion in what is otherwise a very isolating experience.

Lastly, we had chosen Slack as the platform due to the built-in ability for 1:1 video calls but these were mostly unused, participant questions could be solved without them.

### Helpers

The logistics of organising helpers across such a wide arrange of timezones was not a simple task! We started by breaking the world into three regions, <abbr title="asia / pacific">APAC</abbr> (or <abbr title="Asia / Pacific / Oceania">APO</abbr> in our documents), <abbr title="Europe, Middle East, Africa">EMEA</abbr>, and the Americas. We recruited helpers from each of these regions, and had them report their availability during the week.

## Participants

We asked students to register in TIaaS, the Training Infastructure as a Service system that is available on UseGalaxy.eu and UseGalaxy.org.au which allowed us to track a subset of them during the week.

TODO: graphs


## Feedback

The feedback from students was largely very positive. Most students found the training extremely useful to them.

![21 students gave a 5 for usefulness, 2 gave a 4, 1 gave a 3.](/assets/images/gat-f-useful.png)

Importantly for us, most students compared this event favourably with a face-to-face training, reporting "I am very happy with my virtual experience".

![bar chart titled: how would you compare this with a face-to-face event. Was it ok? was it enough? 11 students gave a 5, 11 a 4, 1 gave a 3, and 1 gave a 2.](/assets/images/gat-f-f2f.png)

Likewise, contrary to our expectations, the trainees reported a significant affinity for the videos.

![bar chart titled: where the videos a useful format? 11 gave a 5, 10 gave a 4, 3 gave a 3.](/assets/images/gat-f-videos.png)

We asked students about the best and worst aspects of the event. They identified a number of things they really liked

"Best" Aspect             | People reporting this
-------------             | ---------------------
You go at your own pace   | 7
Flexibility of schedule   | 4
Flexibility of location   | 3
Slack                     | 3
Materials + Videos        | 2
Instructor responsiveness | 1
[specific instructor]     | 1
Tutorials                 | 1
{: .table.table-striped}

And the worst aspects of the event for them:

"Worst" Aspect                                       | People reporting this
----                                                 | ----
Lack of social activities / opportunities            | 10
AWS Polly                                            | 1
Slack                                                | 1
Not live video                                       | 1
Getting lost between the video/tutorial/slides/slack | 1
{: .table.table-striped}

We did not plan social events and this was a mistake on our part. For future Gallantries events in this style we're planning social activities such that students can perhaps meet each other.

## Accessibility

There are a few feedback responses we want to highlight. Some trainees really appreciated being able to revisit earlier materials and do things out of the 'official' order, allowing them to deepen their understanding:

> To be honest, the asynchronous methodology and the virtuality was extremely convenient to learn. The non-linear learning as I experienced the event, did not only help me to cover details that are normally unseen under deployment and admin  but also kindled motivation to master Galaxy at all levels.

The following comment *really* impacted us. It is one of the reasons we've deemed captioning so important: **accessibility**. Where the instructors talk too quickly or in an accent the listener is not familiar with, this can significantly impact understanding. By moving this event online and giving the students freedom to pause, to rewind, to ask questions *whenever* they feel like (not at designated periods at the end of a lesson) we enable everyone to have a more enjoyable and better learning experience.

> Honestly, this has been far the best training so far. [...] The instant support by the trainers has been perfect. This is an important point for me. In my previous in-person trainings sometimes I got lost. Of course I got help, but the class won't wait (so long). So sometimes I found myself rushing through the following stuff to get back on track again - without learning much. This issue has been totally solved in GAT 2021. I could work in my own pace. Furthermore there has been room for more questions in my opinion in contrast to the in-person trainings.

For trainees who might lose their train of thought by the end of a lecture section and forget their question, now they can just immediately ask it within the chat without "interrupting" the class and have a deep discussion, before moving back to the video and continuing at their own pace. For students who misheard or missed a section, they can review it without interrupting the flow of the class. For students who just wanted to review e.g. the "week overview" diagram to figure out where they are, they can do this at any time without losing out on content.

And a final comment on that topic:

> Best - doing this course in my own space with my own tech made this very efficient/comfortable which helped my learning

Often the environment of a small classroom next to unfamiliar people, with a travel laptop can impact the student's learning experience. If they are used to specific accommodations they have at work or home that help them be more productive and focused, they may be forced to attend without these.

One of the instructors had this view of it:

> For students the situation is "I can still hear the instructors but I can pause when I need", while for us instructors it's "this is happening but I can't see anything." So it's probably a lot less weird for them than it is for us.

And this likely feeds into the resistance to moving to fully asynchronous events despite their overwhelming benefits in terms of accessibility for all students, regardless of any disadvantages they might experience.

## Instructors

Our instructors had positive things to say as well. Simon mentions a known blindspot of students disappearing, we need to find more ways to encourage them to share their successes:

> I like some aspects of it. Especially the ability to do a <abbr title="Choose Your Own Adventure">CYOA</abbr> day. It was less tiring as well. We can definitely cover more people at one and it's significantly more accessible. However I did miss the social/getting to know the students aspect. The other problem is getting students with problems to speak up and not just disappear quietly.

Saskia is the primary organiser or Smörgåsbord and was taking notes during her role as an instructor in GAT:

> I agree with all of the above, it is harder to monitor if anybody is falling behind, but on the other hand it is easier to catch up if you do fall behind than in a synchronous format. The social interaction is the big difference, for Smörgåsbord we are trying to organize some "social sessions" (quizzes, games, chats), we will see if people go for those. The check in calls didn't really take off, that would have been a good opportunity for some interaction, not sure how we could encourage participation in those in the future.. I definitely like the fact that it is now more accessible for certain regions of the world that would otherwise not be able to participate. And yes, less stress during the week, even easier to rerun (say at GCC), miss the travel and getting to spend a week with all of you of course.

She had an interesting suggestion we'll look into in future events:

> Wonder if we could create "mentoring groups" each instructor gets assigned a smaller group of students in their time zone, they have their own chat channel, can ask them more personally how they're doing? Maybe it's easier for some participants to speak up in a smaller group?

And Nicola echoed all of the comments, the issue following along with students is difficult and our progress monitoring system does not capture everything.

> Agreed! In general, it has the same benefits and issues of other online training courses. I miss in particular all the social parts with fellow trainers and getting to know new people. Also, as mentioned, it is more difficult to gather the visual feedback of looking at people' faces to see if they are following or completely lost.

# Takeaways

## Methodology

1. Captions are mandatory.
2. Asynchronous means accessibility
3. Fully asynchronous works, students love it.
4. Fully asynchronous means anyone can attend regardless of timezone - reduced exclusion based on instructor timezones.
5. The format is less stressful for students and instructors.

## Communication

1. Real-time communication was key for students.
2. Slack (or equivalent) works quite well with threaded conversations and separate channels for separate topics.

# The Future

With the fantastic feedback and organisation from this event, the Gallantries feels a lot more certain about hosting the largest Galaxy event in history with 700 registrants as of the writing of this post. This methodology works extremely well and scales fantastically.

# Thank You

We'd like to say thank you to all of our instructors and sponsors!

## Instructors

A huge thank you to the instructors who produced videos (in order video airing order)

- Sergey Golitsynskiy
- Martin Cech
- Helena Rasche
- Catherine Bromhead
- Simon Gladman
- Saskia Hiltemann
- Nicola Soranzo
- Gianmauro Cuccuru
- Anthony Bretaudeau
- Enis Afgan
- Anurag Shankar

As well as the huge number of folks who helped edit and correct captions

- Catherine Bromhead
- Simon Bray
- Simon Gladmann
- Estelle Ancelet
- Beatriz Serrano-Solano
- Anthony Bretaudeau
- Martin Cech

And everyone who helped answer questions in Slack!

## Sponsors

This course has received funding from EOSC-Life Second Training Open Call. EOSC-Life has received funding from the European Union’s Horizon 2020 programme under grant agreement number 824087

[![EOSC Life logo](/assets/logos/eosc.png)](https://www.eosc-life.eu/)

We are grateful to Jetstream and the Galaxy Team for providing VMs from their allocation `TG-CCR160022` for this event.

[![Jetstream logo, it's dark red lettering with a teal green wave in an affront to good design](/assets/logos/jetstream.png)](https://jetstream-cloud.org/)

A significant portion of our infrastructure was graciously provided by Galaxy Australia

[![Australian BioCommons](/assets/logos/biocommons.png)](https://www.biocommons.org.au/galaxy-australia)

Virtual Machines were provided by the German Federal Ministry of Education and Research BMBF grant 031 A538A de.NBI-RBC.

[![de.NBI Logo](/assets/logos/denbi.png)](https://cloud.denbi.de/)
