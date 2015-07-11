---
layout: post
cover_image: "voyagequest_cover.png"
permalink: /voyagequest
date:   2014-06-24 00:00:00

# Front page
description: "I made an art project called Voyage Quest to ween people off of their smartphones." # Supports Markdown format
button_title: View case study 

# Detail page
title: Voyage Quest
subtitle: Death to smartphones
summary: 
    title: "Voyage Quest: worth a diploma"
    content: "Voyage quest was my bachelors graduation project from the [Royal Academy of Art](http://www.kabk.nl). To earn my bachelors, I had to write a thesis and work on a year long project. The only constraint on chosing a project to work on was that it must be in some way interactive. I chose a problem that was on my mind at that moment. As a (then) recent smart phone convert, I became fascinated with peoples obsession and reliance on their smartphones and decided to make my project around it."
   

# Meta info
meta:
    tasks: "UI, UX, Concept, Programming"
    type: an iOS app
    duration: "8 months on nights and weekends"

# Style information
color: "#202117"
---

### The Problem

Coming from a generation where my childhood was generally untainted by computers, I still remember the phenomenon of people being together, focused solely on each other. I speak in the past tense because I literally can't remember a social gathering that wasn't constantly disrupted by smartphone usage in recent memory. 

As a late convert to smartphone land, I had a unique perspective on my peers' usage of smartphones as an outsider. I witnessed people walking through the streets, like zombies, faces glued to the their screen, walking in a trance through busy streets. I experienced being deep into conversation with someone, and them unconsciously checking their phone and halting the conversation to read their Twitter/Facebook/whatever feed. I was flabbergasted as people would text me all day, and when we were finally in the same room together, they would spend the entire time texting other people. Most shocking of all to me, this was all socially acceptable behaviour.

{% include figure.html src="/assets/images/posts/voyagequest/sign.jpg" caption="" retina="false" %}


To be clear, I'm not against smartphones. I think actually think they're pretty great. However, I believe as constant connectivity becomes ubiquitous, I think it's important to be critical and conscious of what kind of role technology will play in our lives. That was the point of the project.

Nicolas Carr put it more eloquently than I ever could: “As McLuhan suggested, media aren’t just channels of information. They supply the stuff of thought, but they also shape the process of thought. And what the Net seems to be doing is chipping away my capacity for concentration and contemplation. Whether I’m online or not, my mind now expects to take in information the way the Net distributes it: in a swiftly moving stream of particles. Once I was a scuba diver in the sea of words. Now I zip along the surface like a guy on a Jet Ski.”
{% include figure.html src="/assets/images/posts/voyagequest/Vatican.jpg" caption="" retina="false" %}



### Concept
To end the tyranny of smartphones, I decided to work with the addiction rather than against it. Preaching or shaming would only lead to polarisation. Therefore, I decided to make a smartphone app that would entice people into putting away their smart phones. Kind of ironic, but bare with me. 

My aim was to create an app that, to the user, appeared only as a fun game. Meanwhile, I'd secretly be weening them off of their smartphone. The core game mechanic would be to reward users for doing things in the real world. 

A very simple iteration of this concept is something on screen that reacts to something done in real life, like a precariously balanced pile of fruit falling when you shake the phone. 
{% include figure.html src="/assets/images/posts/voyagequest/Startconcept.png" caption="" retina="false" %}
In essence, it's quite silly. It doesn't feel like you've broken any barriers down by doing that, but in truth you've just connected digital and physical. However, knocking over fruit isn't quite groundbreaking enough to make an engaging game to shatter an addiction.

###Cue gamification 
Gamification is a bit of dumb buzzword, but there's a lot of power behind the concept. I needed to learn how to make an addictive, engaging game if I had any hope of succeeding in my mission. Then came my saviour, Jane McGonigal, who wrote this lovely book:

{% include figure.html src="/assets/images/posts/voyagequest/reality.jpg" caption="I'm aware the title contradicts my entire project, shhhh" retina="false" %}

Thinking of my target audience (smart phone owning millennials), I determined I could hit them right in the feels by creating a game that harkens back to their childhood by creating a Super Mario type game in both visual styling and interaction. 

What does that mean? You're a character, navigating through a world, and in order to solve in-game challenges you have to do something in the real world. The character has to walk a long way? So do you. The character needs to eat something? So do you. The character needs to work with other people to solve a puzzle? So do you. 

By working creatively with inputs on the phone, (bluetooth, wifi, GPS, accelerometer, light sensor, camera, gyroscope, mic, etc.) I could turn each challenge into something quantifiable, and thus check when it was complemented.

### Prototyping
I decided to make a quick prototype to informally test several things: the technical challenges, what users thought of the visual style, and what an effective interaction would be, and whether or not my game was even fun. Firstly I had to figure out how to program a game:
{% include figure.html src="/assets/images/posts/voyagequest/PrototypeCode" caption="annnd done" retina="true" %}

Then I had to combine code and old school visuals. The result was this prototype, with our hero, lazily drawn stick man.
{% include figure.html src="/assets/images/posts/voyagequest/Prototype-compressor.gif" caption="" retina="false" %}
{% include figure.html src="/assets/images/posts/voyagequest/Prototype2.gif" caption="" retina="false" %}

I showed this prototype to my classmates and friends. First reactions were positive, but after explaining my whole concept, something clashed. The visual style was fun, but the idea behind the game was quite sober. Furthermore the storyline in my game lacked any relation to the concept. 

