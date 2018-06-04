---
published: true
layout: page
permalink: gratitude/

organizations:
    b2p:
        img: "/img/logos/b2p.png"
        url: "http://bridgestoprosperity.org"
    eef:
        img: "/img/logos/eef.png"
        url: "http://eef.colorado.edu"
    eia:
        img: "/img/logos/eia.png"
        url: "http://engineersinaction.org"
    microprojects:
        img: "/img/logos/microprojects.jpg"
        url: "http://microprojects.co.sz"
        
companies:
    msa:
        img: "/img/logos/msa.png"
        url: "http://msasafety.com"
    geohydro:
        img: "/img/logos/geohydro.jpg"
        url: "http://geohydro.com"
    hdr:
        img: "/img/logos/hdr.png"
        url: "http://hdr.org"
---

![Kids on Finished Bridge]({{ "/img/edlangeni-kids.jpg" | prepend:site.baseurl }})

Our bridge projects would have never happened had it not been for some special individuals with a collective vision. Together, we connect eager students with communities in need, and realize a powerful transformation in the lives of all those involved. 

We are grateful for all those who have helped our bridge projects, and from all of us at CUB2P we would like to express our appreciation.

### Organization Supporters
Thank you to all of these organizations who are the backbone of what makes this all possible.

<div class="supporters">
{% for supporter in page.organizations %}
   <a href="{{supporter[1].url}}">
       <img src="{{site.baseurl}}{{supporter[1].img}}">
   </a>
{% endfor %}
</div>

### Company Sponsors
Thank you to all of companies who have generously donated equipment, money, and services to help us.

<div class="supporters">
{% for supporter in page.companies %}
   <a href="{{supporter[1].url}}">
       <img src="{{site.baseurl}}{{supporter[1].img}}">
   </a>
{% endfor %}
</div>

### Individual Supporters
Thank you to all of the private donors who have contributed to our crowdfund, or have otherwise supported us financially.

## Sincerely,

<span class="indented">
all of us at CUB2P
</span>
