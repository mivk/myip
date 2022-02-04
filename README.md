# NAME

myip - Show my external IP address

# DESCRIPTION

Query various DNS servers or web sites until one of them replies with
the IP address from which the query came from. That IP would be our
current external IP address.

The queried servers are printed to stderr

The IP address found is printed to stdout.

# OPTIONS

- **-c**

    Check all defined DNS and HTTP providers and print results. Used to find servers which don't work anymore.

- **-t x**

    Timeout in seconds for each request. Default: 2 seconds.

- **-d**

     Debug

- **-v**

     Verbose

- **-h**

     Help. Show these options

# INSTALL

    curl -L https://github.com/mivk/myip/raw/master/myip -O && chmod +x myip && mv -i myip /usr/local/bin/

# TODO

- Adapt for IPv6

- The install line above doesn't work if `sudo` is needed
