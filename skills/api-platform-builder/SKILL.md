---
name: api-platform-builder
description: Master REST API design, FastAPI/Flask microservices, OpenAPI contracts, Pydantic V2 validation, JWT auth, and API stress testing.
---

# AAS API Platform Builder Skill

Use this skill whenever designing, building, documenting, or testing RESTful APIs and microservices.

## 🛠 Core Principles
1. **OpenAPI First**: Define clear endpoint paths, request/response models, and HTTP status codes (200, 201, 400, 401, 403, 404, 422, 500).
2. **Strict Type Validation**: Use Pydantic V2 or TypeScript interfaces for strict request payload validation.
3. **Secure Auth**: Implement JWT (Bearer tokens) or OAuth2 password flows with password hashing (bcrypt/argon2).
4. **Structured Errors**: Return consistent error payload schema: `{"error": {"code": "RESOURCE_NOT_FOUND", "message": "..."}}`.
5. **Pagination & Filtering**: Always implement `limit` and `offset`/`cursor` pagination for list endpoints.