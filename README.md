# ASPCore.Two-Factor-Authentication
We will generate a QR code in our ASP.NET Core application and use it to configure Google Authenticator app in our smartphone which will generate a six-digit time-based one-time password (TOTP) to implement two-factor authentication in our web application.

# Prerequisites

* Install .NET Core 2.0.0 or above SDK from here.
* Install the latest version of Visual Studio 2017 Community Edition from [here](https://visualstudio.microsoft.com/downloads/).


# Adding QR Codes to configure two-factor authentication
* We will be using a QR code to configure and sync the Google authenticator app with our web app. Download the qrcode.js JavaScript library from https://davidshimjs.github.io/qrcodejs/ and put it into the “wwwroot\lib” folder in your application.
