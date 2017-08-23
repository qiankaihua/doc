[<< RETURN](.)

# user

TYPE | NAME | NULLABLE | DEFAULT | REFERENCE | COMMENT
---|---|---|---|---|---
int | id | not null | | |
timestamp | created_at | not null | | |
timestamp | updated_at | not null | | |
string | username | not null | | | UNIQUE
string | password | not null | | |
int | role_id | not null | 3 | role.id |
string | email | not null | | | UNIQUE
string | school | null | | |
int | department_id | not null | 1 | department.id |
string | nickname | null | | |
string | realname | null | | |
text | motto | null | | |
int | grade_id | not null | 4 | grade.id |
bool | gender | not null | false | | 0(false) for male, 1(true) for female

### Initial data

id | username | password | email | role_id
---|---|---|---|---
1 | admin | hash(d033e22ae348aeb5660fc2140aec35850c4da997) | admin@admin.com | 1

__`hash` means bcrypt functions in laravel__
