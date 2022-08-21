---
application: <% tp.file.folder() %>
type: application_note
created: <% tp.file.creation_date() %>
---
modified:: <%+ tp.file.last_modified_date("dddd Do MMMM YYYY HH:mm:ss") %>

# [[<%tp.file.folder() %>]] - [[<% tp.file.title %>]]

## Notes

<% tp.file.cursor() %>