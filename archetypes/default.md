---
title: "{{ replace .Name "-" " " | title }}"
tags: []
image: "/blog/{{ path.Base (path.Dir .File.Path)}}/thumb.jpg"
date: "{{ time.Now.Format "2006-01-02" }}"
draft: true
---

