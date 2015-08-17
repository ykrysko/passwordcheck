# passwordcheck
Modification of PostgreSQL passwordcheck module to meet the DoD requirements

Overall, the following checks are enforced:

- Password must be at least 14 characters long
- Password must contain at least 1 lowercase and 1 uppercase letter, 1 numeric and 1 special character
- Password must not contain username
