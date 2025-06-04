# Redis – Local CRUD Operations

This section contains Redis CLI commands to demonstrate CRUD operations locally.

## 👨‍💻 Steps

1. **Insert:** `SET name "Sanjay"`
2. **Read:** `GET name` → should return `"Sanjay"`
3. **Update:** `SET name "The Great Sanjay"`
4. **Read Again:** `GET name` → should return `"The Great Sanjay"`
5. **Delete:** `DEL name`
6. **Confirm Deletion:** `GET name` → should return `(nil)`

## 📌 Notes

All commands were run inside the Redis CLI (connected at `127.0.0.1:6379`).
