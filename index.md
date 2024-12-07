---

layout: col-sidebar
title: OWASP Minneapolis/St. Paul
tags: MSP

region: North America

auto-migrated: 0
meetup-group: OWASP-MSP-Meetup
country: USA
postal-code: 55101

---
## Welcome
Welcome to the OWASP chapter local to the Minneapolis / St. Paul area of Minnesota.

* Meeting locations vary. Please reference our [Meetup page](https://www.meetup.com/OWASP-MSP-Meetup) for announcements. 
* Everyone is welcome to join us at our chapter meetings; security professionals, software developers, project managers, everyone!

## Participation
The Open Web Application Security Project (OWASP) is a nonprofit foundation that works to improve the security of software. All of our projects, tools, documents, forums, and chapters are free and open to anyone interested in improving application security. 

Chapters are led by local leaders in accordance with the [Chapter Policy](https://owasp.org/www-policy/). Financial contributions should only be made online using the authorized online donation button. To be a **speaker** at **any** OWASP Chapter in the world,  review the [speaker agreement](https://owasp.org/www-policy/legal/speaker-agreement) and then contact the local chapter leaders (see the right panel of this page) with details of what OWASP Project, independent research, or related application security topic you would like to present.

Everyone is welcome and encouraged to participate in our [Projects](/projects), [Local Chapters](/chapters), [Events](/events), [Online Groups](https://groups.google.com/a/owasp.com/), and [Community Slack Channel](https://owasp.slack.com/). We especially encourage diversity in all our initiatives. OWASP is a fantastic place to learn about application security, to network, and even to build your reputation as an expert. We also encourage you to [become a member](/membership) or consider a [donation](/donate) to support our ongoing work.

## Upcoming events:
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
