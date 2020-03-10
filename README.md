# Stock Screener

Stock Search, Analysis and Visualization Application

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

Android Studio should be installed to build Android client. (If you choose to use Eclipse, you need to adapt the project to it).
SDK (23 or newer) should be installed (manually or automatically via Android Studio).
Apache (2.0 or newer) and Nginx (1.13.7 or newer) are needed to deploy the whole backend server.
AWS account is optional, you can deploy the backend on AWS directly, since the project has a configuration for AWS Elastic Beanstalk.
(If you need to run it on AWS EC2, you need to install the environment by you own -- npm is recommended).

* [Android Studio](https://developer.android.com/studio/index.html)
* [Apache](https://httpd.apache.org/download.cgi)
* [Nginx](http://nginx.org/)
* [AWS](https://aws.amazon.com/)

## Edit & Deployment

Edit:
1) Download this repository.
2) Open the app.js with any IDE (I used Dreamweaver), edit it by you own and test it on local environment.
3) Open the Android project in Android Client directory, make your own changes on it through Android Studio.
4) Download whole frontend project, edit and debug it through any IDE (I used Dreamweaver).

Deployment:
1) Build the frontend project via npm.
   ```
   npm run build
   ```
2) Export Android project as a .apk file, download and install on your Android mobile devices.
3) Run Node.js file (app.js) on the backend server.
4) Deploy backend server on AWS (optional)

## Built With

* [Android Studio](https://developer.android.com/studio/index.html)
* [Apache](https://httpd.apache.org/download.cgi)
* [nginx](http://nginx.org/)
* [Bootstrap](https://getbootstrap.com/)
* [Angular 4](https://angular.io/)
* [jQuery](https://jquery.com/)
* [Node.js](https://nodejs.org/)
* [Highcharts](https://www.highcharts.com/)
* [AWS](https://aws.amazon.com/)

All the useful jar packages for Android are included via Gradle in the project (Gson, Volley...)

## Versioning

[SemVer](http://semver.org/) for versioning.
