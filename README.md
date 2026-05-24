# Institute Management System

## Environment Setup

### 1. Create `.env`
```bash
cp .env.example .env
```
### 2. Configure Environment Variables

Open `.env` and update the values according to your local setup.

Example:

```env
SECRET_KEY=your-secret-key

DEBUG=True

ALLOWED_HOSTS=127.0.0.1,localhost

DB_ENGINE=django.db.backends.postgresql
DB_NAME=pti_db
DB_USER=postgres
DB_PASSWORD=postgres
DB_HOST=127.0.0.1
DB_PORT=5432
```
