# How Stories in an Epic Are Reflected on the Roadmap

**Owner:** Product Team | **Last updated:** 2026-03-25

## Summary

The roadmap operates at the epic level. Individual stories within an epic are not surfaced on the roadmap directly — they live in Jira and are the unit of sprint planning, not strategic planning.

## The Hierarchy

```
Roadmap
  └── Epic (visible on roadmap)
        └── Story (lives in Jira, not on roadmap)
              └── Subtask
```

## What Goes on the Roadmap

- Epics with a target quarter or milestone
- Epic status: Not Started / In Progress / Complete / Blocked
- Owning PM and eng lead
- Dependencies on other epics (if any)

## How Stories Roll Up

Story completion drives epic progress. An epic is considered:

| Status | Meaning |
|---|---|
| In Progress | At least one story is active in a sprint |
| At Risk | Stories are behind, or blockers exist |
| Complete | All scoped stories are closed |

PMs are responsible for keeping epic status current in Jira so the roadmap reflects reality.

## What This Is NOT

- The roadmap is not a sprint board — don't add stories to it
- Epic completion % is a signal, not a guarantee — scope can change
- A closed epic does not automatically mean the feature is shipped; confirm with eng before marking done

## Related


