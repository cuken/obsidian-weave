---
company: Bermuda Inc.
location: Bermuda Triangle
title: Manager of the Triangle
email: john@bermudat.com
phone: +55 (123) 456-7890
aliases: Mystery Man
task_tag: john
type: person
---
# [[John Smith]]

## Meetings
```dataview
TABLE summary as "Summary" from [[John Smith]]
where contains(type,"meeting")
sort date desc
```
## Pending Tasks
```tasks
tags include #john
path does not include System
```

## Completed Tasks
```tasks
done
tags include #john
path does not include System
```
