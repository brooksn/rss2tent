rss2tent
========

For Tent v0.3. Best run as an IronWorker on Iron.io.

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