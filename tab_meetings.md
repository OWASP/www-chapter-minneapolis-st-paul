---
title: Meetings
layout:  null
tab: true
order: 1
tags: MSP
meetup-group: OWASP-MSP-Meetup
---

# Meetings

The OWASP-MSP chapter meets at least quarterly. Please see our 
[Meetup page](https://www.meetup.com/OWASP-MSP-Meetup) for the latest information.

## Call for talks

If you have a talk you'd like to give, a discussion to lead, or some ideas for future talks, 
email the chapter leaders listed at right! You don't have to be an OWASP member to share your experience.

## Next meeting scheduled

_[Watch this space]_

{% include chapter_events.html group=page.meetup-group %}

<script type='text/javascript'>
  $(function(){
    $(".timeclass").hover(function() {
      utc_str = $(this).text();
      ndx = utc_str.indexOf(':');
      st_hour_str = utc_str.substring(0, ndx);
      st_min_str = utc_str.substring(ndx + 1, ndx + 3);
      utc_dt = luxon.DateTime.utc(2020, 06, 06, parseInt(st_hour_str), parseInt(st_min_str), 0);
      start_dt = utc_dt.setZone(luxon.DateTime.local().zoneName);

      ndx = utc_str.lastIndexOf(':');
      end_hour_str = utc_str.substring(ndx - 2, ndx - 1);
      end_min_str = utc_str.substring(ndx + 1, ndx + 3);
      utc_dt = luxon.DateTime.utc(2020, 06, 06, parseInt(end_hour_str), parseInt(end_min_str), 0);
      end_dt = utc_dt.setZone(luxon.DateTime.local().zoneName);
      popstr = start_dt.toLocaleString(luxon.DateTime.TIME_WITH_SECONDS) + ' to ' + end_dt.toLocaleString(luxon.DateTime.TIME_WITH_SHORT_OFFSET);
      $(this).prop('title', popstr);
    });
  });
</script>

## Meeting archive

* [20220525](https://www.meetup.com/owasp-msp-meetup/events/285695539/): David Melamed: The OWASP Serverless Security Top 10 as Code - [Video](https://youtu.be/e_2RxD5Mqn4)
* [20220420](https://www.meetup.com/owasp-msp-meetup/events/285130448/): Himanshu Dwivedi: How to Hack an API in 15 minutes!
* [20220323](https://www.meetup.com/owasp-msp-meetup/events/283389664/): Alex Bauert and Nathan Larson: Pen-testing, encryption, open forum
* [20211216](https://www.meetup.com/owasp-msp-meetup/events/282157443/): Alex Bauert and Nathan Larson: The OWASP Top 10, 2021 edition - [Slides](download/20211216_OWASP-MSP_OWASP_Top_Ten_2021.pdf?raw=true)
* [20210727](https://www.meetup.com/owasp-msp-meetup/events/278765243/): Alex Bauert and Nathan Larson: SAST for a Secure Future -- Today - [Slides](download/20210721_OWASP-MSP_SAST_for_a_Secure_Future_--_Today.pdf?raw=true)
* [20210211](https://www.meetup.com/owasp-msp-meetup/events/275615353/): Alex Bauert, Zoa Buske, and Nathan Larson: The state of IoT security - [Slides](download/20210211_OWASP-MSP_The_state_of_IoT_security.pdf?raw=true)
* [20201029](https://www.meetup.com/owasp-msp-meetup/events/273422662/): Alex Bauert, Zoa Buske, and Nathan Larson: Securing Infrastructure as Code - [Slides](download/20201029_OWASP-MSP_Securing_Infrastructure_as_Code.pdf?raw=true)
* [20200227](https://www.meetup.com/owasp-msp-meetup/events/268460210/): Alex Bauert and Nathan Larson: Open forum for OWASP-MSP chapter
* [20191203](https://www.meetup.com/owasp-msp-meetup/events/266259458/): Yan Kravchenko: Assessing Application Security Programs with SAMM 2.0
* [20190924](https://www.meetup.com/owasp-msp-meetup/events/264466608/): John Benninghoff: Chaos engineering
* [20190626](https://www.meetup.com/owasp-msp-meetup/events/262130893/): Alex Bauert: Open forum for OWASP-MSP chapter
* [20190320](https://www.meetup.com/owasp-msp-meetup/events/258911164/): Chris Rasinen and Cody Bertram: The State of Application Security
* [20190109](https://www.meetup.com/owasp-msp-meetup/events/257053514/): Tony Ramirez: Hacking Your Enterprise by Reverse Engineering Your Mobile Apps
* [20181128](https://www.meetup.com/owasp-msp-meetup/events/256158710/): Alex Bauert: Threat Modeling
* [20180912](https://www.meetup.com/owasp-msp-meetup/events/253933603/): Yan Kravchenko: Evolution of Application Security Programs through OWASP SAMM 2.0
* [20180719](https://www.meetup.com/owasp-msp-meetup/events/252531062/): Eric Johnson: Secure DevOps: A Puma’s Tail
* [20180514](https://www.meetup.com/owasp-msp-meetup/events/249940370/): Bjoern Kimminich: The OWASP Juice Shop Project
* [20180125](https://www.meetup.com/owasp-msp-meetup/events/246716107/): Ryan Manship: Red Teaming
* [20171026](https://www.meetup.com/owasp-msp-meetup/events/243939172/): Greg Anderson: The OWASP DefectDojo Tool Project
* [20170928](https://www.meetup.com/owasp-msp-meetup/events/242716394/): Vishal Asthana: How Billion Dollar Enterprises Manage Application Security at Scale
* [20170816](https://www.meetup.com/owasp-msp-meetup/events/241857223/): Yan Kravchenko: Evolution of Application Security
* [20170420](https://www.meetup.com/owasp-msp-meetup/events/238763276/): Brian Johnson: Containers and Application Security
* [20170316](https://www.meetup.com/owasp-msp-meetup/events/237614671/): Girish Nair: Instrumenting Software and Software Security
* [20170215](https://www.meetup.com/owasp-msp-meetup/events/237019121/): Bob Sullivan: Full static analysis on 2 hours a month:
* [20170111](https://www.meetup.com/owasp-msp-meetup/events/236052922/): Jack Mannino: MircoServices and Security


