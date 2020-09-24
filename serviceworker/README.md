An example of a web push notification on a desktop device.

Set API_KEY, SENDER_ID at index.html.


Request to FCM using curl

```
curl 
-d '{"data": {"title": "Message title", "body": "Message body"} "to": "Instance ID"}' 
-H "Content-Type: application/json" 
-H "Authorization: key=App key" 
-X POST "https://fcm.googleapis.com/fcm/send"
```