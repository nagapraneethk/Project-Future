# Home

## Today
```dataview
TABLE created
FROM "Daily"
SORT file.name DESC
LIMIT 1
```

## Active Projects
```dataview
TABLE status, priority
FROM "04 Projects"
WHERE type="project" AND status!="completed"
```

## Recent Sessions
```dataview
TABLE project, created
FROM "03 Sessions"
WHERE type="session"
SORT created DESC
LIMIT 5
```
