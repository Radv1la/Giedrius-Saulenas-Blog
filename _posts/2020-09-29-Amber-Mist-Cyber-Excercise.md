---
layout: post
title: Amber Mist 2020 cyber excercise
subtitle: Participating as the blue team member during the Amber Mist 2020 cyber exercise
description: Cyber security excercise
cover-img: /assets/img/amber-mist.jpg

tags: [Amber Mist, cybersecurity excercise, blue team, red team, Amber Mist 2020]
categories: [Cybersecurity Excercise]
---
As the cybersecurity exercise, Amber Mist 2020 had finished, I am sharing my experience during the two weeks of intense exercise time. Even though it was not easy, and it was pretty exhausting some of the days, I enjoyed every minute of it.
## What is Amber Mist?

{% twitter https://twitter.com/LTU_Army/status/1309493733382123521 maxwidth=500 limit=5 %}

Amber Mist is an international cybersecurity exercise that is held annually by the Defence Staff of the Lithuanian Armed Forces. It all started as the national level exercise in 2014 and gradually it grew into an international exercise with participants from other countries, such as Ukraine, Georgia, USA.

The purpose of the exercise is to improve cooperation and defense skills of military/international and civil IT specialists, to defend critical IT infrastructure.

The concept of the exercise is pretty straightforward – there are blue, red, and green teams. Green team simulates a work of an actual business – browses the internet, intranet services, and so on. The red team is responsible for attacking the infrastructure of a fictive business organization - the one that the green team is part of. And the blue team was responsible for protecting the network.


![Red team versus blue team](/assets/img/red-vs-blue.png)

There were separate polygons for each of the participating teams. The polygons had tens of different virtual machines with Linux or Windows operating systems and had many vulnerable components and applications. There were also a few routers that segmented the network, and each of them was configurable.

## The actual excercise

As I mentioned before, the exercise took a couple of weeks. During which there were different activities, that involved training, familiarization with the polygon, and the actual exercise.

I was a blue team member and had to defend the infrastructure. As the exercise was international, there were different commands from various countries and different organizations. I was a part of mixed command that consisted of high qualification professionals from the Lithuanian railways, Vilnius University, and Lithuanian Military Academy.

During the preparation period we were brainstorming what systems should be hardened, were writing our automation scripts for hardening the systems. We even managed to make our own LAN so that we could have our polygon for testing our scripts. The LAN also gave us a possibility of familiarizing ourselves with the tools and systems, that we had to use during the actual exercise.

Even though we spent a whole week preparing, it passed like a blink. Some of us were spending the remaining part of the day preparing for what we will do tomorrow, or trying to improve our scripts, find additional information.

When the actual exercise had started we were thinking that we are ready enough… But we were wrong. There were a few attacks each day, and even though we defended against some of them, other attacks were pretty successful. Many of the targets from our dashboard, showing the vital infrastructure we had to defend, was red each of the days. Anyway, the main purpose of the exercise is to train. And there is no better way to learn than learn from your failures.

## How did I get into the exercise?

As I am not in the military, it might sound weird that I was participating in the exercise, organized by the military. The secret is, that every year number of the Vilnius University students are allowed to participate in the exercise. As one of my lecturers, this year was the leader of the blue team, I had an opportunity to join the team.

## Things that I learned
Every challenge teaches you something. These are lessons, that I learned:

* You don’t mess with the routers. Or, if you do so, you must be careful. I learned this lesson after changing the router settings, after which many of our systems had turned red in the dashboard :)
* Cooperation is the key. Especially, in such a critical situation as a live cyber-attack.
* It is crucial to document your observations and steps taken during a live situation. This will benefit not only the people working together with you, but it might also be used for informing the stakeholders about the current situation. And of course, it will help to learn the lessons after the incident is finished.
* During a situation, you will not be able to defend everything. That’s why you need to prioritize. Identify the critical points and defend them.
* Always stay calm and focused. Especially during a tense situation.

## Was the exercise useful?

It definitely was. This was a great opportunity to prove myself and to learn new things.

Those couple of weeks helped to grow not only as a specialist but as a person also. As during the exercise I had only about a year of professional experience, mostly as a security tester, I had an excellent opportunity to deepen my knowledge in the domains such as networking or threat hunting, where I wasn’t experienced in. I was also able to test the things, that I learned at the university, in a real environment. The exercise helped “connecting the dots” in terms of knowledge. The exercise also helped to identify what technological domains I am weakest at.

After the exercise, I made a list of things that I am going to  learn. As Daniel Miessler said about having solid basics about networking, system administration, and programming: [“They key at this point is not to have major holes in your game, and being weak in any of those is a major hole.”](https://danielmiessler.com/blog/build-successful-infosec-career/) And I 100 % agree with this.

As one of the things that I learned, is that networking is my weak point, this is the router I bought after the exercise to deepen my networking knowledge.

![MikroTik router that I bought](/assets/img/mikrotik.jpg)
