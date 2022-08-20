---
company: <% tp.file.cursor() %>
business_unit: 
task_tag: 
type: application
---

# [[<% tp.file.title %>]]

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
