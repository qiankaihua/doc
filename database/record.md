[<< RETURN](.)

# record

TYPE | NAME | NULLABLE | DEFAULT | REFERENCE | COMMENT
---|---|---|---|---|---
int | id | not null | | |
timestamp | created_at | not null | | |
timestamp | updated_at | not null | | |
int | user_id | not null | | user.id |
int | problem_id | not null | | problem.id |
int | contest_id | null | | contest.id |
int | compile_info_id | null | | compile_info.id |
int | language_id | not null | | language.id |
int | code_id | not null | | code.id |
int | judge_result_id | not null | 1 | judge_result.id |
int | time_cost | null | | |
int | memory_cost | null | | |
