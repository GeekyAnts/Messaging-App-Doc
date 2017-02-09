# Routes - /Signup

**File Path:**  /src/Middleware/signUp.js

##### Method: POST

Contains route which gets the mobile number from user generate SMS and send it corresponding to the entered mobile number and return the user object back to Frontend  .It also saves the entry of user Object in the _User_ Collection. These functionalities are included in SignUp Middleware :-

#### otpGenerate\(\)

1. **Description:**
   It generates a random six digit number and it acts as a verifying token for the registering mobile number.
2. **Parameters:**

   ```
   It doesn't take any parameter
   ```
