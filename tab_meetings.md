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
[Meetup page](https://www.meetup.com/OWASP-MSP-Meetup) for the latest information. Chapter meetings are open to all!

## Call for talks

If you have a talk you'd like to give, a discussion to lead, or some ideas for future talks, email the chapter leaders listed at right! You don't have to be an OWASP member to share your experience. We're always looking for new ideas or fresh takes on the standards.

## Next scheduled meeting

* [24 Oct 2023: Andrew Carlson -- Gamifying Tabletop Exercises](https://www.meetup.com/owasp-msp-meetup/events/296499717) - [PDF worksheet](download/How_To_Tabletop_Like_A_Boss.pdf) - [Editable worksheet](download/How_To_Tabletop_Like_A_Boss.docx)
* ? Dec 2023: End-of-year retrospective -- to be planned


<!-- the below doesn't seem to be working -->

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

* [20230317](https://www.meetup.com/owasp-msp-meetup/events/291851101): [Redacted]: Application Security Considerations in Offensive Operations - [No video available]
* [20221011](https://www.meetup.com/owasp-msp-meetup/events/288608767): Guy Levinger: Cherrybomb – API security tests in the CI pipeline - [Video](https://youtu.be/jBeK0Qw0h94)
* [20220919](https://www.meetup.com/owasp-msp-meetup/events/287952262/): Sudheer Karanam: Privilege Identity & Access Management - [Slides](download/20220919_OWASP-MSP_Privileged_Access_Management.pdf?raw=true) - [Video](https://youtu.be/2DLl5wRHuNE)
* [20220718](https://www.meetup.com/owasp-msp-meetup/events/286913008/): Brian Reed: Pen-testing mobile apps with the OWASP MASVS - [Slides](download/20220718_OWASP-MSP_MASVS.pdf?raw=true) - [Video](https://youtu.be/Endr8RPpNSM)
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
* [20170215](https://www.meetup.com/owasp-msp-meetup/events/237019121/): Bob Sullivan: Full static analysis on 2 hours a month
* [20170111](https://www.meetup.com/owasp-msp-meetup/events/236052922/): Jack Mannino: MircoServices and Security
* [20161026](https://www.meetup.com/owasp-msp-meetup/events/234747284/): Jeremy Long: Depending on Vulnerable Libraries (OWASP Dependency-Check) - [Video](https://youtu.be/BUiWcDj1Ikw) - [Tool](https://owasp.org/www-project-dependency-check/)
* [20160921](https://www.meetup.com/owasp-msp-meetup/events/233911050/): Dan Cornell: The ABCs of Source-Assisted Web Application Penetration Testing With OWASP ZAP: Attack Surface, Backdoors, and Configuration - [Video](https://youtu.be/95YMV2G8bq0)
* [20160824](https://www.meetup.com/owasp-msp-meetup/events/233207985/): John Benninghoff: Practical Identity Access Management: Lessons from the Field - [Video](https://youtu.be/XxBoXwItNKs)
* [20160726](https://www.meetup.com/owasp-msp-meetup/events/232388831/): Caroline Wong: Software Security and Metrics
* [20160624](https://www.meetup.com/owasp-msp-meetup/events/231508872/): Anurag Agarwal: Practical Threat Modeling classroom
* [20160511](https://www.meetup.com/owasp-msp-meetup/events/230654716/): George Chatzisofroniou: Evil Twin Attack with Wifiphisher - [Tool](https://wifiphisher.org/)
* [20160308](https://www.meetup.com/owasp-msp-meetup/events/229240311/): Matt Tesauro: Doing App Sec at Scale
* [20160217](https://www.meetup.com/owasp-msp-meetup/events/228406877/): David Lindner: Testing Tools for iOS Applications - [Slides](download/20160217_OWASP-MSP_iOS_Testing_Tools.pdf?raw=true)
* [20160113](https://www.meetup.com/owasp-msp-meetup/events/227554267/): David Lindner: OWASP Mobile Top Ten Security Risks - [Slides](download/20160113_OWASP-MSP_Mobile_Top_Ten_2014.pdf?raw=true)
* [20150928](https://www.meetup.com/owasp-msp-meetup/events/225096445/): Jay Schulman: Why Security Needs DevOps
* [20150718](https://www.meetup.com/owasp-msp-meetup/events/222867480/): Darren Meyer: Put Down the Megaphone: Effective Security Advocacy Without All The Shouting.
* [20150507](https://www.meetup.com/owasp-msp-meetup/events/221969524/): Igor Matlin: Warning Ahead: Security Storms are brewing in your Javascript
* [20150409](https://www.meetup.com/owasp-msp-meetup/events/221283716/): Gunnar Peterson and Gerry Gebel: Getting the OWASP Top Ten Right with Dynamic Authorization
* [20150316](https://www.meetup.com/owasp-msp-meetup/events/220728619/): Kevin Nassery: Measuring Software Security Programs
* 20111107: Gene Kim - InfoSec in the New World Order: Rugged DevOps and More - [Video](https://youtu.be/p-t8xnuv_ow)
* 20090629: Cassio Goldschmidt: Tracking the Progress of an SDL Program: Lessons from the Gym - [Slides](https://www.slideshare.net/webappsecguy/tracking-the-progress-of-an-sdl-program-lessons-from-the-gym-1684512)


