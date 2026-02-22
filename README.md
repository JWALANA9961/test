# q-git-revert-env

A Flask-based REST API service.

## Version

9.0.0

## Quick Start

```bash
pip install -r requirements.txt
python app.py
```

## API Endpoints

- `GET /health` - Health check
- `POST /api/v1/login` - User authentication
- `GET /api/v1/users` - List users
- `POST /api/v1/register` - Register new user

## Environment Variables

Copy `.env.example` to `.env` and configure:

- `DATABASE_URL` - PostgreSQL connection string
- `JWT_SECRET` - Secret for JWT tokens
- `REDIS_URL` - Redis connection for caching

## Development

```bash
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
flask run --debug
```

## Testing

```bash
pytest tests/ -v
```

## License

MIT

# Automated Security Updates Project
Developer: 25ds3000157@ds.study.iitm.ac.in

This project is configured with Dependabot to automatically 
monitor and update Python dependencies.