---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
archives: "{{ dateFormat "2006" now }}"
tags: []
author: "{{ .Site.Params.AuthorName }}"
draft: true
---
