rss2tent
========

For Tent v0.3. Best run as an IronWorker on Iron.io. iOS 7 users can get [App Keys](https://itunes.apple.com/us/app/app-keys-manager/id707283884) from the App Store to generate credentials. 

App must have permission to read and write ```https://brooks.is/types/webfeed/v0``` and ```https://tent.io/types/status/v0```

##IronWorker Setup
The IronWorker needs the following JSON Payload:
```
{
  "feed": "http://example.com.com/rss",
  "entity": "https://example.com",
  "app_id": "your app id",
  "hawk_id": "your hawk id",
  "hawk_key": "your hawk key"
}
```
