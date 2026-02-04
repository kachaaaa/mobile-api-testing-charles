# Pet Project: API Testing via Charles Proxy (Mobile Web)

## 📌 Project Overview
This pet project demonstrates API testing skills using Charles Proxy
to intercept and analyze mobile web traffic.

## 🛠 Tools & Technologies
- Charles Proxy
- iOS Safari
- HTTP/HTTPS
- GitHub

## 🎯 Scope
- Intercepting mobile HTTP traffic
- Analyzing API requests and responses
- Verifying server behavior for valid and invalid HTTP methods
- Creating test cases and bug reports

## 🌐 Tested Target
- https://httpbin.org


## 📂 Project Structure

The repository is organized to clearly separate test cases and observations generated during API testing with Charles Proxy:

mobile-api-testing-charles/
├── README.md
├── test-cases/
│   ├── TC_Charles_modify_Post.md
│   │   └─ Test Case: modification of POST request using Charles Breakpoints
│   └── observation/
│       ├── OBS_Server_closes_connection.md
│       │   └─ Observation: server behaviour when a modified request fails
│       └── screenshots/
│           ├── post_failed_breakpoint.png
│           └── post_200_ok.png

Each directory contains:
- `test-cases/` — documented test cases executed during API testing  
- `observation/` — technical observations and results from executed tests  
- `screenshots/` — visual evidence captured during testing
