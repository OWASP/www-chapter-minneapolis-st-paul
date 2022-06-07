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

## Past meetings

* [20220525](https://www.meetup.com/owasp-msp-meetup/events/285695539/): David Melamed: The OWASP Serverless Security Top 10 as Code - [Video](https://youtu.be/e_2RxD5Mqn4)
* [20220420](https://www.meetup.com/owasp-msp-meetup/events/285130448/): Himanshu Dwivedi: How to Hack an API in 15 minutes!
* [20220323](https://www.meetup.com/owasp-msp-meetup/events/283389664/): Alex Bauert and Nathan Larson: Pen-testing, encryption, open forum
* [20211216](https://www.meetup.com/owasp-msp-meetup/events/282157443/): Alex Bauert and Nathan Larson: The OWASP Top 10, 2021 edition - [Slides](download/20211216_OWASP-MSP_OWASP_Top_Ten_2021.pdf?raw=true)
* [20210727](https://www.meetup.com/owasp-msp-meetup/events/278765243/): Alex Bauert and Nathan Larson: SAST for a Secure Future -- Today - [Slides](download/20210721_OWASP-MSP_SAST_for_a_Secure_Future_--_Today?raw=true)
* [20210211](https://www.meetup.com/owasp-msp-meetup/events/275615353/): Alex Bauert and Nathan Larson: The state of IoT security - [Slides](download/20210211_OWASP-MSP_The_state_of_IoT_security.pdf?raw=true)


