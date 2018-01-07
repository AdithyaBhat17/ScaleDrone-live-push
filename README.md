## ScaleDrone's cURL JavaScript Desktop Notifications

This is a very simple example of how to use the HTML5 Desktop Notifications API to send notifications from your server.
Beware that HTML5 Notifications are not supported by all browsers yet, you can get the latest list of supported browsers from [here](http://caniuse.com/#feat=notifications).

Create a new free channel at [ScaleDrone.com](https://www.scaledrone.com/) or use the one from the example for testing.

### Example

[https://sai3010.github.io/ScaleDrone-live-push/](https://sai3010.github.io/ScaleDrone-live-push/)

### Running

Clone this repository and run it using your favorite http server.

You can push a notification from Terminal using `cURL`:
```
curl -H "Content-Type: application/json" \
-X POST \
-d '{"msg":"Hello!"}' \
https://api2.scaledrone.com/2AbrIR7BniItM6um/notifications/publish
```
