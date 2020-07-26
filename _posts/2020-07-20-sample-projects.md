---
layout: post
title:  "Projects"
date:   2018-02-20
excerpt: "A selection of some fun projects / ideas"
project: true
tag:
- projects 
- IoT
- hack
- slackbot
- hobby
- machine learning
comments: false
feature: /assets/img/projects/project_feature.jpg
---

Ariadne: Lifehack for the Munich Public Transportation
-----
Google Maps / MVV (Munich Public Transportation) can give you the directions to your destination. But once you arrive at the destination, especially using the Metro / Suburban Rail, there is a multitude of exits. Choosing an exit among the choices is not trivial at all times. This could cost up to 5-10 minutes per journey.

We built Ariadne which suggests the closest exits to your destination for the public transportation. It also recommends the part of the train you need to board to be close to the suggested exit. The users can provide feedback about the suggestions that can further improve the system. Additionally, we developed the ability to navigate indoors without the use of any infrastructure using mobile phone sensors. 

This project was developed initially during the [hackatum](https://hack.tum.de/), the annual hackathon from Technical University of Munich. Based on the positive feedback we received, we pursued it further including pitching it to some business customers like the German rail company, Deutsche Bahn. We also secured 2nd place in the [Mobility Innovation Competition @ Campus](http://zentrum-digitalisierung.bayern/micc-mobility-innovation-competition-campus-2017/) held by the Center for Digitalization, Bavaria State. 

You can watch a video that showcases some of the ideas. 
<iframe width="560" height="315" src="//www.youtube.com/embed/AN9Ly8vFv-Y" frameborder="0"> </iframe>

Alexa Skill for Ariadne
----
A prototypical voice skill was also tested for Ariadne. It was implemented mainly to learn about how voice skills were developed for Amazon Echo.
<iframe width="560" height="315" src="//www.youtube.com/embed/zzZjqM-rD2E" frameborder="0"> </iframe>


Hodor: Controlling the office door from the Internet
-----
At [KI labs](www.ki-labs.com), we faced the problem of shortage of keys. To solve this problem, we connected the intercom system in the office to the internet using a Raspberry Pi which could then be controlled from Slack. 

It was also interesting to see this turning into a platform of sorts with multiple teams working on further integrations like mobile apps, face detection based authentication, etc.

<figure>
    <img src="/assets/img/projects/hodor.jpeg">
    <figcaption>Hodor in action</figcaption>
</figure>

You can read more about it on the [blog post](https://medium.com/ki-labs-engineering/hodor-controlling-the-office-door-from-slack-a79e77635e39)

[Code](https://github.com/KI-labs/Hodor)


Sign 2 Speech: Sign Language Interpretation for Speech Impaired
-----
Sign 2 Speech provides a communication solution to hearing impaired or mute people. It empowers them to navigate every day social environments by translating gestures to speech. This was developed during, [Think.Make.Start](https://www.thinkmakestart.com/), a two week inter-disciplinary course on product development at the Technical University of Munich. 

The gesture recognition was done based on the electromyography (EMG) sensors present in Myo armband. The arm band could be used to detect gestures based on the muscle movement and these gestures could be customized by the user. The gestures once recognized would trigger the speech using a portable speaker or the smartphone.

You can watch a short demo of it being used by speech impaired people.
 <iframe width="560" height="315" src="//www.youtube.com/embed/i0AWo0em9J4" frameborder="0"> </iframe>

The project was adjudeged as one of the best projects in the cohort.

Just a Little Longer: Hardware based Parental Control System for Kids
-----
This was developed over the weekend during Code TwentyFour, the hackathon organized by ProSieben in Munich. JaLL enables kids to consume content on smartphones or smart TVs using physical coins based on NFC similar to a piggy bank. Parents could monitor and set limits on what content could be consumed by the kids. 

The NFC based tokens were read by the reader placed inside the piggybank and allowed kids to consume media for the specified amount of time. The content was played inside a frontend which enabled us to control the media playback based on the validity of tokens governed by a backend API.

This project was adjudged the best project at the hackathon :)

<figure class="half">
    <img src="/assets/img/projects/jall.jpg">
    <img src="/assets/img/projects/jall_ui.jpg">
    <figcaption>Piggybank for coins and the Jall interface</figcaption>
</figure>

JaLL being tested by prospective consumer. The audio is partially in German. 
<iframe width="560" height="315" src="//www.youtube.com/embed/XDhffYlrn9A" frameborder="0"> </iframe>

You can read more about it on the [project page](https://devpost.com/software/just-a-little-longer)

ViewfAInder: Buy What you see on TV
-----
This was developed over the weekend during 7Hack, the hackathon organized by ProSieben in Munich. ViewfAInder is an AI (computer vision) based system that enables you to pause your TV show to discover articles shown on the show that you can buy online. 

For the hackathon, we developed a browser plugin that would enable you to pause content on the PC. We take a screenshot of the content and then analyze it for products (holiday location, clothes, etc) and provide their links from the hackathon sponsors in an overlay over the video.

This project was one of the best projects at the hackathon :)

<figure class="half">
    <img src="/assets/img/projects/viewfAInder.jpg">
    <img src="/assets/img/projects/viewfAInder_architecture.png">
    <figcaption>ViewfAInder</figcaption>
</figure>

You can read more about it on the [project page](https://devpost.com/software/viewfainder)


Message Hub
------
We have a ton of messages across different messaging platforms like Whatsapp, Facebook Messenger, Telegram, Instagram, Slack, etc. It is a pain to find something that you discussed with a friend some time ago. We developed a hub for your messages that help you in finding all the messages that you send instantly. It also stores the important information from the messages for later retrieval.

We built an app that captures messages from different messaging applications like Telegram & Slack. The messages are analysed for their content & tagged. In the hub, you can visualize all your historic communication across different platforms over time including times of peak exchange in a heat map. Hovering on the peaks gives you more information about the exchange including the summaries and contents of the exchange. In addition, it can give you an overview of the locations on Here maps. Also packed in is a powerful search powered by Algolia to get the messages by content. Appointments agreed upon are also saved as an event on the platform.

<figure class="half">
    <img src="/assets/img/projects/message_hub.jpg">
    <img src="/assets/img/projects/message_hub2.jpg">
    <figcaption>Message Hub</figcaption>
</figure>

This project was awared the best project using [Algolia](https://www.algolia.com/) at the [jacobsHack!](https://jacobshack.com/). 

More can be read about the project on the [project page](https://devpost.com/software/message-hub)

Gesture Based Computing
----
Gesture based computing was developed during my undergraduate course. We developed a computer vision based system using color markers to control the computer. The gestures could be configured and adjusted according to the users' preferences. There were gestures for common use cases like opening the browser, image viewer, video player, controlling the mouse and keyboard among other gestures. 

An overview of some of the gestures can be seen in this video. 
<iframe width="560" height="315" src="//www.youtube.com/embed/nwgK-jifuY4" frameborder="0"> </iframe>

The results of the project are published in the [IJCA Special Issue on Advanced 
Computing and Communication Technologies for HPC Applications](https://www.ijcaonline.org/specialissues/accthpca/number4/7578-1032)