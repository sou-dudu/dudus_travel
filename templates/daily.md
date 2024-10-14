---
created: <% tp.file.creation_date() %>
title: <% tp.file.title %>
tags:
  - daily
draft: true
---
# <% moment(tp.file.title,'YYYY-MM-DD').format("dddd, MMMM DD, YYYY") %>

<< [[<% fileDate = moment(tp.file.title, 'YYYY-MM-DD-dddd').subtract(1, 'd').format('YYYY-MM-DD-dddd') %>|Yesterday]] | [[<% fileDate = moment(tp.file.title, 'YYYY-MM-DD-dddd').add(1, 'd').format('YYYY-MM-DD-dddd') %>|Tomorrow]] >>

---
# Notes
<% tp.file.cursor() %>


# Daily checks
### Sleep:
- [ ] 1-2
- [ ] 3-4
- [ ] 5-6
- [ ] 7-8
- [ ] 9-10
### Breathin exercise
- [ ] Morning
- [ ] Afternoon
- [ ] Night
### Reflection
