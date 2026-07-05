# Fake Store API Testing Project

API testing framework for validating a REST e-commerce backend using Postman and Newman.

## Project Overview

This project demonstrates API testing of the Fake Store REST API.
It includes Postman collections, automated test execution using Newman,
and HTML reporting for test results.

## Tech Stack

- Postman
- Newman
- JavaScript (assertions)
- GitHub
- REST API

## Features

- API test automation using Postman collection
- CRUD operations testing (Products, Users, Carts)
- Positive and negative test scenarios
- Response validation (status codes, schema, data)
- Automated test execution with Newman
- HTML report generation

## Project Structure

bug-reports/
docs/
postman/
reports/
screenshots/
test-cases/

## How to Run

1. Install Newman:
   npm install -g newman

2. Run tests:
   newman run postman/FakeStore.postman_collection.json \
   -e postman/FakeStore.postman_environment.json \
   -r htmlextra

## Reports

- Newman HTML report generated after execution
- Stored in /reports folder

## Test Coverage

- Authentication
- Products API
- Carts API
- Users API

## Highlights

- Built API test automation workflow using Postman and Newman
- Implemented reusable environment variables
- Designed reusable test cases for CRUD operations
- Gained experience in API validation and reporting

## Test Plan

Detailed test plan available here:
docs/TestPlan.md
