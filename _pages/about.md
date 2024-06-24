---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<span class='anchor' id='about-me'></span>

{% include_relative includes/intro.md %}

{% include_relative includes/news.md %}

{% include_relative includes/pubs.md %}

{% include_relative includes/honers.md %}

<br />

<!-- <script type='text/javascript' id='clustrmaps' src='//cdn.clustrmaps.com/map_v2.js?cl=ffffff&w=300&t=tt&d=XbjQrc5aoquCRCPZtmzBPmq7AViRLSFFjRfOnozEBf0&co=2d78ad&ct=ffffff&cmo=3acc3a&cmn=ff5353'></script> -->

<script type='text/javascript'>
  document.addEventListener("DOMContentLoaded", function(){
    var script = document.createElement('script');
    script.type = 'text/javascript';
    script.src = '//cdn.clustrmaps.com/map_v2.js?cl=ffffff&w=300&t=tt&d=XbjQrc5aoquCRCPZtmzBPmq7AViRLSFFjRfOnozEBf0&co=2d78ad&ct=ffffff&cmo=3acc3a&cmn=ff5353';
    script.id = 'clustrmaps';
    document.body.appendChild(script);

    script.onload = function() {
      document.getElementById("clustrmaps").onclick = function(event){
        event.preventDefault();
      };
    };
  });
</script>

<br />