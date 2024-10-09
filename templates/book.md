---
created: <% tp.file.creation_date() %>
title: <% tp.file.title %>
tags:
  - books
draft: true
---
<% await tp.file.move("/content/resources/books/" + tp.file.title) %>
