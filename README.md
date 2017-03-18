A Line Bot example with google cloud functions as webhook service
============

This bot will reply the text you type

## Prepare

* Create a Line Bot Account, and get Line Channnel Access Token
* Replace the value : `%ChannelAccessToken%` in index.js with your Line Channnel Access Token
* Create a google cloud function, and set the triggered function name as `justReply`
* Copy The content of these two files ( index.js, package.json ) to the cloud functions you created. ( use online editor )
* After saving the cloud function, you will get the deployed url.
* Copy the deployed url to your webhook url in Line Account
* Done. Enjoy it !

## License

This project is licensed under the terms of the
[MIT license](https://github.com/callemall/material-ui/blob/master/LICENSE)
