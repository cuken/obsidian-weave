---
tags: application overview
---

# [[Application Overview]]

> [!info] Getting Started
> This note will display a table of all of your Applications, what Business Unit it belongs to, and any relevant Task Tag's associated with it. Please refer to the documentation on the useage of 'Task Tag' in Weave.

> [!tip]
> Consider modifying the query below to pull the metadata for each application that matters to you.

```dataview
table company as "Company", business_unit as "Business Unit", task_tag as "Task Tag", summary as "Summary" from "Applications"
```
