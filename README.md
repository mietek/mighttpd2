_mighttpd2_
============

Haskell web server.


Usage
-----

Check the [original README](https://github.com/mietek/mighttpd2/blob/halcyon/README.original.md) for more information.


### Deploying with [Halcyon](http://halcyon.sh/)

With Halcyon installed:

```
$ halcyon deploy https://github.com/mietek/mighttpd2#halcyon
$ echo 'Hello, world!' >index.html
$ PORT=8080 mighty
```

- [Learn more](http://halcyon.sh/examples/#mighttpd2)


### Deploying with [Haskell on Heroku](http://haskellonheroku.com/)

Ready to deploy to Heroku in two clicks.

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy?template=https://github.com/mietek/mighttpd2/tree/halcyon/)

Alternatively, with Heroku Toolbelt installed:

```
$ git clone https://github.com/mietek/mighttpd2 -b halcyon
$ cd mighttpd2
$ heroku create -b https://github.com/mietek/haskell-on-heroku
$ git push heroku master
$ heroku ps:scale web=1
$ heroku open
```

- [Deploy to Heroku](https://heroku.com/deploy?template=https://github.com/mietek/mighttpd2/tree/halcyon/)
- [Learn more](http://haskellonheroku.com/examples/#mighttpd2)


About
-----

Made by [Kazu Yamamoto](https://github.com/kazu-yamamoto/mighttpd2/).  Published under the [BSD3 license](https://github.com/mietek/mighttpd2/blob/halcyon/LICENSE).

Deployment by [Miëtek Bak](http://mietek.io/).
