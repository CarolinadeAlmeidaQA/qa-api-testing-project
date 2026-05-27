# API Evidence - 404 User Not Found

## Endpoint
GET https://jsonplaceholder.typicode.com/users/999999

---

## Test Scenario
Validate system behavior when requesting a non-existent user.

---

## Expected Result
API should return 404 Not Found for invalid user ID.

---

## Actual Result
API returned 404 Not Found as expected.

---

## Conclusion
The API correctly handles invalid resource requests and returns appropriate HTTP status code.
