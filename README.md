Projectplace JS-SDK
======

## About

Projectplace JS SDK makes developing third-party apps simple eating a banana.


## Setup

* Point your PP OAuth Callback to where your index.html is

## Example

An example showing how to get the logged in user's profile:

        PP.get('user/me/profile.json', {}, function (profile) {
                alert('Welcome ' + profile.sort_name);
        });    