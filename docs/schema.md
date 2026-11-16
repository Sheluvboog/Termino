# Database schema (draft)

## businesses

- id (int, PK)
- slug (varchar, unique)
- name (varchar)
- timezone (varchar)
- created_at (datetime)

## users

- id (int, PK)
- business_id (int, FK -> businesses.id)
- email (varchar, unique)
- password_hash (varchar)

## services

- id (int, PK)
- business_id (int, FK -> businesses.id)
- name (varchar)
- duration_min (int)
- price_cents (int)

## appointments

- id (int, PK)
- business_id (int, FK -> businesses.id)
- service_id (int, FK -> services.id)
- client_name (varchar)
- client_email (varchar)
- starts_at (datetime, UTC)
- ends_at (datetime, UTC)
- status (varchar: booked / cancelled / done)