---
layout: page
title: Submissions
---

## Tracks

Papers can be submitted to one of three tracks ([IPAW](#ipaw), [TaPP](#tapp), [demonstration and poster](#demonstrations-and-posters)). <!-- Boris: check first. All papers will be published as [LIPIcs proceedings](https://www.dagstuhl.de/en/publications/lipics/). -->
Furthermore, we are soliciting proposals for [co-located events and workshops](#proposals-for-workshops-and-co-located-events).

### IPAW

Authors are invited to submit original research work the IPAW track. This track solicits full research papers that describe mature, high-quality research on the topics of interest of the Provenance Week. Papers submitted to IPAW are expected to have some form of initial validation, such as a case study or preliminary experiments showing the feasibility of the proposed approach.

Papers must be:
- not published or under review elsewhere
- no longer than 10 pages + references
  - that is, references  do not count on the page limit - feel free to include as many references as required
- formatted according to the LIPIcs guidelines:
  - [LIPIcs author guidelines](https://www.dagstuhl.de/en/publications/lipics/instructions-for-authors/)
- submitted as PDF files to the IPAW track at:
  - [IPAW track submission site](https://www.)

Important Dates:
{% assign deadlines = site.data.dates.paper_types | where:"name","Papers (IPAW and TaPP tracks)" | first %}
{% for d in deadlines.dates %}
- **{{ d.event }}**: {{ d.date }}
{% endfor %}



### TaPP

The TaPP track continues the tradition of TaPP to provide a genuine workshop environment for discussing and developing new ideas and exploring connections between disciplines and between academic research on provenance and practical applications.

We invite innovative and creative contributions, including papers outlining new challenges for provenance research, promising formal approaches to provenance, innovative use of provenance, experience-based insights, resourceful experiments, and visionary (and possibly risky) ideas. The provenance community is very diverse, we therefore strongly encourage authors to contextualise their work.

Papers must be:
- not published or under review elsewhere
- no longer than 8 pages
- formatted according to the LIPIcs guidelines:
  - [LIPIcs author guidelines](https://www.dagstuhl.de/en/publications/lipics/instructions-for-authors/)
- submitted as PDF files to the TaPP track at:
  - [TaPP track submission site](https://www.)

Important Dates:
{% assign deadlines = site.data.dates.paper_types | where:"name","Papers (IPAW and TaPP tracks)" | first %}
{% for d in deadlines.dates %}
- **{{ d.event }}**: {{ d.date }}
{% endfor %}



### Demonstrations and Posters

ProvenanceWeek encourages the presentation of posters and
demonstrations. Proposals for posters and demonstrations should be limited to a
short description. For posters please describe the poster content and research
problem. For demonstrations clearly indicate what is going to be demonstrated,
the significance of the research contribution, and/or applications. Accepted
posters and demonstrations will be presented during a separate session at the
workshop.

Demo and poster proposal must be:
- no longer than 2 pages
- formatted according to the LIPIcs guidelines:
  - [LIPIcs author guidelines](https://www.dagstuhl.de/en/publications/lipics/instructions-for-authors/)
- submitted as PDF files to the demo/poster track at:
  - [demo/poster track submission site](https://www.)
- poster authors must also submit a preliminary version of the poster as a supplementary file

Important Dates:
{% assign deadlines = site.data.dates.paper_types | where:"name","Demos and Posters" | first %}
{% for d in deadlines.dates %}
- **{{ d.event }}**: {{ d.date }}
{% endfor %}



## Submission Site

Papers are submitted using the HotCRP system.

- **Submission site**: [{{ site.data.conference.submission_site }}]({{ site.data.conference.submission_site }})

## Topics

- Provenance visualization, and human interaction with provenance
- Provenance for big data and extreme computing
- Provenance for attribution and trust
- Provenance for transparency and accountability
- Security and privacy implications of provenance
- Provenance, social media, and the semantic web
- Provenance analytics, discovery, and reasoning about provenance and its quality
- Data sharing and data citation
- Provenance of workflows and annotations
- Standardization of provenance models, services, and representations
- Provenance management system prototypes and commercial solutions
- Applications of provenance in real-life settings
- Theoretical foundations of provenance
- Connections between provenance and established topics in other research fields
- (programming languages, security, software engineering, fairness, etc.)
- Provenance-based audit and forensics
- Design, performance and scalability of provenance systems

## Proposals for Workshops and Co-located Events

We are looking for a small number of original and high-quality events, which
focus on novel and visionary directions for provenance. Such events should seek
to welcome work in progress that is not prime for proper refereed publications.

Events that help broaden the community and increase its impact are particularly
welcome. Examples of co-located events include tutorials, challenges, and
discussions on specific topics. Co-located events should not issue formal calls
for papers and should not have formal proceedings (since papers should be sent
to IPAW or TAPP). Co-located events can be half a day or a full day.

If you are interested in organizing a co-located event at Provenance Week,
please send an email to <a href="mailto:%62%67%6C%61%76%69%63@%69%69%74.%65%64%75">[bglavic] at [iit] o [edu]</a> with:
- event title
- event aims
- organizers
- proposed format
- duration
- how it helps broaden community and increase impact

Important Dates:
{% assign deadlines = site.data.dates.paper_types | where:"name","Workshop and Co-located Event Proposals" | first %}
{% for d in deadlines.dates %}
- **{{ d.event }}**: {{ d.date }}
{% endfor %}