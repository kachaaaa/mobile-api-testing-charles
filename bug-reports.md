# Bug Reports

## BUG_API_01: Non-JSON response for unsupported HTTP method

**Severity:** Low  
**Priority:** Low  
**Environment:** iOS Safari, Charles Proxy  

**Steps to Reproduce:**
1. Send GET request to https://httpbin.org/post

**Actual Result:**
- Server returns 405 error page in non-JSON format

**Expected Result:**
- Server should return structured JSON error response

**Notes:**
- Status code is correct
- Response format is inconsistent with API-style responses
