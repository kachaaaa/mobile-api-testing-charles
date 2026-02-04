### Test Case: Modify POST request via Charles Breakpoints

**Tool:** Charles Proxy  
**Endpoint:** https://httpbin.org/post  
**Method:** POST  

**Steps:**
1. Enable Breakpoints in Charles
2. Send POST request to /post
3. Modify request body (set field value to empty string "")
4. Send modified request

**Expected Result:**
Server should return validation error or reject request

**Actual Result:**
Server closes connection without response

## Charles Proxy Tests

- Intercepted and modified POST requests using Charles Breakpoints
- Tested server behavior on invalid request payload
- Observed connection termination without response
