
```start-multi-column
ID: ID_8tp4
Number of Columns: 2
Largest Column: standard
border:off
```

> [!todo]+ Today's Tasks
> ```tasks
> not done
> due <%tp.date.now( "YYYY-MM-DD")%>
> sort by path
> sort by priority
> hide due date 
>```

--- column-end ---

>[!warning]+  Overdue
>```tasks
>not done
>sort by priority 
>due before <% tp.date.now("YYYY-MM-DD")%>
>```

=== end-multi-column

```dataviewjs
await dv.view("tasksCalendar", {pages: "", view: "month", firstDayOfWeek: "1", options: "style1"})
```

## Unscheduled Tasks

```tasks
not done
sort by path
sort by priority
hide due date
hide backlink
```
