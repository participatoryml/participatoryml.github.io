---
layout: landing
title: Participatory Approaches to Machine Learning
subtitle: ICML 2020 Workshop (July 17)
---
{% assign papers = site.data.papers_2020 %}

Because of the SARS-CoV-2/COVID-19 pandemic, the workshop will take place virtually.
The exact format will be based on the [ICML conference guidelines](https://icml.cc/Conferences/2020/VirtualICML).

ICML Virtual Site: [icml.cc/virtual/2020/workshop/5720](https://icml.cc/virtual/2020/workshop/5720)

## Overview

The designers of a machine learning (ML) system typically have far more power
over the system than the individuals who are ultimately impacted by the system
and its decisions. Recommender platforms shape the users' preferences; the
individuals classified by a model often do not have means to contest a decision;
and the data required by supervised ML systems necessitates that the privacy and
labour of many yield to the design choices of a few.

The fields of algorithmic fairness and human-centered ML often focus on
centralized solutions, lending increasing power to system designers and
operators, and less to users and affected populations. In response to the
growing social-science critique of the power imbalance present in the research,
design, and deployment of ML systems, we wish to consider a new set of technical
formulations for the ML community on the subject of more democratic,
cooperative, and participatory ML systems.

Our workshop aims to explore methods that, by design, enable and encourage the
perspectives of those impacted by an ML system to shape the system and its
decisions. By involving affected populations in shaping the goals of the overall
system, we hope to move beyond just tools for enabling human participation and
progress towards a redesign of power dynamics in ML systems.

### Topics

We invite work that makes progress on the workshop themes, including but not
limited to:

-   **Recourse and reachability**: Creating systems that ensure the user
    has the potential to adapt their predictions or recommendations
    ([Ustun, Spangher, and Liu 2019](https://arxiv.org/abs/1809.06514);
    [Dean, Rich, and Recht 2020](https://arxiv.org/abs/1912.10068)).

-   **Richer interactive ML:** Incorporating richer user feedback into
    ML systems. Limitations of current methods in fully capturing a
    user’s ‘preferences’
    ([Schnabel, Bennett, and Joachims 2018](https://arxiv.org/abs/1802.07578);
    [Yang et al. 2019](http://ceur-ws.org/Vol-2327/IUI19WS-ExSS2019-9.pdf))

-   **Mechanism design or computational social choice and learning**:
    designs that incorporate preference elicitation in allocative ML
    systems, such as adaptive experimentation or learning-based
    algorithmic governance
    ([Narita 2019](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3094905);
    [M. K. Lee et al. 2019](https://www.cs.cmu.edu/~akahng/papers/webuildai.pdf);
    [Kahng et al. 2019](http://proceedings.mlr.press/v97/kahng19a.html))

-   **Collective and participatory design applied to community
    involvement in ML:** Qualitative and quantitative methods and
    frameworks aimed at giving a voice to communities affected by ML
    systems. Tools for collective training processes and collective
    design of ML systems
    ([Katell et al. 2020](https://people.csail.mit.edu/pkrafft/papers/critplat-toolkit-lessons.pdf);
    [Brown et al. 2019](https://www.andrew.cmu.edu/user/achoulde/files/accountability_final_balanced.pdf);
    [Halfaker and Geiger 2019](https://arxiv.org/abs/1909.05189);
    [Patton et al. 2020](https://dl.acm.org/doi/10.1145/3375627.3375841)).

-   **Deferral and/or abstention**: Classification frameworks which
    incorporate deferral to humans, or at least a non-classification
    outcome.
    ([Madras, Pitassi, and Zemel 2018](https://arxiv.org/abs/1711.06664);
    [El-Yaniv and Wiener 2010](http://jmlr.csail.mit.edu/papers/volume11/el-yaniv10a/el-yaniv10a.pdf)).

-   **Documentation & audit methods:** Work which is intended to inform
    and engage users in model design, development or deployment
    processes and its limitations
    ([Raji et al. 2020](https://arxiv.org/abs/2001.00973);
    [Mitchell et al. 2019](https://arxiv.org/abs/1810.03993)).

-   **Contestation:** Technological methods and tools for
    analyzing/protesting/contesting the outcomes of ML systems in the
    absence of centralized cooperation 
    ([Kulynych & Overdorf et al. 2020](https://arxiv.org/abs/1806.02711)).

-   **Analysis or audits of amplifiers of systemic injustice in decision systems**
    ([Arnold et al. 2020](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3580557);
    [Pierson et al. 2020](https://www.nature.com/articles/s41562-020-0858-1);
    [Obermeyer et al. 2019](https://science.sciencemag.org/content/366/6464/447);
    [Ali & Sapieżyński et al. 2019](https://arxiv.org/abs/1904.02095);
    [Raji and Buolamwini 2019](https://www.media.mit.edu/publications/actionable-auditing-investigating-the-impact-of-publicly-naming-biased-performance-results-of-commercial-ai-products/);
    [Buolamwini and Gebru 2018](http://proceedings.mlr.press/v81/buolamwini18a.html?mod=article_inline)).

-   **Tools that support community and worker organization**
    ([Matias and Mou 2018](https://natematias.com/media/Community_Led_Experiments-CHI_2018.pdf);
    [Irani and Silberman 2013](http://crowdsourcing-class.org/readings/downloads/ethics/turkopticon.pdf);
    [Salehi et al. 2015](https://hci.stanford.edu/publications/2015/dynamo/DynamoCHI2015.pdf)).

## Schedule

The central part of our workshop is the [livestream on the ICML virtual
site](https://icml.cc/virtual/2020/workshop/5720). The livestream will broadcast invited talks and
panels, as well as the latest announcements and possible schedule changes. The interactive
discussions with other participants---poster and breakout sessions---will happen on our Discord server.

{% include schedule.html data=site.data.schedule_2020 %}

## Poster Sessions

Each contributed paper has its own audio/video channel on our Discord server.
During the "poster" session, participants can discuss the paper with its authors in the respective channel.
_Before joining a channel as a participant, please make sure to familiarize yourself with the paper
and watch the paper's short introduction video._

### Poster Session 1 (<span class="timespan">2:45 PM - 3:30 PM UTC</span>)

{% include poster-list.html session="am" %}

### Poster Session 2 (<span class="timespan">6:30 PM - 7:15 PM UTC</span>)

{% include poster-list.html session="am" %}

## Breakout Sessions

On our Discord server, you can chat with other workshop participants at any time in thematic text or
audio/video channels; we will add channels during the day if topics come up. In addition to this, as an
experiment, we will hold two thematic discussion sessions guided by facilitators:

### Breakout Session 1 (<span class="timespan">3:30 PM - 4:15 PM UTC</span>)

* **Community Organization and ML Systems.** Facilitated by Seda Gürses.
* **Stakeholder Engagement in System Design**. Facilitated by Haiyi Zhu.
* **Recourse**. Facilitated by Kristen Vaccaro.

### Breakout Session 2 (<span class="timespan">8:00 PM - 8:45 PM UTC</span>)

* **Community Organization and ML Systems**. Facilitated by David Robinson.
* **Interactive ML**. Facilitated by Sarah Dean.

## Contributed Papers
The contributed papers include both novel research papers as well as papers that have already been
published in other venues (marked as "Encore").

### Qualitative frameworks, methods, and analyses

{% assign cat_papers = papers | where: "category", "Qual" %}
{% for paper in cat_papers %}
{% include paper-box.html paper=paper %}
{% endfor %}

### Algorithmic approaches and quantitative methods

{% assign cat_papers = papers | where: "category", "Quant" %}
{% for paper in cat_papers %}
{% include paper-box.html paper=paper %}
{% endfor %}

### Applications

{% assign cat_papers = papers | where: "category", "Applications" %}
{% for paper in cat_papers %}
{% include paper-box.html paper=paper %}
{% endfor %}

### Critical examinations

{% assign cat_papers = papers | where: "category", "Critical" %}
{% for paper in cat_papers %}
{% include paper-box.html paper=paper %}
{% endfor %}

### Policy

{% assign cat_papers = papers | where: "category", "Policy" %}
{% for paper in cat_papers %}
{% include paper-box.html paper=paper %}
{% endfor %}

## Invited Speakers

* [Nicolas Papernot](https://www.papernot.fr/), University of Toronto/Vector Institute
* [Alexandra Chouldechova](https://www.andrew.cmu.edu/user/achoulde/), Carnegie Mellon University
* [Tawana Petty](https://pacscenter.stanford.edu/person/tawana-petty/), [Detroit Community Technology
  Project](https://detroitcommunitytech.org/)
* [Berk Ustun](https://www.berkustun.com/), Harvard University
* [Aleksandra Korolova](https://www.korolova.com/), University of Southern California
* [Piotr Sapieżyński](https://www.sapiezynski.com/), Northeastern University
* [Jamelle Watson-Daniels](https://www.jamellewd.com), [Data for Black Lives](http://d4bl.org/)

## Call for Participation
We would like to experiment with breakout discussions to encourage group discussions around shared
topics of interest. Please fill out our [this form](https://forms.gle/JSbGqznGjZRrv1Sd9) if you are
interested in joining or organizing such a discussion.

## Call for Papers

The workshop will include contributed papers. All accepted papers will be
allocated either a virtual poster presentation, or a virtual talk slot. We will
not publish proceedings, but will optionally link the papers and talk recordings
on the workshop website.

We invite submissions in two tracks:

* **Research Track.** Full papers, works-in-progress, position papers, and case studies. We expect
  that these submissions introduce novel ideas or results.

  The papers should have up to 4 pages (excluding references, acknowledgements, or appendices), and
  be formatted using the [ICML submission
  template](https://media.icml.cc/Conferences/ICML2020/Styles/icml2020_style.zip). Papers should be
  anonymized.

* **Encore Track.** Papers that have already been accepted at other venues.

  There are no format requirements for this track. The papers should be accepted
  at another recognized archival conference or journal, and be submitted by one
  of the paper's authors.

Submissions are currently closed.

For any questions, please send us an email to `participatory-ml-organizers` at `lists.mayfirst.org`

## Timeline

* Submission deadline: ~~**June 22, 2020, AoE**~~
* Notification: ~~**July 1, 2020**~~
* Workshop: July 17, 2020

## Organizing Committee
* [Angela Zhou](https://people.orie.cornell.edu/az434/), Cornell University
* [David Madras](http://www.cs.toronto.edu/~madras/), University of Toronto
* [Inioluwa Deborah Raji](https://ainowinstitute.org/people/deborah-raji.html), AI Now Institute
* [Bogdan Kulynych](https://bogdankulynych.me), EPFL
* [Smitha Milli](http://smithamilli.com), UC Berkeley
* [Richard Zemel](https://www.cs.toronto.edu/~zemel), University of Toronto

## Funding assistance

We are grateful to [Open Philanthropy](https://www.openphilanthropy.org/)
for providing funding assistance for the workshop. If you want to participate in the workshop and
require funding, please write us an email to `participatory-ml-organizers` at `lists.mayfirst.org`
