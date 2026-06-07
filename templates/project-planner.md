# Project Planner (Notion Template) - $15

Plan and ship projects with milestones, tasks, and a timeline. Works for solo creators and small teams.

## Build spec

### 1. Projects (database)
Properties:
- Project (title)
- Status (select: Planning, Active, Blocked, Done)
- Owner (person or text)
- Start (date)
- Due (date)
- Progress (formula or rollup % of tasks done)

Views: Board by Status, Timeline by Start/Due.

### 2. Milestones (database)
Properties:
- Milestone (title)
- Project (relation -> Projects)
- Target date (date)
- Done (checkbox)

### 3. Tasks (database)
Properties:
- Task (title)
- Project (relation -> Projects)
- Milestone (relation -> Milestones)
- Assignee (person or text)
- Due (date)
- Status (select: To do, Doing, Done)

Views: Board by Status, Table filtered by current project.

### 4. Dashboard
- Active projects gallery
- This-week task view
- Upcoming milestones list

## Selling notes
Mid-tier template for teams/creators. Price: $15 on Gumroad.
