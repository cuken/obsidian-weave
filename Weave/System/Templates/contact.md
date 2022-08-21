---
company: <% tp.file.cursor() %>
location:
title:
email:
phone: 
aliases:
task_tag: <% tp.file.title.split(" ")[0].toLowerCase() %>
type: person
---
# [[<% tp.file.title %>]]

## Meetings
```dataview
TABLE summary as "Summary" from [[<% tp.file.title %>]]
where contains(type,"meeting")
sort date desc
```
## Pending Tasks
```tasks
tags include #<% tp.file.title.split(" ")[0].toLowerCase() %>
path does not include System
```

## Completed Tasks
```tasks
done
tags include #<% tp.file.title.split(" ")[0].toLowerCase() %>
path does not include System
```