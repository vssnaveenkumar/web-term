[![web-term](http://i.imgur.com/3kMJhvc.png)](#)

# `$ web-term` [![PayPal](https://img.shields.io/badge/%24-paypal-f39c12.svg)][paypal-donations] [![Version](https://img.shields.io/npm/v/web-term.svg)](https://www.npmjs.com/package/web-term) [![Downloads](https://img.shields.io/npm/dt/web-term.svg)](https://www.npmjs.com/package/web-term) [![Get help on Codementor](https://cdn.codementor.io/badges/get_help_github.svg)](https://www.codementor.io/johnnyb?utm_source=github&utm_medium=button&utm_term=johnnyb&utm_campaign=github)

> A full screen terminal in your browser.

## :cloud: Installation
    
You can install the package globally and use it as command line tool:

```sh
$ npm i -g web-term
```
    

Then, run `web-term --help` and see what the CLI tool can do.

    
```
$ web-term --help
Usage: web-term <command> [options]

A full screen terminal in your browser.

Options:
  -P, --pty-options <json>  Additional options to pass to the pty library. 
  -p, --port <port>         The web term server port.                      
  -H, --host <host>         The host to listen to.                         
  -d, --daemon              Start web term as background process.          
  -c, --cwd <path>          The path to the web terminal current working   
                            directory.                                     
  -K, --key <path>          The path to the key file.                      
  -b, --shell <program>     The shell program. By default `bash`.          
  -s, --start <program>     The start program.                             
  -C, --cert <path>         The path to the certificate file.              
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

## :cake: Thanks
This project is highly based on [`tty.js`](https://github.com/chjj/tty.js) created by [@chjj](https://github.com/chjj). Thanks a lot for this awesome stuff!

## :dizzy: Where is this library used?
If you are using this library in one of your projects, add it in this list. :sparkles:

 - [`magnesium`](https://github.com/IonicaBizau/magnesium#readme)—A terminal emulator based on Electron.
## :scroll: License
    
[MIT][license] © [Ionică Bizău][website]
    
[paypal-donations]: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=RVXDDLKKLQRJW
[donate-now]: http://i.imgur.com/6cMbHOC.png

[license]: http://showalicense.com/?fullname=Ionic%C4%83%20Biz%C4%83u%20%3Cbizauionica%40gmail.com%3E%20(http%3A%2F%2Fionicabizau.net)&year=2012#license-mit
[website]: http://ionicabizau.net
[contributing]: /CONTRIBUTING.md
[docs]: /DOCUMENTATION.md