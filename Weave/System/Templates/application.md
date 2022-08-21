---
company: <% tp.file.cursor() %>
business_unit: 
task_tag:
summary: 
type: application
created: <% tp.file.creation_date() %>
---

# [[<% tp.file.title %>]]

```dataview
table type AS "Type", created AS "Created", modified AS "Modified" from "Applications/<% tp.file.title %>"
where type != "application"
```

## Tasks

```tasks

not done
tags include #<% tp.file.title %>
path does not include System

```

## Completed Tasks

```tasks

done
tags include #<% tp.file.title %>  
path does not include System

```
