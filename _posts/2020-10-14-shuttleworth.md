---
layout: post
title: "What I've been up to, besides PhD"
categories: open-hardware
comments: false
image: /assets/img/logair.png
---

<p>
<a href="http://logair.ch"><img src='/assets/img/logair.png'></a>
</p>

>**Tl;dr:** Some time ago I was lucky enough to receive a [Shuttleworth Foundation flash grant](https://www.shuttleworthfoundation.org/fellows/flash-grants/); in this post I share how I used this one-time support to advance one of my projects, LogAir.

I usually refer to low-cost air quality monitoring projects as one the *"cliches"* of open hardware/IoT. So many initiatives have emerged during the last 10 years around the world, such a variety of approaches in terms of technology, goals, openness. During [GOSH 2018 in Shenzhen](http://openhardware.science/gatherings/gosh-2018-2/) alone, we run a session on the topic and gathered about 10 people working on different projects. And yet here I am, having co-founded [LogAir](https://logair.io) in 2019 with my collegue, [Emmanuel Kellner](https:/twitter.com/EmmanuelKellner). 

I think the reason why I got into it is because I see LogAir as a project building on all those experiences, and compatible with all those that are open too. I was never too worried about the technology part, as it is widely documented online and Emmanuel and [Nicos](https://twitter.com/AtomicNicos) (our software development intern) can make wonders with it. I wanted to focus instead on two other aspects that I've seen failing over and over: helping people make **meaning out of data** and making **data useful for policy** makers.

Just in case, I'm always referring here to **community-generated data**, not data from official measurements. Taking into account those aspects I mentioned above, in my head one of the missing links was the ability of community air quality projects to share their data sans friction. After GOSH 2018's session, a lesson we all learned is that pretending that people use one sigle golden hardware design was useless. There are as designs as contexts, and it's OK, what we need is interoperability.

I was also considering the experience of important community AQ projects that "made it" into the official maps: [PurpleAir](https://www2.purpleair.com/ ) in California with a layer added into [this pilot USEPA map](https://fire.airnow.gov/?lat=37.768719999999995&lng=-122.4454258&zoom=12#), and [Sensor Community](https://sensor.community/) (ex-Luftdaten) with their data popping up for example in [Bristol's open data portal](https://opendata.bristol.gov.uk/explore/?q=air+quality&sort=modified). They both propose certain hardware designs, is it scalable a model like this? What if I want to use another device? Can we add infinite layers to official maps?

<p align='center'>
    <img src='/assets/img/usepa_notice.png'><br>  
    <i>Notice on community-generated data in the <a href='https://fire.airnow.gov/?lat=37.768719999999995&lng=-122.4454258&zoom=12'>USEPA Fire and Smoke Map</a></i>
</p>

I decided LogAir could be a nice playground to embed all these thoughts and experiment with them. How does the problem look like in practical terms? Which are the non-technical obstacles to design interoperable collaborative systems for air quality in practice? 

So when I got the Shuttleworth flash grant, I intended to use it first to attend a meeting close to Geneva, where I'm currently based: [Citizen Science with Application to Nuclear, Seismic and Air Quality Monitoring](http://indico.ictp.it/event/9026/). Lots of people doing exactly what I wanted to do, good departure point. Unfortunately COVID-19 got in the middle and the meeting was cancelled (not re-scheduled, not moved online... AQ is not an urgent problem, it seems :P). A bit disappointed, a while after that I came across [Open Environmental Data](https://twitter.com/OpenEnviroData), the next cool thing [Shannon Dosemagen](https://twitter.com/sdosemagen) is working on.  

And voilà! I was delighted to see I didn't have to reinvent the wheel. The analysis on [Data Governance Models and the Environmental Context](https://www.openenvironmentaldata.org/blog/data-models-part3) mentioned all the items we were trying to work on with LogAir, and detailed many of the bottlenecks too. Maybe we could become a  use case of OpenEnviroData ideas...?

This is why we are focusing now with LogAir on creating partnerships, in particular with official agencies and policy makers, to learn first hand about their expectations, fears, the ways they work every day at the office. What does it take to collaborate? One big step, for example, was being heard by [Geneva's air quality agency](https://www.ge.ch/dossier/qualite-air), who accepted the calibration of LogAir sensors against their official standards. Another important aspect we are discussing is privacy: most environmental data is tied to geographic coordinates. Can a model like the [Swiss Data Science Center](https://datascience.ch) be useful for us? And who is going to pay for all this work? The Shuttleworth grant also allowed me to dedicate time to learn and think about business models for an initiative like ours. Last but not least, it allowed me to redesign [LogAir's website](https://logair.ch).

Now my PhD has taken over and there's no space in my head for anything else, but I'll be posting updates on this experiment once I become a Doctor ;)




