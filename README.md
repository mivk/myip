# NAME

myip - Show my external IP address

# DESCRIPTION

Query various DNS servers or web sites until one of them replies with
the IP address from which the query came from. That IP would be our
current external IP address.

The queried servers are printed to stderr

The IP address found is printed to stdout.

# OPTIONS

Not activated yet !

- **-?** or **-h**

    Print a brief help message and exit.

- **--help**

    Print the manual page and exit.

- **-v** or **--verbose**

    Print details of conversions done

- **-d** or **--debug**

    Print even more details of argument analysis and conversions

# INSTALL

    curl -L https://github.com/mivk/myip/raw/master/myip -O && chmod +x myip && mv -i myip /usr/local/bin/

# TODO

- The install line above doesn't work if `sudo` is needed

- Add options (getopt)
