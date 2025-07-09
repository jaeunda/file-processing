# #4: Record I/O
### Fields of Record (85 bytes)
- Student ID (8 bytes)
- Student Name (10 bytes)
- Department (12 bytes)
- Address (30 bytes)
- E-mail Address (20 bytes)
### Functions
#### Append
- `a.out -a <record_file_name> "student_id" "student_name" "department" "address" "email"`
#### Search
- `a.out -s <record_file_name> "field_name=field_value"`
#### Delete
- `a.out -d <record_file_name> "field_name=field_value"`
#### Insert
- `a.out -a <record_file_name> "student_id" "student_name" "department" "address" "email"`
