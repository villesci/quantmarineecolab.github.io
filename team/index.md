---
title: Team
nav:
  order: 4
  tooltip: About our team
---

# <i class="fas fa-users"></i>Team

Our lab is made up of a collaborative and diverse team of scientists. We value and actively work to create a lab, university, and community that is more diverse, inclusive, and equitable.


{%
  include list.html
  data="members"
  component="portrait"
  filters="role: pi, group: current"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: grad, group: current"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: undergrad, group: current"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: programmer, group: current"
%}

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: mascot, group: current"
%}
{:.center}

{% include section.html %}

There are often openings for graduate students and postdoctoral fellows within the Quantitative Marine Ecology Lab. Please see the link below for more information. 

{%
  include link.html
  icon="fas fa-hands-helping"
  text="Join the Team"
  link="join"
  style="button"
%}
{:.center}

![First team photo](/images/blog_post_images/2021_retreat1.jpg "2021 team photo")

{% include section.html %}





## Funding

Our work is made possible by funding from several organizations.
{:.center}

{%
  include gallery.html
  style="square"

  image1="images/NSF_Logo.png"
  link1="https://www.nsf.gov/"
  tooltip1="National Science Foundation"

  image2="images/Gund_logo.png"
  link2="https://www.uvm.edu/gund"
  tooltip2="Gund Institute"

  image3="images/fulbright-logo.jpg"
  link3="https://cies.org/"
  tooltip3="Fulbright Program"

  image4="images/cdf_logo.jpg"
  link4="https://darwinfoundation.org/en//"
  tooltip4="Charles Darwin Foundation"
  
  image5="images/unh_logo.png"
  link5="https://www.unh.edu/"
  tooltip5="University of New Hampshire"

%}
