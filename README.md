# Login Page Test Cases Project

## Description
This project demonstrates test case design and implementation for a Login Page. It includes functional testing and boundary value testing.


## Test Cases

### TC_01 – Valid Login
- Enter correct username and password
- Click login
- Expected: User is redirected to dashboard page

### TC_02 – Invalid Login
- Enter incorrect credentials
- Expected: "Invalid credentials"

### TC_03 – Empty Fields
- Leave fields empty
- Expected: "Fields cannot be empty"

### TC_04 – SQL Injection
- Input: ' OR '1'='1
- Expected: Login fails and error shown


## Boundary Value Testing (Password)

- 7 characters → Rejected
- 8 characters → Accepted
- 12 characters → Accepted
- 13 characters → Rejected


## How to Run
1. Download the project
2. Open index.html in browser
