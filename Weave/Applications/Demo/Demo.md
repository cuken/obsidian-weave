---
company: Bermuda Inc.
business_unit: Mystery Division
task_tag: demo
summary: "What's better than a demo?"
type: application
created: 2022-08-21 11:49
---

# [[Demo]]

```dataview
table type AS "Type", created AS "Created", modified AS "Modified" from "Applications/Demo"
where type != "application"
```

## Meetings

```dataview
TABLE Host, summary as "Summary", date as "Date" from "Meetings"
where contains(Application_Tag,"demo")
sort date desc
```

## Tasks

```tasks

not done
tags include #Demo
path does not include System

```

## Completed Tasks

```tasks

done
tags include #Demo  
path does not include System

```
