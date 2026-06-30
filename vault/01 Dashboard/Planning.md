# 🗓 Planning

## Active Plans

```dataview
TABLE status, created
WHERE type="plan"
SORT created DESC
```

## Upcoming Reviews

```dataview
LIST
WHERE contains(type,"review")
SORT created DESC
```
