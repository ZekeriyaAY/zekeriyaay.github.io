---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
icon: "dev"
description: ""
group: "Code"
slug: "{{ .File.BaseFileName }}"
---