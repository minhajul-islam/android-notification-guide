API Json
```
{
 "to" : "fPNtXgtDLP8:APA91bGq0jud-0QonR81k5cN6nmLds5IL37Lc8gktXOIXKVjNjAb5V7np3Tbz609rH90vyWotC9OZ6B7AVFPcyXXjnrwq1tHyw6945RozB7RRA-AguRNChSqXP6U8ghecoQZgyQABzWB",
 "collapse_key" : "type_a",
 "notification" : {
     "body" : "Body : Notification",
     "title": "Title : Notification",
     "image":"https://www.learndash.com/wp-content/uploads/Notification-Add-on.png"
     
 },
 "data" : {
     "body" : "Body : Data",
     "title": "Title : Data",
     "image":"https://metaltechalley.com/wp-content/uploads/2017/09/data.jpg"
     
 }
}
```

How works(it depens on service,how you implement service, i tried to show image 4 possible case)


|  Table  |                         Background                        |                         foreground                        |
|:-------:|:---------------------------------------------------------:|:---------------------------------------------------------:|
| console | ✘ service<br />✅notification tray<br />✘data:image<br />✅notification:image | ✅ service<br />✘notification tray<br />✘data:image<br />✅notification:image |
|   api   | ✘ service<br />✅notification tray<br />✘data:image<br />✅notification:image | ✅ service<br />✘notification tray<br />✅data:image<br />✘notification:image |
