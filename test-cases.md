# Test Cases

## TC_API_01: Successful POST request to /post endpoint
**Type:** Positive  
**Tool:** Charles Proxy  
**Platform:** iOS Safari  

**Steps:**
1. Open Safari on iPhone
2. Navigate to https://httpbin.org/forms/post
3. Submit the form

**Expected Result:**
- HTTP status code 200
- JSON response is returned

**Actual Result:**
- HTTP 200 OK
- JSON response received

**Status:** Passed

---

## TC_API_02: Unsupported HTTP method for /post endpoint
**Type:** Negative  

**Steps:**
1. Open Safari on iPhone
2. Navigate to https://httpbin.org/post

**Expected Result:**
- HTTP status code 405 Method Not Allowed

**Actual Result:**
- HTTP 405 Method Not Allowed

**Status:** Passed
