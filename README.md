# TestCases.md
# Test Cases - Sample Project

This repository contains a sample set of test cases for a login feature.  
The goal is to demonstrate structured thinking, attention to detail, and QA documentation skills.  

---

## Test Case Table

| ID   | Feature | Test Scenario                          | Precondition            | Steps                                                                 | Expected Result                                    | Status |
|------|----------|----------------------------------------|-------------------------|----------------------------------------------------------------------|---------------------------------------------------|--------|
| TC01 | Login    | Login with valid credentials           | User has an account     | 1. Go to login page <br> 2. Enter valid email and password <br> 3. Click "Login" | User is redirected to dashboard                    | Pass   |
| TC02 | Login    | Login with invalid password            | User has an account     | 1. Go to login page <br> 2. Enter valid email and invalid password <br> 3. Click "Login" | Error message is displayed: "Invalid credentials" | Pass   |
| TC03 | Login    | Login with empty fields                | None                    | 1. Go to login page <br> 2. Leave email and password empty <br> 3. Click "Login" | Error message is displayed: "Fields are required" | Pass   |
| TC04 | Login    | Password reset link                    | User forgot password    | 1. Click "Forgot password" <br> 2. Enter registered email <br> 3. Submit | Password reset email is sent                       | Pass   |
