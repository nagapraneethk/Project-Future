# 🏠 Home

## Today's Note
```dataview
LIST
FROM "Daily"
SORT file.name DESC
LIMIT 1
```

## Active Projects
```dataview
TABLE status, priority
FROM "04 Projects"
WHERE type="project" AND status="active"
```

## Recent Sessions
```dataview
TABLE project, created
FROM "03 Sessions"
WHERE type="session"
SORT created DESC
LIMIT 10
```

## Recent Ideas
```dataview
LIST
FROM "02 Notes"
WHERE type="idea"
SORT created DESC
LIMIT 5
```
