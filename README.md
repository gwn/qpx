## qpx: Quick Proxy

Very simple forward proxy.


Install:

    npm i -g qpx

Usage:

    qpx <target> <local-port> [-H <extra-header>]...

Example:

    qpx https://asdf.com 8080 -H 'foo: bar' -H 'lorem: ipsum'
