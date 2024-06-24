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
document.addEventListener("DOMContentLoaded", function() {
  var script = document.createElement('script');
  script.type = 'text/javascript';
  script.src = '//cdn.clustrmaps.com/map_v2.js?cl=ffffff&w=300&t=tt&d=XbjQrc5aoquCRCPZtmzBPmq7AViRLSFFjRfOnozEBf0&co=2d78ad&ct=ffffff&cmo=3acc3a&cmn=ff5353';
  script.id = 'clustrmaps';
  document.body.appendChild(script);

  // 监听 document 的点击事件
  document.addEventListener('click', function(event) {
    var target = event.target;

    // 检查点击事件是否来自于地图插件或其内部元素
    while (target) {
      if (target.id === 'clustrmaps' || target.closest('#clustrmaps')) {
        // 阻止默认行为和事件冒泡
        event.preventDefault();
        event.stopPropagation();
        return;
      }
      target = target.parentElement;
    }
  }, true); // 使用捕获模式以确保事件在到达目标之前被捕获
});
</script>

<br />