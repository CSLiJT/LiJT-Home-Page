---
title: {{ title }}
date: {{ date }}
tags:
categories:
mathjax: false
codeblock:
  enable: true
  show_result: true
---

<!--more-->

<section class="post-full-comments">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/gitalk@1/dist/gitalk.css">
    <script src="https://cdn.jsdelivr.net/npm/gitalk@1/dist/gitalk.min.js"></script>
    <div id="gitalk-container"></div>
    <script>
        var gitalk = new Gitalk({
            clientID: 'e1bbf465a324641f76ce',
            clientSecret: 'b865ad952a6494eb48283884abbe479d3f89f4a4',
            repo: 'LiJT-Daily-Comments',
            owner: 'CSLiJT',
            admin: ['CSLiJT'], //这里可以填写具有写权限的用户名列表，用来初始化Issues的
            id: decodeURI(window.location.pathname),
            distractionFreeMode: true // Facebook-like distraction free mode
        });
        gitalk.render('gitalk-container');
    </script>
</section>