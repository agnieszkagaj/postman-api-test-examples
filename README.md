# OVERVIEW
This repository contains a Postman collection based on the following API: [Simple Tool Rental API](https://github.com/vdespa/quick-introduction-to-postman/blob/main/simple-tool-rental-api.md#Register-a-new-API-client).
# TESTS - SCOPE & FEATURES
- Testing all the available end-points with the use of bacis methods (`GET`, `POST`, `PATCH`, `DELETE`)
- API responses validation (e.g. status codes, data structure, data types, response time)
- Assertions related to response body (e.g. JSON format, body empty, missing properties, data duplicates, correct body schema)
- Positive tests (e.g. successful POST, PATCH, DELETE + verification through GET)
- Negative tests (e.g. unsuccessful POST, correct error message)
- `Dynamic data management` with the use of `collection variables` (e.g. API token, url, order ID, random customer name). Advantages: improved API token security, easy parametrisation, better resistance to changes, tests automation
- `Mock server` implemented for code verification, test validation, correct/incorrect API response demonstation
