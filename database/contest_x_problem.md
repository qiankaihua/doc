[<< RETURN](.)

# contest_x_problem

TYPE | NAME | NULLABLE | DEFAULT | REFERENCE | COMMENT
---|---|---|---|---|---
int | id | not null | | |
timestamp | created_at | not null | | |
timestamp | updated_at | not null | | |
int | contest_id | not null | contest.id | |
int | problem_id | not null | problem.id | |
string | alias | null | | | alias title
int | order | not null | 0 | |
