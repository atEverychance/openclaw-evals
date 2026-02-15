# Manual Setup Instructions for OpenClaw Evals Project

## Setting up the Project Board

1. Go to https://github.com/atEverychance/openclaw-evals/projects
2. Click the "New project" button
3. Give the project the title "OpenClaw Evals"
4. Choose the "Basic kanban" template or start with a blank project
5. Create the following columns:
   - Backlog (for issues that are not yet ready to be worked on)
   - Ready (for issues that are ready to be picked up)
   - In Progress (for issues currently being worked on)
   - Review (for issues awaiting review)
   - Done (for completed issues)

## Setting up Automated Workflows

After creating the project board, set up automation rules:

1. In the project settings, look for "Automation" or "Rules"
2. Create rules to automatically move issues between columns based on labels:
   - When an issue is labeled "status:backlog", move it to the "Backlog" column
   - When an issue is labeled "status:ready", move it to the "Ready" column
   - When an issue is labeled "status:in-progress", move it to the "In Progress" column
   - When an issue is labeled "status:review", move it to the "Review" column
   - When an issue is labeled "status:done", move it to the "Done" column

## Adding Labels to Issues

For each issue, manually add the appropriate labels:

1. Go to each issue (Issues tab)
2. Click the "Labels" dropdown
3. Select the appropriate labels:
   - One type label (type:feature, type:bug, or type:docs)
   - One area label (area:costs, area:evals, area:reporting, or area:automation)
   - One priority label (priority:high, priority:medium, or priority:low)

## Issue Assignments

Assign issues to team members as appropriate:

1. Go to each issue
2. Click the "Assignees" dropdown
3. Select the appropriate team member

## Next Steps

1. Begin implementation of Issue #7: Evaluation framework design (Phase 1)
2. Create detailed documentation for the framework components
3. Start developing the cost tracking components (Issues #1, #2, #3)