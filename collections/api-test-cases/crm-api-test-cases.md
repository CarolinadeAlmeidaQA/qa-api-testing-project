# CRM API Test Cases

## TC-API-001 - Retrieve customer data successfully

### Method
GET

### Endpoint
/customers/{id}

### Expected Result
API returns status code 200 and correct customer data.

---

## TC-API-002 - Create appointment successfully

### Method
POST

### Endpoint
/appointments

### Expected Result
Appointment is created successfully and returned in response payload.


---

## TC-API-003 - Invalid authentication token

### Method
GET

### Endpoint
/customers/{id}

### Expected Result
API returns unauthorized error.
