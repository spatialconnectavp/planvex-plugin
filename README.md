# Planvex Plugin for Claude Code

Project management tools for [Planvex](https://planvex.vercel.app) — manage issues, notes, folders, comments, and labels directly from Claude Code.

## Install

```
/plugin marketplace add spatialconnectavp/planvex-plugin
/plugin install planvex@planvex-marketplace
```

## Tools (17)

### Issues
- **list_issues** — List issues with filtering by status, priority, area
- **get_issue** — Get a single issue with labels
- **create_issue** — Create a new issue
- **update_issue** — Update an issue's fields
- **list_labels** — List all labels in the workspace
- **workspace_summary** — High-level workspace stats (issue counts, recent activity)

### Notes
- **list_notes** — List all notes with title, ID, and last-updated timestamp
- **get_note** — Get a note's full text content
- **create_note** — Create a new note
- **update_note** — Update a note's title or content

### Folders
- **list_folders** — List all folders
- **create_folder** — Create a new folder
- **move_note_to_folder** — Move a note into a folder (or to root)

### Comments
- **list_comments** — List comments on an issue
- **add_comment** — Add a comment to an issue
