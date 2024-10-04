---
created: <% tp.file.creation_date() %>
title: <% tp.file.title %>
tags:
  - author
draft: true
---

<% await tp.file.move("/content/books/" + tp.file.title) %>