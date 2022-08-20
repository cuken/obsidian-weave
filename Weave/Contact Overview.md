---
tags: contact
---

# [[Contact Overview]]

> [!info] Getting Started
> This note will display a lit of all of the contacts within your vault. Review the query below if you want to include / exclude any fields.

>[!tip]
> If you add any new metadata to your contacts, make sure you update the [[Templates/Contact]] note as well to include the metadata change on all future creations.

```dataview
TABLE
  company as "Company",
  title as "Title",
  email as "Email",
  cell as "Cell"
from "Contacts"
```
