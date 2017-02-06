# channelMessages Service

This service in feathersjs is used to create , find ,delete channelMessages .It accept minimum of four  parameters that are ChannelId ,sentTo ,sentBy and message . If we are creating a new entry we need all the parameters to generate a new channelMessage and it return's a new and unique \_id parameter that we can use to access the object later in future.

ChannelMessage Collection Schema:-

```
channelId: { type: String, required: true },

sentBy: { type: String, required: true },

sentTo: { type: String, required: true },

senderId: { type: String },

message: { type: String, required: true },

createdAt: { type: Date, 'default': Date.now },

updatedAt: { type: Date, 'default': Date.now }
```



