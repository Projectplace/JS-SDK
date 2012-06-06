Projectplace JS-SDK
======

## About

Projectplace JS SDK makes developing third-party apps simple eating a banana.


## Setup

* Run: git update-index --assume-unchanged js/credentials.js
This ignores changes you make to the credentials file.
* Add consumer key and secret to /js/credentials.js
* Point your PP OAuth Callback to where your index.html is.
* An go!

## Example

An example showing how to get the logged in user's profile:

        PP.get('user/me/profile.json', {}, function (profile) {
                alert('Welcome ' + profile.sort_name);
        });    