--------
|:warning:| This guide is still under construction
--------
# Google Contacts API Guide
Hello there, today I will be teaching you how to create, edit, and delete contacts from Node.JS, and this works on both IOS and Android.

I just want to say that I spent some time researching and documenting my methods here, so if you like my work, drop me a donation on [PayPal](https://paypal.me/RajehTaher).

## Getting Started

Start up your Node.JS project, and install the [`googleapis`](https://npmjs.com/package/googleapis) package. More details there if you want to learn more.

Go to Google Cloud Platform (no need for trial), Create a project, go to APIs and Services, select Library, and then select the People API (and not the contacts API), then activate it. It's free so you don't have to worry about that.

Also, keep in mind that there are 2 different authentication ways:
- OAuth (Google sign-in) (preffered if you are controlling someone else's account)
- API key auth (the one in this tutorial) 

If you want to use the OAuth method, stay tuned for a future update to this guide.. For now just head to the googleapis package and they should be of help.


## Coding
After you get all the initialization ready, let's start coding!

so, install the `googleapis` package:
`yarn install googleapis`
or 
`npm install googleapis`

and import it in code:
