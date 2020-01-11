---
layout: article
title: Site-to-Site VPN
mode: immersive
header:
  theme: dark
article_header:
  type: overlay
  theme: dark
  background_color: '#4c4cc2'
  background_image:
    gradient: 'linear-gradient(313deg, rgba(2,0,36, .6) 0%, rgba(76,76,194, .6) 47%, rgba(0,212,255, .6) 100%)'
    src: https://github.com/alexma2344/sitio/blob/master/assets/images/rainbows.jpg?raw=true"
sharing: true
comment: true
mathjax: true
mathjax_autoNumber: true
articles:
  excerpt_type: html
tags: cisco router vpn ipsec ike
---

<!--more-->

---

## Why?

Because it uses [IPSec](https://en.wikipedia.org/wiki/IPsec#IETF_documentation), and with it can get any two or more subnets next to each other, over the internet or an MPLS cloud.

IPsec is an open framework that allows for the exchange of security protocols as new technologies and
encryption algorithms are developed.

<center><img src="https://github.com/alexma2344/sitio/blob/master/assets/images/ipsec-framework.jpg?raw=true"></center>
<div style="text-align: center;">
    <span style="font-size:11px; color:grey">
        IPSec Framework.
    </span>
</div>

### Documents:

[Best practices, Business scenarios](https://github.com/alexma2344/sitio/blob/master/assets/images/vpn_cg.pdf)

There are two central configuration elements in the implementation of an IPsec VPN:

1. Implement Internet Key Exchange (IKE) parameters.
2. Implement IPsec parameters.

## Configuration

#### Verify reachability between the two sites

### 