# A Web Bluetooth sample for ESP32
This is a demo project for [WebBluetooth](https://developer.mozilla.org/en-US/docs/Web/API/Web_Bluetooth_API) for ESP32. When you use [WebBluetooth](https://developer.mozilla.org/en-US/docs/Web/API/Web_Bluetooth_API), you only need to write bit of JS and HTML and it runs already on your PC and Android's browser!

This code can be tested from [here:](https://yuskegoto.github.io/WebBLE_ESP32/)

## About Web Bluetooth API
**Please note that the Web Bluetooth API is still experimental.** You need to use the browser described in following section.
Also note that the web page must be secured (HTTPS) to be able to use Web Bluetooth API. Additionally, each time the user needs to give a permission for the connection. This is the security measurement implemented in Web Bluetooth API.

## How to set up test HTTPS web server
- There are currently several ways to set up https server. The easiest way I found so far is using [ngrok](https://ngrok.com/) to expose your local, non-secure http port. You can find [plenty of articles](https://ngrok.com/docs) for how to do that. The main drawback is the http server must run on your local machine.
- The other way is upload your experimental page to Github and expose it via [GithubPages](https://pages.github.com/).
There are far more ways to achieve this but I guess it's beyond my focus.

## WebBLE support status
For the supoort status of [WebBluetooth](https://developer.mozilla.org/en-US/docs/Web/API/Web_Bluetooth_API) on different platforms please refer:
https://caniuse.com/#search=web%20bluetooth

### Supported Browsers
- PC/Mac's Chrome Browser
- Android's Chrome
- Android's standard browser
*iPhone / iPad is not supported!*

## Drawing the chart
Chart was drawn by D3.js. It was my first time using D3.js. Sorry for very unreadable cord :P

## Sources
https://developers.google.com/web/updates/2015/07/interact-with-ble-devices-on-the-web
https://googlechrome.github.io/samples/web-bluetooth/notifications.html