# Movies API Testing

## Overview
This repository contains test cases for the Movies API endpoint `/movies`, which returns a list of movies. Testing was performed using Postman.

## Test Scenarios
- Validating response structure and data types.
- Testing invalid and unexpected query parameters.
- Testing invalid endpoint.
- Simulating large payloads.
- Checking for rate-limiting.

## How to Use
1. Import the `movies-api-testing.json` file into Postman.
2. Run the collection using Postman Runner for automated testing.

## Observations
- The API does not enforce rate-limiting, even under heavy load.
- All invalid parameters are ignored, and the response remains consistent.
- Recommendation: Implement stricter validation and rate-limiting mechanisms.
