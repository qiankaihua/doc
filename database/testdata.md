# testdata

TYPE | NAME | NULLABLE | DEFAULT | REFERENCE | COMMENT
---|---|---|---|---|---
int | id | not null | | |
timestamp | created_at | not null | | |
timestamp | updated_at | not null | | |
int | problem_id | not null | | problem.id |
string | input_filename | not null | | |
string | output_filename | not null | | |
string | hashcode | not null | | | UNIQUE
