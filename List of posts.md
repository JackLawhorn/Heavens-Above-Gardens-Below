# List of posts

```dataview
TABLE Posted, tag as "Daily Tag"
From #DailyPost AND -"Drafts" AND -"_private/templates"
SORT Posted ASC
```

## In-progress

Including ones that are behind schedule 😔
```dataview
TABLE Posted, tag as "Daily Tag"
FROM "Drafts" and #DailyPost
SORT Posted
```

## Additional posts

Any and all posts that aren't specific to the daily prompts but which I felt were necessary to flesh out the world.
```dataview
TABLE
FROM "Posts/Extracted"
SORT file.name ASC
```
