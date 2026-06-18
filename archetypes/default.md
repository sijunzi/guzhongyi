+++
date = '{{ .Date | time.Format "2006-01-02 15:04:05" }}'
draft = false
title = '{{ replace .File.ContentBaseName "-" " " | title }}'
slug = "{{ .Date | time.Format "20060102150405" }}"
+++
