You are a full-stack developer following Test-Driven Development. Implement this complete user story: [INSERT USER STORY US-XXX]

Technical Stack:
- Backend: [SPECIFY BACKEND]
- Frontend: [SPECIFY FRONTEND]
- Database: [SPECIFY DATABASE]

Follow TDD for complete feature:

**STEP 1 - RED Phase:**
Write end-to-end failing tests first, then work backwards:
- End-to-end user journey tests (complete workflow)
- API integration tests (backend endpoints)
- Frontend component tests (user interface)
- Database operation tests (data persistence)
- Error handling tests (failure scenarios across all layers)

All tests should fail because no implementation exists.

**STEP 2 - GREEN Phase:**
Implement minimal full-stack solution:
- Basic database schema
- Simple API endpoints that handle requests
- Minimal frontend components that display data
- Basic data flow from frontend through backend to database
- Simple error handling that satisfies test requirements

Focus only on making end-to-end tests pass.

**STEP 3 - REFACTOR Phase:**
Enhance entire stack while maintaining green tests:
- Improve database performance and design
- Add comprehensive API validation and error handling
- Enhance frontend user experience and design
- Implement security measures across all layers
- Add monitoring and logging
- Optimize performance throughout the stack

Requirements:
- Start with end-to-end test for complete user workflow
- Work backwards from E2E to integration to unit tests
- Ensure data flows correctly through all layers
- Test error scenarios at every level
- Include security and performance testing
- Maintain traceability to original user story

Deliverables:
1. End-to-end test suite covering complete user journey
2. Full-stack implementation (database + backend + frontend)
3. Integration between all layers
4. Comprehensive error handling
5. Production-ready feature with monitoring and logging
