# Week 7: Design your own domain (WB-07)

**My domain:** <!-- Hospital OPD / College Library / Hostel Management / Event Ticketing -->

## Checklist
- [ ] `requirements.md`: 8–10 short user requirements
- [ ] `er-diagram.png`: entities, attributes, cardinalities, at least one many-to-many relationship
- [ ] `schema.sql` normalised to 3NF, with constraints
- [ ] `design-notes.md`: functional dependencies, one anomaly the design prevents, one deliberate denormalisation and why
- [ ] `indexing.md`: 100k rows, `EXPLAIN ANALYZE` before and after an index, both plans and timings
- [ ] `safe_query.py`: psycopg with a parameterised query, plus a comment on why string concatenation is unsafe
- [ ] Stretch: a transaction that moves a booking/seat/bed and rolls back on failure

## How to run

```bash
psql -d <your-db> -f schema.sql
python safe_query.py
```
