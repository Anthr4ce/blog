# archetypes/writeup.md
---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
tags: [ "{{ .Section | lower }}", "{{ .File.Dir | path.Base | lower }}", "writeup" ]
draft: false
---

