# Requirements: TaskFlow (MVP)

| ID | User story | Acceptance criteria |
|---|---|---|
| US-01 | As a user, I can sign up and log in | Email + password; invalid login returns an error; passwords are hashed |
| US-02 | As a user, I can create, edit and delete tasks | Task has title, description, due date, status (todo/doing/done) |
| US-03 | As a user, I can assign a task to a teammate | Assignee must be a member of the same project |
| US-04 | As a user, I can filter tasks by status and assignee | Filters can be combined; results are paginated |
| US-05 | As an assignee, I get an email 24h before a task is due | Sent once per task; not sent for done tasks |
