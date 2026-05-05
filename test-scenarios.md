
# API Test Scenarios

## Endpoint: GET /users

### Positive Scenarios
- Validate status code is 200
- Validate response contains user data
- Validate response structure (id, name, email)

### Negative Scenarios
- Access invalid endpoint → expect 404
- Send malformed request → validate error response

### Edge Cases
- Empty response handling
- Unexpected data format handling


## Endpoint: POST /posts

### Positive Scenarios
- Validate status code is 201
- Validate response contains created data

### Negative Scenarios
- Missing required fields → validate error handling
- Invalid data types → validate response

### Edge Cases
- Large payload handling
- Duplicate data handling