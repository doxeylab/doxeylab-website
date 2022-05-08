---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# <i class="fas fa-users"></i>Team

We have been fortunate to have an outstanding team composed of students and researchers at all levels from undergrads to PhD students to Postdocs. We are always looking for new members to join our lab!

{% include section.html %}

## Current members

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: pi"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: postdoc, group: current"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: phd, group: current"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: msc, group: current"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: undergrad, group: current"
%}
{:.center}


## Alumni

Our outstanding lab alumni are listed below, including former graduate students, PDFs, and also undergraduate students that have co-authored publications. If you are missing from this list, apologies, and please let us know.

{% include list.html 
   data="members"
   component="portrait"
   filters="group: alumni"
   style="small"
%}
{:.center}

{% include section.html background="images/banner.jpg" dark=true%}

If you are interested in joining the lab, don't hesitate to contact us. Previous experience in bioinformatics or programming or data science is generally required for bioinformatic-related positions. For wet-lab/experimental positions, a background in molecular or microbiology is recommended.

{% include section.html %}


## Funding

Our work is made possible by funding from several organizations.
{:.center}

{%
  include gallery.html
  style="square"

  image1="images/nserc.png"
  link1="https://www.nserc-crsng.gc.ca/"
  tooltip1="NSERC"

  image2="images/mitacs.png"
  link2="https://www.mitacs.ca/"
  tooltip2="Mitacs"

  image3="images/photo.jpg"
  link3="https://nasa.gov/"
  tooltip3="Cool Initiative"

  image4="images/computecanada.png"
  link4="https://www.computecanada.ca/"
  tooltip4="Compute Canada"

  image5="images/cihr.jpg"
  link5="https://cihr-irsc.gc.ca/"
  tooltip5="CIHR"

  image6="images/SOSCIP.gif"
  link6="https://www.soscip.org/"
  tooltip6="SOSCIP"
%}
