# ICT371 Question 3: Library Returns and Overdue Fines

Individual PostgreSQL solution for Question 3 of the ICT371 Advanced Database assignment.

## Contents
- `Q3_Library_Returns_Overdue_Fines.sql` - SQL implementation extracted from the supplied combined Q2-Q10 assignment script.

## Run
1. Open a PostgreSQL database in pgAdmin or `psql`.
2. Execute the SQL file.
3. Review the verification queries and results included in the script, where provided.

## Important PostgreSQL note
This question schedules a job with `pg_cron`. The PostgreSQL server must have the extension installed and configured (including `shared_preload_libraries` and a server restart). If `pg_cron` is not available, run the database objects and seed statements but skip/comment the `cron.schedule(...)` statement. A successful upload to GitHub does not itself execute or test the SQL.

## Schema
The script uses schema `q3` to keep this question's objects separate from other questions.
