# Test Plan – Fake Store API Testing

1. Project Overview

This test plan defines the testing approach for the Fake Store API, a RESTful service used to simulate an e-commerce backend. The goal is to validate API functionality, reliability, and response correctness using manual and automated API testing techniques.

API under test:
https://fakestoreapi.com

2. Objectives

- Validate all major API endpoints (Users, Products, Carts)
- Verify CRUD operations (Create, Read, Update, Delete)
- Ensure correct HTTP status codes are returned
- Validate response body structure and data types
- Perform negative testing for invalid inputs
- Ensure API response performance is acceptable
- Automate test execution using Postman and Newman

3. Scope

In Scope:

- Authentication (login)
- Products API
- Users API
- Carts API
- Basic error handling validation
- Response validation (JSON structure, fields, data types)

Out of Scope:

- UI testing (not applicable)
- Database validation (no direct DB access)
- Performance/load testing beyond basic response time checks

4. Testing Types

- Functional Testing
- Positive Testing
- Negative Testing
- Boundary Testing
- API Contract Testing (basic schema checks)
- Regression Testing (via collection runs)

5. Test Environment

API: https://fakestoreapi.com
Tool: Postman
Automation runner: Newman
OS: Windows
Browser: Not applicable (API testing)

6. Test Strategy

- Manual Testing
- API requests executed in Postman
- Validation of responses manually
- Exploratory testing of endpoints
- Automated Testing
- Postman collection created for all endpoints
- Assertions added using JavaScript
- Execution via Newman CLI
- HTML reports generated for results analysis

7. Test Data

- Static test credentials (if applicable)
- JSON payloads for POST/PUT requests
- Randomized product/cart data where needed

8. Entry Criteria

- API is accessible and stable
- Postman collection is created
- Test environment is configured

9. Exit Criteria

- All critical test cases executed
- No open critical defects
- Expected vs actual results documented
- Newman report generated successfully

10. Deliverables

- Postman collection
- Postman environment file
- Test cases documentation
- Bug reports (if any)
- Newman HTML report
- Test plan document

11. Risks & Assumptions

Risks:

- API may change or become unavailable
- Limited control over backend behavior
  Assumptions:
- API returns consistent responses
- No authentication limitations for public endpoints

12. Tools

- Postman
- Newman
- Git & GitHub
- VS Code

13. Conclusion

This test plan ensures structured validation of the Fake Store API, covering functional correctness, response validation, and basic automation using industry-standard API testing tools.
