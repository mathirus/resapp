 codex/add-menu_items-table-description-to-schema.sql
# Restaurant Application
=======
# Restaurant App

1. Copy the environment example file and rename it to `.env`:

```bash
cp backend/.env.example backend/.env
```

2. Edit `backend/.env` and fill in your database credentials.


Before running the server make sure the database has the required tables.

Create the `menu_items` table using the SQL script under `backend/docs/schema.sql`:

```sh
sqlite3 path/to/your.db < backend/docs/schema.sql
```

Adjust the database path as needed.
