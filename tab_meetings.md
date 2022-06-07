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

* 20220525: David Melamed: The OWASP Serverless Security Top 10 as Code - [Details](https://www.meetup.com/owasp-msp-meetup/events/285695539/) - [Video](https://youtu.be/e_2RxD5Mqn4)
* 20220420: Himanshu Dwivedi: How to Hack an API in 15 minutes! - [Details](https://www.meetup.com/owasp-msp-meetup/events/285130448/)
* 20220323: Alex Bauert and Nathan Larson: Pen-testing, encryption, open forum - [Details](https://www.meetup.com/owasp-msp-meetup/events/283389664/)
* 20211216: Alex Bauert and Nathan Larson: The OWASP Top 10, 2021 edition - [Details](https://www.meetup.com/owasp-msp-meetup/events/282157443/)
* 20210727: Alex Bauert and Nathan Larson: SAST for a Secure Future -- Today - [Details](https://www.meetup.com/owasp-msp-meetup/events/278765243/)
* 20210211: Alex Bauert and Nathan Larson: The state of IoT security - [Details](https://www.meetup.com/owasp-msp-meetup/events/275615353/)


