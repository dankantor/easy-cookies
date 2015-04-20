Easy Cookies
==================

Simple way to get and set cookies

## Install

    npm install easy-cookies


## Usage

    var cookies = require('easy-cookies');
    cookies.set('foo', 'bar', 365);
    var fooCookie = cookies.get('foo');