- ### [[Chemistry]]
- ### [[Physics]]
- ### [[Computer Science]]
- ### [[Math]]

### Papers to be done
```dataview
table QP, MS, tags[1] as paper
From #Paper
where !Done and length(tags) != 1
```

### Papers Done
```dataview
table DateDone, tags[1] as paper, MyScore*100/FullScore as Score
From #Paper
where done
sort DateDone ASC
```
