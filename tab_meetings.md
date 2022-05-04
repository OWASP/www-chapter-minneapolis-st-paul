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

6pm 25 May 2022:
OWASP-MSP May meet: OWASP Serverless Security Top 10 as Code
In-person: https://www.meetup.com/OWASP-MSP-Meetup/events/285695472/
On-line: https://www.meetup.com/OWASP-MSP-Meetup/events/285695539/

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

## Past few meetings

* 20 April 2022: How to Hack an API in 15 minutes!
* 23 March 2022: Open forum on appsec
* 16 Dec. 2021: The OWASP Top 10, 2021 ed

