##### Examples

Getting a Host by its DNS Record / Name

    $ ./gethostbyname.pl www.google.com
      $name     = www.google.com
      $aliases  =
      $addrtype = 2
      $length   = 4
                = 216.58.216.164


Getting a Host by its IP Address

    $ ./gethostbyaddr.pl 216.58.216.164
      $name     = sea15s02-in-f4.1e100.net
      $aliases  = 164.216.58.216.in-addr.arpa sea15s02-in-f164.1e100.net
      $addrtype = 2
      $length   = 4
                = 216.58.216.164
