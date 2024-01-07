# Dredd API Testing Guide

## Installation
Install Dredd using npm:
```bash
npm install -g dredd
```

## Invoke dredd with the OpenAPI spec file
```bash
Syntax : dredd file.yaml SERVER_END_POINT
Example: dredd openapi.yaml https://reqres.in/api
```

## Invoke dredd with test report
```bash
dredd openapi.yaml https://reqres.in/api --reporter=apiary
```
Sample response: https://app.apiary.io/public/tests/run/53f9c28a-188a-4964-b153-abea4f229f92
