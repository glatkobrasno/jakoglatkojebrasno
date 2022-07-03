---
title: "{{ replace .Name "-" " " | title }}"

date: {{ .Date }}
url: /{{ .Name }}/
image: images/thumbs/{{ .Name }}.jpg
categories:
  - c1
tags:
  - t1
draft: true
---

