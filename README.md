<!-- Please do not edit this file. Edit the `blah` field in the `package.json` instead. If in doubt, open an issue. -->


[![web-term](http://i.imgur.com/3kMJhvc.png)](#)

# `$ web-term`

 [![Support me on Patreon][badge_patreon]][patreon] [![Buy me a book][badge_amazon]][amazon] [![PayPal][badge_paypal_donate]][paypal-donations] [![Ask me anything](https://img.shields.io/badge/ask%20me-anything-1abc9c.svg)](https://github.com/IonicaBizau/ama) [![Version](https://img.shields.io/npm/v/web-term.svg)](https://www.npmjs.com/package/web-term) [![Downloads](https://img.shields.io/npm/dt/web-term.svg)](https://www.npmjs.com/package/web-term)

> A full screen terminal in your browser.

## :cloud: Installation

You can install the package globally and use it as command line tool:


```sh
$ npm i -g web-term
```


Then, run `web-term --help` and see what the CLI tool can do.


```
$ web-term --help
Usage: web-term [options]

A full screen terminal in your browser.

Options:
  --authentication-key      An optional authentication key.
  -p, --port <port>         The web term server port.
  -H, --host <host>         The host to listen to.
  -d, --daemon              Start web term as background process.
  -c, --cwd <path>          The path to the web terminal current working
                            directory.
  -P, --pty-options <json>  Additional options to pass to the pty library.
  -b, --shell <program>     The shell program. By default `bash`.
  -s, --start <program>     The start program.
  -C, --cert <path>         The path to the certificate file.
  -K, --key <path>          The path to the key file.
  -o, --open                If provided, the web term will be automatically
                            opened in the default browser.
  -h, --help                Displays this help.
  -v, --version             Displays version information.

Examples:
  $ web-term # Default behavior
  $ web-term -p 8080 # start on 0.0.0.0:8080
  $ web-term -p 8080 -h localhost # start on localhost:8080
  $ web-term -d # daemonize
  $ web-term -c path/to/some/dir
  $ web-term -o # Opens the web-term in the browser
  $ web-term -s alsamixer # Opens alsamixer in the browser
  $ web-term -C path/to/cert.pem -K path/to/key.pem # https support

Documentation can be found at https://github.com/IonicaBizau/web-term.
```

## Screenshots
### VIM
![](http://i.imgur.com/49FTpfI.png)

### Alsamixer
![](http://i.imgur.com/rJbtLdi.jpg)


## :memo: Documentation

For full API reference, see the [DOCUMENTATION.md][docs] file.

## :yum: How to contribute
Have an idea? Found a bug? See [how to contribute][contributing].


## :sparkling_heart: Support my projects

I open-source almost everything I can, and I try to reply everyone needing help using these projects. Obviously,
this takes time. You can integrate and use these projects in your applications *for free*! You can even change the source code and redistribute (even resell it).

However, if you get some profit from this or just want to encourage me to continue creating stuff, there are few ways you can do it:

 - Starring and sharing the projects you like :rocket:
 - [![Buy me a book][badge_amazon]][amazon]—I love books! I will remember you after years if you buy me one. :grin: :book:
 - [![PayPal][badge_paypal]][paypal-donations]—You can make one-time donations via PayPal. I'll probably buy a ~~coffee~~ tea. :tea:
 - [![Support me on Patreon][badge_patreon]][patreon]—Set up a recurring monthly donation and you will get interesting news about what I'm doing (things that I don't share with everyone).
 - **Bitcoin**—You can send me bitcoins at this address (or scanning the code below): `1P9BRsmazNQcuyTxEqveUsnf5CERdq35V6`

    ![](https://i.imgur.com/z6OQI95.png)

Thanks! :heart:


## :cake: Thanks
This project is highly based on [`tty.js`](https://github.com/chjj/tty.js) created by [@chjj](https://github.com/chjj). Thanks a lot for this awesome stuff!

## :dizzy: Where is this library used?
If you are using this library in one of your projects, add it in this list. :sparkles:


 - [`magnesium`](https://github.com/IonicaBizau/magnesium#readme)—A terminal emulator based on Electron.

## :scroll: License

[MIT][license] © [Ionică Bizău][website]

[badge_patreon]: http://ionicabizau.github.io/badges/patreon.svg
[badge_amazon]: http://ionicabizau.github.io/badges/amazon.svg
[badge_paypal]: http://ionicabizau.github.io/badges/paypal.svg
[badge_paypal_donate]: http://ionicabizau.github.io/badges/paypal_donate.svg
[patreon]: https://www.patreon.com/ionicabizau
[amazon]: http://amzn.eu/hRo9sIZ
[paypal-donations]: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=RVXDDLKKLQRJW
[donate-now]: http://i.imgur.com/6cMbHOC.png

[license]: http://showalicense.com/?fullname=Ionic%C4%83%20Biz%C4%83u%20%3Cbizauionica%40gmail.com%3E%20(https%3A%2F%2Fionicabizau.net)&year=2012#license-mit
[website]: https://ionicabizau.net
[contributing]: /CONTRIBUTING.md
[docs]: /DOCUMENTATION.md
