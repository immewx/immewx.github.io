---
title: Hello World (updated)
description: Welcome to Hugo Theme Stack
slug: hello-world
date: 2022-03-06 00:00:00+0000
image: cover.jpg
categories:
    - Example Category
tags:
    - Example Tag
weight: 1       
---

Welcome to Hugo theme Stack. This is your first post. Edit or delete it, then start writing!

For more information about this theme, check the documentation: https://stack.jimmycai.com/

Want a site like this? Check out [hugo-theme-stack-stater](https://github.com/CaiJimmy/hugo-theme-stack-starter)

> Photo by [Pawel Czerwinski](https://unsplash.com/@pawel_czerwinski) on [Unsplash](https://unsplash.com/)

**User Agent:**
<div id="user-agent"></div>

<script>
  fetch('https://demo-agent.mewx.workers.dev/')
    .then(response => response.text())
    .then(userAgent => {
      document.getElementById('user-agent').textContent = userAgent;
    })
    .catch(error => console.error('Error fetching user agent:', error));
</script>
