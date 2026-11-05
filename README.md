# Shoply

A small e-commerce API: users, orders and an admin area, built with Flask and SQLAlchemy.

- Token authentication with roles: `user`, `manager`, `admin`
- Access rules: [security-policy.md](security-policy.md)
- Endpoints: [api-spec.md](api-spec.md)

```bash
pip install -r requirements.txt
python -m app.main
```

Pull requests here are reviewed for security bugs by the LGTM GitHub App.
