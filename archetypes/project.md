---
title: {{ replace .File.ContentBaseName "-" " " | title }}
date: {{ .Date }}
description: {{ replace .File.ContentBaseName "-" " " | title }} is awesome.
keywords: []
params:
    project_home: 'https://example.com'
    project_repo: 'https://github.com/example/example'
---
