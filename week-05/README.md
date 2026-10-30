# Week 5: College database (WB-05)

The `college` database in PostgreSQL: schema, seed data and 25 commented queries.

## Checklist
- [ ] `schema.sql`: departments, students, courses, enrolments with PK, FK, NOT NULL, UNIQUE, CHECK and DEFAULT constraints
- [ ] `seed.sql`: at least 4 departments, 40 students, 12 courses, 120 enrolments (a generator script is welcome; commit it)
- [ ] `queries.sql`: 25 queries, each preceded by a comment with the question in plain English
- [ ] All three files run cleanly on an empty database, in order
- [ ] Stretch: 5 more queries from LeetCode SQL 50, linked below

## How to run

```bash
createdb college
psql -d college -f schema.sql
psql -d college -f seed.sql
psql -d college -f queries.sql
```
