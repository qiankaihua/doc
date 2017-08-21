[<< RETURN](..)

# language

TYPE | NAME | NULLABLE | DEFAULT | REFERENCE | COMMENT
---|---|---|---|---|---
int | id | not null | | |
timestamp | created_at | not null | | |
timestamp | updated_at | not null | | |
string | display_name | not null | | |
string | extension | not null | | |
int | time_factor | not null | | 1 | real_time_limit = time_limit * time_factor
int | memory_factor | not null | | 1 | real_memory_limit = memory_limit * memory_factor

### Initial data

id | display_name | extension | time_factor | memory_factor
---|---|---|---|---
1 | C | c | 1 | 1
2 | C++ | cc | 1 | 1
3 | Java | java | 3 | 3
