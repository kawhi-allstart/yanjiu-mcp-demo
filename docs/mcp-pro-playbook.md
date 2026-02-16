# GitHub MCP Pro Workflow

## Why this branch exists

This branch demonstrates a practical MCP workflow:

1. Work on an isolated branch
2. Update files with SHA safety
3. Open PR and inspect changed files
4. Keep rollback path ready

## Quick commands (conceptual)

- Create branch: `create_branch`
- Safe update: `create_or_update_file` with `sha`
- Open PR: `create_pull_request`
- Inspect PR files: `pull_request_read(get_files)`
- Rollback: read old file content by commit SHA and write it back on a recovery branch
