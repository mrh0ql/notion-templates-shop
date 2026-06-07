# Freelancer Dashboard (Notion Template) - $19

A single-page command center for freelancers to manage clients, projects, and income.

## Build spec

### 1. Clients (database)
Properties:
- Name (title)
- Status (select: Lead, Active, Paused, Done)
- Email (email)
- Rate (number, $)
- Notes (text)

Views: Board by Status, Table all.

### 2. Projects (database)
Properties:
- Project (title)
- Client (relation -> Clients)
- Deadline (date)
- Status (select: Not started, In progress, Review, Done)
- Value (number, $)

Views: Board by Status, Calendar by Deadline.

### 3. Tasks (database)
Properties:
- Task (title)
- Project (relation -> Projects)
- Due (date)
- Done (checkbox)
- Priority (select: Low, Med, High)

View: Table filtered Done = unchecked, sorted by Due.

### 4. Dashboard page
Embed linked views of each database, plus:
- Callout block: weekly goal
- A "This week" task view
- Active projects gallery

## Selling notes
Package as a duplicatable template link. Price: $19 on Gumroad.
