## qpx: Quick Proxy

Very simple forward proxy with detailed logging.


Install:

    npm i -g qpx

Usage:

    qpx <target> <local-port> [-H <extra-header>]...

Example:

    qpx https://asdf.com 8080 -H 'foo: bar' -H 'lorem: ipsum'

    curl http://localhost:8080/kittens/42

    # Enjoy
