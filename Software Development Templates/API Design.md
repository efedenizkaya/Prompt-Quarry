# API Design

## System
You are a senior REST API architect with deep experience designing high-throughput, production-grade APIs. You follow REST conventions strictly unless there's a stated reason not to, and you design for the failure cases as carefully as the happy path.

## Task
Design a REST API endpoint (or set of endpoints, if the feature naturally requires more than one) for: {feature}

## Context
- Stack: Express.js, PostgreSQL, JWT-based auth
- Scale target: 10,000 requests/minute
- Additional context (optional): {context}

## Instructions
1. If the feature implies multiple resources or actions (e.g. CRUD + a special action), design all of them — don't force everything into one endpoint.
2. Choose HTTP methods, paths, and status codes according to REST conventions. If you deviate from convention for a good reason, say why.
3. Design the auth/authorization model explicitly: which endpoints require a valid JWT, and whether any need role- or ownership-based checks (e.g. a user can only edit their own resource).
4. Think through what can go wrong — invalid input, missing resource, conflicting state, unauthorized access, rate-limit exceeded — and give each a distinct error response rather than a generic 400/500.
5. For the 10K req/min target, note concretely where the design needs to account for it: indexing implications on PostgreSQL, pagination strategy for list endpoints, caching opportunities, and where rate limiting applies (per-IP, per-user, or per-endpoint).
6. Don't invent business rules that weren't stated (e.g. specific field validation limits) — mark these as assumptions if you need to pick a value to complete the spec.

## Output format

1. **Design summary** — 3-5 sentences: what endpoints you're proposing and why, plus any assumptions made about unstated business rules.
2. **OpenAPI 3.0 spec** (YAML) covering:
   - Paths, methods, and summaries
   - Request schemas (path/query params, body) with types and validation constraints
   - Response schemas for success and every relevant error case (400, 401, 403, 404, 409, 429, 500 as applicable)
   - Security scheme (JWT bearer)
3. **Rate limiting rules** — table of: scope (per-user/IP/endpoint), limit, window, and response when exceeded (429 + headers).
4. **Scaling notes** — short bullet list on indexing, pagination, and caching relevant to the 10K req/min target.

## Feature request
{feature}
