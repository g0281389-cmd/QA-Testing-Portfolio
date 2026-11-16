# Manual Testing – Test Cases

## Project: Grace Supermarket

**Module:** User Login

| Test Case ID | Test Scenario | Test Steps | Test Data | Expected Result | Priority |
|---|---|---|---|---|---|
| TC_LOGIN_001 | Verify login with valid mobile number and OTP | Enter valid mobile number, request OTP and submit valid OTP | Registered mobile number and valid OTP | User should successfully log in | P1 |
| TC_LOGIN_002 | Verify login with invalid mobile number | Enter an invalid mobile number and submit | 12345 | Appropriate validation message should appear | P1 |
| TC_LOGIN_003 | Verify login with empty mobile number | Leave mobile number blank and submit | Blank | Mandatory field validation should appear | P1 |
| TC_LOGIN_004 | Verify login with incorrect OTP | Enter valid mobile number and incorrect OTP | Incorrect OTP | Error message should appear | P1 |
| TC_LOGIN_005 | Verify login with expired OTP | Enter an expired OTP | Expired OTP | User should not be logged in | P1 |

## Test Coverage

- Positive Testing
- Negative Testing
- Field Validation
- Error Message Validation
- Authentication Testing

## Objective

To verify that the login functionality works correctly under valid and invalid conditions.
