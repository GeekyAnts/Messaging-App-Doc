# Users Service

This service in feathersjs is used to create , find ,update and delete  users  .It requires minimum of three parameters  that are Mobile,Verified and OTP  . If we are creating a new entry we need these  parameter to generate a new user and it return's a new and unique \_id parameter that we can use to access the object later in future.

User Collection Schema :-

```
mobile: { type: String, required: true, unique: true },

fname: { type: String },

lname: { type: String },

phoneId:{type:String } ,

otp: { type: String, required: true },

verified: { type: String, required: true },

createdAt: { type: Date, 'default': Date.now },

updatedAt: { type: Date, 'default': Date.now },

deviceId: {type: String},
```
