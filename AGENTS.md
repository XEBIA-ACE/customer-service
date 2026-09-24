# AGENTS.md

## Stack

- **Service:** Customer Service
- **Type:** business
- **Technologies:**
- Java
- Spring Boot
- REST API
- GraphQL
- Kafka
- Redis
- Docker
- Kubernetes
- PostgreSQL
- **Responsibilities:**
- Create, update, and delete customer profiles
- Perform real-time customer search and retrieval with support for partial and fuzzy matching
- Prevent duplicates and ensure customer data integrity
- Emit events for customer profile changes
- Integrate with authentication and audit services
- Encrypt and securely manage PII

## General Rules

- Always read files in /specs before implementing
- Never implement without acceptance criteria
- Code should be simple and readable
- Avoid overengineering
- The project follows a hexagonal architecture

## Required Workflow

1. Read the specs in the /specs directory
2. Generate tasks.md if it does not exist
3. Implement based on the tasks
4. Create automated tests
5. Validate acceptance criteria

## Testing

- Cover all acceptance criteria
- Tests should be clear and straightforward
- Generated code must reach **90% unit test coverage**

## Constraints

- Do not invent requirements that are not described
- Do not change behavior without updating the spec
