---
created: <% tp.file.creation_date() %>
title: <% tp.file.title %>
tags:
  - music
  - artist
draft: true
---
<% await tp.file.move("/content/resources/music/artist/" + tp.file.title) %>

## Información
- **Nombre completo:** <% tp.file.cursor() %> 
- **Nacionalidad:**
- **Genero:** 
- **Album:**
## Notas

