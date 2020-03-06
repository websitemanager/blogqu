---
draft: true
date: {{ .Date }}
title: "{{ replace .Name "-" " " | title }}"
subtitle: ""
seotitle: ""
description : ""
slug: ""
tags:
- linux
categories:
- android
- linux
- raspberrypi
resources:
- src: "cover.jpeg"
  name: "cover"
- src: "*.jpeg"
---

Sampurasun.

***

{{< photo src=".jpeg" alt="" >}}

{{< photo class=fullwidth src=".jpeg" alt="" >}}

{{< photoset max="2" >}}
  {{< photo src=".jpeg" alt="" >}}
  {{< photo src=".jpeg" alt="" >}}
{{</ photoset >}}

{{< photoset max="3" >}}
  {{< photo src=".jpeg" alt="" >}}
  {{< photo src=".jpeg" alt="" >}}
  {{< photo src=".jpeg" alt="" >}}
{{</ photoset >}}

***