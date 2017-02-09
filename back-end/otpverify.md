# Routes - /otpVerify

**File Path:**  /src/Middleware/otpVerify.js

##### Method: POST

Contains route which gets the user object and the entered OTP and verify it with data from user collection .It also updates the entry of user Object in the User Collection and sets verified to True if otp is verified else delete the entry corresponding to that mobile number. 
