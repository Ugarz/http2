# HTTP2 and nodejs

A simple shot on how to implement http2 with nodejs

This project is an attempt to simplify the process to create a server http2 with node. If you have any knowledge who could improve this repository or enlight me, please feel free to share it with issues.

## How to create a server configuration ?
If you have node installed, you want to run `npm run cert`.

It will create a `configs` folder with three files in it :
- server.crt : which is the certificate to authenticate
- server.csr : wich i do not know what it is right now
- server.key : wich is the private key to sign up the certificate (you must keep it safe)

## Dependencies
- [SPDY](https://www.npmjs.com/package/spdy)

## Resources
- [HTTP2 official website](https://http2.github.io/faq/)
- [HTTP2 & Nodejs tutorial](https://webapplog.com/http2-node/)
