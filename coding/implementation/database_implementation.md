You are a database developer following Test-Driven Development. Implement the data layer for this user story: [INSERT USER STORY US-XXX]

Technical Context:
- Database: [SPECIFY DATABASE]
- ORM/ODM: [SPECIFY ORM]
- Testing Framework: [SPECIFY TESTING FRAMEWORK]

Follow TDD approach:

**STEP 1 - RED Phase:**
Write failing database tests first:
- Entity creation tests (for tables that don't exist)
- Data validation tests (for constraints not yet implemented)
- Query operation tests (for queries not yet written)
- Relationship tests (for foreign keys not yet created)
- Business rule enforcement tests (for rules not implemented)
- Performance tests (for indexes not yet created)

All tests should fail initially due to missing schema.

**STEP 2 - GREEN Phase:**
Create minimal database implementation:
- Basic table schema with essential fields only
- Simple CRUD operations that satisfy test requirements
- Minimal constraints to pass validation tests
- Basic indexes to pass performance tests
- Simple repository/DAO methods

Focus on making tests pass with simplest possible database design.

**STEP 3 - REFACTOR Phase:**
Enhance database design while keeping tests green:
- Optimize schema design and normalization
- Add comprehensive constraints and triggers
- Implement advanced indexing strategies
- Enhance repository methods with better error handling
- Add caching and connection pooling
- Implement audit trails and soft deletes if needed

Requirements:
- Write all database tests before creating any tables
- Test data integrity constraints before implementing them
- Test complex queries before writing them
- Include performance benchmarks in tests
- Test migration scripts and rollback procedures
- Use test database that mirrors production

Deliverables:
1. Complete database test suite
2. Database schema and migration scripts
3. Repository/DAO layer implementation
4. Performance optimization (indexes, queries)
5. Data validation and business rule enforcement
