---
tags: ['Class', '<%+ tp.file.title %>']
PageType: 'Class'
HitDie: 'd4'
Type: 'Martial'
Skills: 0
BAB: 0
BDE: 0
share: true
---
```js
<% await tp.file.move("/docs/Classes/" + tp.file.title + "/" + tp.file.title) %>
```
## Class Details
Hit Die:  <%+ tp.frontmatter.HitDie %>
Type: <%+ tp.frontmatter.Type %>
Skill Ranks Per Level: <%+ tp.frontmatter["Skills"] %> + Int modifier

