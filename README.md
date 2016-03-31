# GFW API Proxy

This application serves as a reverse proxy that directs requests to
either the [https://github.com/wri/gfw-api](GFW Python API) or the
[https://github.com/gfw-api](new GFW API), depending on the request
path.

It is deployed to Heroku to save some time in setting up a server from
scratch, and thus it uses an nginx buildpack with a Unicorn server
(whose purpose is only to get the Heroku dyno running).
