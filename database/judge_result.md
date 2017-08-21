[<< RETURN](.)

# judge_result

TYPE | NAME | NULLABLE | DEFAULT | REFERENCE | COMMENT
---|---|---|---|---|---
int | id | not null | | |
timestamp | created_at | not null | | |
timestamp | updated_at | not null | | |
string | alias | not null | | |
string | en | not null | | |
string | color | not null | | |

### Initial data

id | alias | en | color
---|---|---|---
1 | Pending | Pending | #9e9e9e
2 | Judging | Judging | #2196f3
3 | AC | Accepted | #4caf50
4 | PE | Presentation Error | #ff9800
5 | WA | Wrong Answer | #f44336
6 | OLE | Output Limit Exceeded | #e91e63
7 | TLE | Time Limit Exceeded | #9c27b0
8 | MLE | Memory Limit Exceeded | #673ab7
9 | CE | Compilation Error | #ffeb3b
10 | RE | Runtime Error | #ff5722
11 | SE | System Error | #000000
