# -alx-airbnb-database
# Database Normalization for AirBnB Clone Schema

## Objective
To ensure that the database design adheres to the principles of Third Normal Form (3NF) for data consistency and efficiency.

---

## First Normal Form (1NF)
- All fields contain atomic values (no repeating groups).
- Each attribute stores a single piece of data.
✅ The schema satisfies 1NF.

---

## Second Normal Form (2NF)
- No partial dependencies exist as all tables use single-column primary keys (UUID).
- All non-key attributes are fully functionally dependent on the primary key.
✅ The schema satisfies 2NF.

---

## Third Normal Form (3NF)
- No transitive dependencies between non-key attributes.
- All non-key attributes are dependent solely on the primary key.
✅ The schema satisfies 3NF. 

---

## Conclusion
The schema is well-structured and adheres to normalization principles up to 3NF. This ensures minimal data redundancy and improved data integrity
