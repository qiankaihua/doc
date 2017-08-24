[<< RETURN](.)

# problem

TYPE | NAME | NULLABLE | DEFAULT | REFERENCE | COMMENT
---|---|---|---|---|---
int | id | not null | | |
timestamp | created_at | not null | | |
timestamp | updated_at | not null | | |
string | title | not null | | |
text | description | null | | |
text | input | null | | |
text | output | null | | |
text | samples | null | | | json数组 \[{input: '', output: ''}, ...\]
text | hint | null | | |
string | source | null | | |
int | time_limit | not null | 1000 | | MS
int | memory_limit | not null | 65536 | | KB
int | output_limit | not null | 16384 | | KB
bool | is_spj | not null | false | |
bool | is_visible | not null | false | |
int | difficulty | null | | | 1 ~ 5; 0 and null for not certain
