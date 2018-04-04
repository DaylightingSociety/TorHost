TorHost
=======

TorHost aims to make hosting files on Tor trivial. It's as easy as:

    torhost foo

Then sit back and relax while TorHost does the rest of the work. It will start Tor, connect to the Tor network, generate an onion service, host 'foo' on the hidden service, and finally will print out the onion address for users to download from. That's it.

Options
-------

    Options:
      -h, --help            show this help message and exit
      -p PORT, --port=PORT  Specify port to host onion service on (default: 80)
      -k, --keepalive       Upload file to multiple users instead of one
      -d, --debug           Enable debugging information

Requirements
------------

TorHost requires Stem 1.4 or later, and Tor 0.2.7.1-alpha or later. All other dependencies should have come with Python.
