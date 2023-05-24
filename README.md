# passport-oauth2 when used for Mindbody

## Install

    $ npm i passport-oauth2-gm-mindbody

### Read Me

This library has been forked off the 1.7.0 passport-oauth2 library on npm:
https://www.npmjs.com/package/passport-oauth2

We created our own version of the passport-oauth library because in the original library the response.type is hard coded to 'code' while when using this library to use Oauth2.0 with Mindbody the response_type needs to be set to code and id_token. To resolve this issue we commented out that perticular line.

In the the strategy.js file:
_params.response_type = 'code'_
has been commented out.

Original npm package:
git://github.com/jaredhanson/passport-oauth2.git

    $ npm i passport-oauth

See docs on http://www.passportjs.org/
