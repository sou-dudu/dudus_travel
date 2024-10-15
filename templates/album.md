---
title: <% tp.file.title %>
created: <% tp.file.creation_date() %>
draft: 
tags:
  - album
  - music
---
<% await tp.file.move("/content/resources/music/album/" + tp.file.title) %>

**Artist**:: <% tp.file.cursor() %>
**Genere**::
**Año**::

---
### Notas
- 

---
 > [!info] Ultimas recetas añadidas
>```dataview
Table WITHOUT ID  file.link as "Album",Artista, Genero, Año FROM #album  WHERE !draft AND file.name != "<% tp.file.title %>" SORT file.mtime LIMIT 5 
>```



