# 🔧 E-Commerce Address Book Service

Address Book Management Service for shipping addresses.

## Port

**8083**

## Endpoints

- `POST /api/v1/address` - Save address (unique constraint: same user cannot save exact same address twice)
- `GET /api/v1/address/{id}` - Get address by ID
- `GET /api/v1/address?userId=` - Get all addresses for a user

## Running Locally

```bash
mvn spring-boot:run
```

