

### Papers

#### Finished Papers
```dataview
table FullScore, MyScore, DateDone
from #Physics  and #Paper
where Done
```
#### Unfinished Papers
```dataview
table QP, MS
from #Physics  and #Paper
where !Done
```
