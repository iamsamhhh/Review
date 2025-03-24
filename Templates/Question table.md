```dataview
table mark, difficulty, content
from #<% tp.file.cursor() %>
where contains(tags, "Question")
```
