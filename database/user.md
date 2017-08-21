[<< RETURN](.)

# user

TYPE | NAME | NULLABLE | DEFAULT | REFERENCE | COMMENT
---|---|---|---|---|---
int | id | not null | | |
timestamp | created_at | not null | | |
timestamp | updated_at | not null | | |
string | username | not null | | | UNIQUE
string | password | not null | | |
int | role_id | not null | 3 | |
string | email | not null | | | UNIQUE
string | school | null | | |
int | department_id | null | 1 | department.id |
int | nickname | null | | |
int | realname | null | | |
text | motto | null | | |
int | grade_id | null | 4 | grade.id |
bool | gender | not null | false | | 0(false) for male, 1(true) for female
