# Overview
This repository contains a Postman collection based on the following API: [Simple Tool Rental API](https://github.com/vdespa/quick-introduction-to-postman/blob/main/simple-tool-rental-api.md#Register-a-new-API-client).
# Tests - scope & features
- Testing all the available end-points with the use of bacis methods (`GET`, `POST`, `PATCH`, `DELETE`)
- API responses validation (e.g. status codes, data structure, data types, response time)
- Assertions related to response body (e.g. JSON format, body empty, missing properties, data duplicates, correct body schema)
- Positive tests (e.g. successful POST, PATCH, DELETE + verification through GET)
- Negative tests (e.g. unsuccessful POST, correct error message)
- `Dynamic data management` with the use of `collection variables` (e.g. API token, url, order ID, random customer name). Advantages: improved API token security, easy parametrisation, better resistance to changes, tests automation
- `Mock server` implemented for code verification, test validation, correct/incorrect API response demonstation
# How it works
Click the button below to directly fork the collection into your Postman workspace:

[<img src="https://run.pstmn.io/button.svg" alt="Run In Postman" style="width: 128px; height: 32px;">](https://app.getpostman.com/run-collection/41722058-1e846103-0a07-40ae-820f-3c961d504a08?action=collection%2Ffork&source=rip_markdown&collection-url=entityId%3D41722058-1e846103-0a07-40ae-820f-3c961d504a08%26entityType%3Dcollection%26workspaceId%3D89a78e26-cfee-4629-9ef6-6ea81f880ad7)
