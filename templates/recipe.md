---
created: <% tp.file.creation_date() %>
title: <% tp.file.title %>
tags:
  - recipe
draft: true
---
<% await tp.file.move("/content/resources/nutrition/recipes/" + tp.file.title) %>
**Pais**:: 
**Puntuación**:: 
### Informacion

<% tp.file.cursor() %>

---
### Cantidades
- 
---
### Preparacion

---
 > [!info] Ultimas recetas añadidas
>```dataview
Table WITHOUT ID  file.link as "Recipe",Pais, Puntuación FROM #recipe WHERE !draft AND file.name != "<% tp.file.title %>" SORT file.mtime LIMIT 5 
>```



