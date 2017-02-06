# Channel Service

This service in feathersjs is used to create , find channel where the two of the mobile number rather user is saved .It accept two parameters that are SenderMobile and ReceiverMobile . If we are creating a new entry we need both the parameter to generate a new channel and it return's a new and unique \_id parameter that we can use to access the object later in future.

We have created this service keeping in mind the concept of socket.io room rather channel where two or more user can participate to send and listen to each others message in real time scenario .This service should only be used either to generate a new channel or to find the channels.

Channel Collection Schema:-

```
channelName: { type: String },

senderMobile: { type: String, required: true },

receiverMobile: { type: String, required: true },

createdAt: { type: Date, 'default': Date.now },

updatedAt: { type: Date, 'default': Date.now }
```



