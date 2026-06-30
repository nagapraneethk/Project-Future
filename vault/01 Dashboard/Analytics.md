# 📊 Analytics

## Sessions This Month
```dataview
TABLE created, project
FROM "03 Sessions"
WHERE type="session"
SORT created DESC
```

## Projects by Status
```dataview
TABLE status
FROM "04 Projects"
WHERE type="project"
```

## Recently Added Concepts
```dataview
TABLE created
FROM "02 Notes"
WHERE type="concept"
SORT created DESC
LIMIT 15
```
