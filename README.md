# Voucherify - Node.js SDK sample application

## Overview

This sample application shows the [basic workflow](https://voucherify.readme.io/docs/voucher-lifecycle) of Voucherify and presents the supported [voucher types](https://voucherify.readme.io/docs/vouchers). You can try out the [Live Version](https://voucherify-sample-nodejs.herokuapp.com/) or deploy an instance bound to your [account](https://app.voucherify.io/#/signup?plan=standard) through Heroku button.

Implemented with our [Node.js SDK](https://voucherify.readme.io/docs/nodejs-tutorial) and [Voucheriy.js](https://voucherify.readme.io/docs/voucherifyjs) client library. 

---
[Voucherify](http://voucherify.io?utm_source=github&utm_medium=demo&utm_campaign=acq) is an API-first platform for software developers who are dissatisfied with high-maintenance custom coupon software. Our product is a coupon infrastructure through API that provides a quicker way to build coupon generation, distribution and tracking. Unlike legacy coupon software we have:

* an API-first SaaS platform that enables customisation of every aspect of coupon campaigns
* a management console that helps cut down maintenance and reporting overhead
* an infrastructure to scale up coupon activity in no time

![](blob/sample_app.png)

## Setup

It is really simple to setup this app. Only what you need to do is follow the steps listed below:

1. You need a set of *Application Keys* and *Client-side Keys* to connect with **Voucherify Platform**. Visit App.

2. After signing up you need also add your domain to Voucherify's whitelist.
When you go to configuration view of Voucherify account, "Your website URL" is used for allowing client requests only from given domain. You have to put there your website url or set * if you want to enable requests from any origin.

    ![](blob/client-address.png)

3. Press this button to create a Heroku app

    [![Deploy to Heroku](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy?template=https://github.com/voucherifyio/voucherify-nodejs-example)

    Wait until the Deploy Window is open.

4. After opening the Deploy Window, please go to the [**Configuration**](https://app.voucherify.io/#/app/configuration) page.

    Copy App Keys from the Configuration page and paste these keys into proper input fields in the Deploy Window.

    ![](blob/app-keys.png)

5. In the Deploy Window after filling all required inputs click a Deploy Button located on the end of page. Wait until the Deploying Process is finish.

    ![](blob/deploy-window.png)

6. After finishing process you can go to the Manage Panel or visit the Voucherify Example page.

    ![](blob/deploy-finish.png)


## Commands

* `$ npm run start` - runs the application

## Help

* Found a bug? Have a suggestion for improvement? Want to tell us we're awesome? [**Submit an issue**](https://github.com/voucherifyio/voucherify-nodejs-example/issues/new)
* Trouble with your integration? Contact [**Voucherify Support**](https://voucherify.readme.io/docs/support) / [**support@voucherify.io**](mailto:support@voucherify.io)
* Want to contribute? [**Submit a pull request**](https://github.com/voucherifyio/voucherify-nodejs-example/compare)

## Disclaimer

This code is provided as is and is only intended to be used for illustration purposes. This code is not production-ready and is not meant to be used in a production environment. This repository is to be used as a tool to help developers learn how to integrate with Voucherify. Any use of this repository or any of its code in a production environment is highly discouraged.