All good feedback: I needed to go back to the drawing board to connect the threads of concept, storyline, and visual style. 

###Pivot
I decided to rework the story to put a more dire need to end the addiction to devices. The new story became: in a dystopian future, people are so addicted to their devices that society is a cultureless blob. You, the protagonist, have recently lost your device and have your eyes opened to what the world has become. Your mission is to rid the world of devices via a series of challenges (that take place in the real world).

###Visual design
With the new story, the colorful pixel art didn't fit the new dystopian storyline. To rework the style, I turned to one of my all time favorite movies for a inspiration, Blade Runner. (I'll take any excuse to rewatch Blade Runner really)
{% include figure.html src="/assets/images/posts/voyagequest/Bladerunner.jpg" caption="What a dreamboat" retina="false" %}

I decided to make the scenes black and white, with a heavy emphasis on contrast, like an old film noir. I also tried to emphasize the industrial/technological elements of the city. I stuck with a hand-drawn style, because I felt like it gave off a gritty vibe that suited the bleak story well. 
{% include figure.html src="/assets/images/posts/voyagequest/doors-compressor.gif" caption="" retina="false" %}


###Done is better than perfect
Part of having no restrictions while making a project means it's easy to slide into a void of refining, perfecting, and exploring every possible avenue. Even the assignment: "smartphones are intrusive, make a game about that" could produce an infinite amount of games. Even this point, I had read book after book about everything from psychology to technology to gamification. Enough was enough. Based on feedback from my peers and professors, I decided it was time to stop exploring and start making the game in earnest.
{% include figure.html src="/assets/images/posts/voyagequest/In progress.jpg" caption="" retina="false" %}


###Produce, Produce, Produce
My first step was to create a storyboard that encompassed the story and three challenges that could take place in the real world, but within the confines that I would have to present this project in a gallery (so no making users walk a mile or something).

After the practicalities were established, I had to create the assets, learn enough of cocos2d to string a game together, and make a technical plan. Production included creating all the assets, including many hand drawn frame-by-frame animations which were almost the death of me. Then of course programming, testing, wrangling iPhones, and building a website/identity around the game. The actual core game was built in about three weeks of crazy long days. One of the game levels required the users to scream into the iPhone, so I think I definitely annoyed my neighbours with my testing. 

After eight months of tribulations, doubts, research, and learning, I had a working game! 

{% include figure.html src="/assets/images/posts/voyagequest/Jump-compressor.gif" caption="jump for joy" retina="false" %}


###Name choice
Oddly, one of the hardest things to do was name this game. It had the working title of Intervention at the beginning, but that seemed a tad on the preachy side. However, somehow I could not think of anything better, even up until the point where it was time to put in the app store. Felt a bit like this: 
{% include figure.html src="/assets/images/posts/voyagequest/pbf.jpg" caption="" retina="false" %}

In the end, I chose the quite silly name "Voyage Quest" as a result of a brainstorming session with my project mentor and professor. She and I wrote many random words on a piece of paper that related to the game. I connected Voyage Quest, which she hated, but somehow the absurdity of it just touched me. She was still against it, and despite the fact she was one of the main judges on whether or not I would graduate, I kept it as Voyage Quest. Stick to your (absurd) guns I guess.

{% include figure.html src="/assets/images/posts/voyagequest/Default.png" caption="The Voyage Quest logo, gritty hand drawn" retina="true" %}


###Present, Present, Present
One important aspect of my graduation was how I chose to present my work. Graduating students have to display their work in an exhibition for a week. I built three custom stands to hold iPhones and placed them in a dark room. Three iPhones because part of the game involved working together. Inside the stands, I installed a projector that showed everything going on on the screen to entice passerbys. I attached the iPhone with anti-theft cords, and allowed people to interact with the game however they chose. I lurked in the corner, and people not realising that it was my work spoke candidly about what I made, which was pretty great feedback. 
{% include figure.html src="/assets/images/posts/voyagequest/plan1.png" caption="A sketch of my plan" retina="false" %}

{% include figure.html src="/assets/images/posts/voyagequest/grad.jpg" caption="Using a circular saw was, to date, one of the scariest experiences of my life" retina="false" %}


###Graduate! 

My main points of feedback were curiosity about what game could be if it were fleshed out more, and some tweaks in the interface that would make easier to understand. Despite a few negative points, reactions were mostly positive, and I was deemed fit to graduate. Photo evidence below.
{% include figure.html src="/assets/images/posts/voyagequest/diploma.jpg" caption="running away before they change their mind and take my diploma back" retina="false" %}


##The end? 
The entire time I was working on this project, I was also working 36 hours per week at a tech start up as an iOS developer. Despite all of the practical challenges, Voyage Quest still happened. 

After I crossed the finish line at graduation, a saw the game as a symbol of all of the stress and unhappiness that had plagued me for the past year. I still believe in the concept and topic, but I think it's better to let some things die to move on to bigger and better projects. What can't be erased are the huge array skills I gained from building this game. I know how to produce game art, code in cocos2d, tackle procrastination, and push through stress to make sure a product is finished. 

The code base is there, the game works, so who knows? Maybe someday I'll pick this up again; until then the smart phone tyranny will have to remain...



{% include figure.html src="/assets/images/posts/voyagequest/Stand.png" caption="" retina="true" %}


The end for now.


