# api_token

TYPE | NAME | NULLABLE | DEFAULT | REFERENCE | COMMENT
---|---|---|---|---|---
int | id | not null | | |
timestamp | created_at | not null | | |
timestamp | updated_at | not null | | |
int | user_id | not null | | user.id |
string | token | not null | | | UNIQUE
string | ip | null | | | user client's ip
timestamp | expired_at | null | | | expired time
