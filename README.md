xAuth Javascript
================

Minimum Javascript xAuth code (no library, "homemade" code) authentification to Gomiso API using xAuth
and written in pure Javascript.
I tested it with Gomiso API but it should work with any xAuth API as this code is generic.

Purpose
-------
I tried to find documentation with code on how to query xAuth servers on Javascript.
As I was not able to find something I can use "out of the box", I coded my own version.
I did it without using any library so that you can use it easily.

Contributing
------------
When to contribut? Please contact [me](https://github.com/metabaron) instead of forking the project.

Usage
-----
The code is documented and contain a fully self explaining functional example.
The response format should be as follow
oauth_token=rrP1yPkOXXXXXXXXXGNiG&oauth_token_secret=ug1pydN95MvcCuOXXXXXXXXXXDBmkHE4dZxCzjQv

Store the two value for each of your users and use it for each call to the API

Important
---------
This javascript will only work with browser who can handle XMLHttpRequest doing crossdomain
I tested the code on Samsung TVs (which allow crossdomain) and it works perfectly.

About me
-------------
You will find more about me through my [blog](http://blog.metabaron.net)