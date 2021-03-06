---
title: Computational Synthesis Institute
venue1: SESYNC
address1: 1 Park Place, Annapolis MD
country: United-States
humandate: Jul 26-29, 2016
humantime: 9:00 am - 5:00 pm
startdate: 2016-07-26
enddate: 2016-07-29
registration: closed
instructor: ["Ian Carroll", "Kelly Hondula", "Philippe Marchand", "Mary Shelley"]
assistant: ["Kate Weiss"]
contact: icarroll@sesync.org
twitter:
 - csisesync
 - 755481646099492864
etherpad: https://public.etherpad-mozilla.org/p/sesync-comp-institute-july-16
download: http://sesync.us/fs
data2doc: data2doc.html
github: true
---

[//]: # " Edit the values in the parameter block above to be appropriate for your bootcamp. "
[//]: # " Please use three-letter month names for the 'humandate' field. "

## Table of Contents
{:.no_toc}

* TOC
{:toc}

## General Information

This summer's Computational Institute will provide science teams from the socio-environmental synthesis community with hands-on training in open source tools for collaborative coding and data management, analysis, visualization, and dissemination.
The goals of the workshop are to learn new concepts, skills and approaches for data-driven research, advance work on team projects, and become familiar with tools compitible with the cyberinfrastructure available at most research institutions.

[//]: # " This block displays the instructors' names if they are available. "

{% if page.instructor %}
  **Instructors:**  
  {{page.instructor | join: ', ' }}
{% endif %}
{% if page.assistant %}
  **Assistant:**  
  {{page.assistant | join: ', ' }}
{% endif %}

[//]: # " Modify this block to reflect the target audience for your bootcamp. "
[//]: # " In particular, if it is only open to people from a particular institution, "
[//]: # " or if specialized prerequisite knowledge is required, please mention that. "

[//]: # " This block displays the address and links to a map showing directions. "
{% if page.latlng %}
  **Where:**  
  {{ page.address }}.
{% endif %}

[//]: # " Modify the block below if there are any special requirements. "

**Requirements:**  
Participants must bring a laptop.

[//]: # " The following block automatically inserts a contact email address if one has been specified for the page. "
[//]: # " If one hasn't, this block inserts the generic contact address for Software Carpentry. "

{% capture mailto %}
  {% if page.contact %}
    <a href='mailto:{{page.contact}}'>{{page.contact}}</a>
  {% else %}
    <a href='mailto:{{site.contact}}'>{{site.contact}}</a>
  {% endif %}
{% endcapture %}
**Contact:**  
Please email *{{ mailto | strip }}* with any questions and for information not covered here.

## Acknowledgements & Support
Portions of the instructional materials are adopted from [Data Carpentry](http://www.datacarpentry.org){:target="_blank"} and [Software Carpentry](http://software-carpentry.org){:target="_blank"}.
The structure of the curriculum as well as the teaching style are informed by [Software Carpentry](http://software-carpentry.org){:target="_blank"}.


[//]: # " Edit this block to show the syllabus and schedule for your bootcamp. "

## Schedule

**Plenary sessions begin promptly at 9:00 am.** Come prepared to survive until the first coffee break at 10:30 am and on-site lunch provided by SESYNC at 12:30 pm. Trainees are responsible for their own breakfast and dinner arrangements (we can make recommendations).

| Tuesday   | 9:00 am    | Welcome and Overview of SESYNC                                       |
|           | 9:15       | [Collaborative & Reproducible Workflows]                             |
|           | *10:30*    | *Break*                                                              |
|           | 10:45      | [Data Storage and Access for All]                                    |
|           | *12:30 pm* | *Lunch*                                                              |
|           | 1:30       | Introduce 'data2doc' Project & Team Meetings                         |
|           | *3:30*     | *Break*                                                              |
|           | 4:00       | One Hour Language                                                    |
|           |            | choose **one** *new* language: [R], [Python], [SQL], or [JavaScript] |
|           | *5:00*     | *Reception (informal with snacks, tasty beverages, etc.)*            |
| Wednesday | 9:00 am    | [The Landscape of Spatial Data Tools]                                |
|           | *10:30*    | *Break*                                                              |
|           | 10:45      | Scripting Geospatial Analysis                                        |
|           | *12:30 pm* | *Lunch*                                                              |
|           | 1:30       | [Geospatial Packages in R]                                           |
|           | *3:30*     | *Break*                                                              |
|           | 3:45       | Coaching Sessions                                                    |
| Thursday  | 9:00 am    | [Version Control & Data Provenance]                                  |
|           | *10:30*    | *Break*                                                              |
|           | 10:45      | [Shiny Apps]                                                         |
|           | *12:30 pm* | *Lunch*                                                              |
|           | 1:30       | Coaching Sessions                                                    |
|           | *3:30*     | *Break*                                                              |
|           | 3:45       | [Data Manipulation in R]                                             |
| Friday    | 9:00 am    | Coaching Sessions and ad-hoc Plenary                                 |
|           | 12:00 pm   | Wrap-up and Review                                                   |
|           | *12:30*    | *Lunch*                                                              |
|           | 1:30       | Presentation of "data2doc" documents                                 |
{:.table .table-striped}
[//]: # " Add .disable-links to classes to disable links"

## Pre-Arrival Installations & Downloads

To participate, you will need working copies of the software described below.
Please make sure to install everything **before** the start of the short course.

[//]: # " Choose or create setup instructions in _includes to reflect your bootcamp. "

{% include setup-non-sesync.md %}

[//]: # " Hyperlinks "

[Geospatial Packages in R]: {{ site.gh-pages }}/geospatial-packages-in-R-lesson{{ page.date | date: "/%Y/%m/%d/" }}
[Scripting Geospatial Analysis]: {{ site.gh-pages }}/basic-PyQGIS-lesson{{ page.date | date: "/%Y/%m/%d/" }}
[Version Control & Data Provenance]: {{ site.gh-pages }}/vcdp-lesson{{ page.date | date: "/%Y/%m/%d/" }}
[The Landscape of Spatial Data Tools]: {{ site.gh-pages }}/osgeo-lesson{{ page.date | date: "/%Y/%m/%d/" }}
[Data Storage and Access for All]: {{ site.gh-pages }}/introdb-lesson{{ page.date | date: "/%Y/%m/%d/" }}
[Collaborative & Reproducible Workflows]: {{ site.gh-pages }}/basic-git-lesson{{ page.date | date: "/%Y/%m/%d/" }}
[Shiny Apps]: {{ site.gh-pages }}/basic-Shiny-lesson{{ page.date | date: "/%Y/%m/%d/" }}
[Data Manipulation in R]: {{ site.gh-pages }}/data-manipulation-in-R-lesson{{ page.date | date: "/%Y/%m/%d/" }}
[R]: {{ site.gh-pages }}/basic-R-lesson{{ page.date | date: "/%Y/%m/%d/" }}
[Python]: {{ site.gh-pages }}/basic-Python-lesson{{ page.date | date: "/%Y/%m/%d/" }}
[SQL]: {{ site.gh-pages }}/basic-SQL-lesson{{ page.date | date: "/%Y/%m/%d/" }}
[JavaScript]: {{ site.gh-pages }}/basic-JavaScript-lesson{{ page.date | date: "/%Y/%m/%d/" }}
