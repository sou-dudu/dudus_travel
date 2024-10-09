---
created: <% tp.file.creation_date() %>
title: <% tp.file.title %>
tags:
  - plant
draft: true
---
<% await tp.file.move("/content/resources/plants/" + tp.file.title) %>
- **Nombre Común:** <% tp.file.cursor() %>
- **Nombre Científico:** 
- **Familia:**
- **Características Físicas:** 
- **Hábitat:** 
- **Usos:** 
- **Época de Floración:** 
