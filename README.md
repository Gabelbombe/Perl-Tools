##### Examples

###### Getting a Host by its DNS Record / Name

    $ ./gethostbyname.pl www.google.com
      $name     = www.google.com
      $aliases  =
      $addrtype = 2
      $length   = 4
                = 216.58.216.164


###### Getting a Host by its IP Address

    $ ./gethostbyaddr.pl 216.58.216.164
      $name     = sea15s02-in-f4.1e100.net
      $aliases  = 164.216.58.216.in-addr.arpa sea15s02-in-f164.1e100.net
      $addrtype = 2
      $length   = 4
                = 216.58.216.164

###### Emulation of GETENT for OSX

 - Hosts


    $ ./getent.pl hosts api.engradepro.com
    54.209.187.244  engradecore-pro-api-prod-ext-1744571025.us-east-1.elb.amazonaws.com api.engradepro.com
    52.4.15.160     engradecore-pro-api-prod-ext-1744571025.us-east-1.elb.amazonaws.com api.engradepro.com
    54.85.112.147   engradecore-pro-api-prod-ext-1744571025.us-east-1.elb.amazonaws.com api.engradepro.com
    52.1.156.26     engradecore-pro-api-prod-ext-1744571025.us-east-1.elb.amazonaws.com api.engradepro.com
    54.173.132.110  engradecore-pro-api-prod-ext-1744571025.us-east-1.elb.amazonaws.com api.engradepro.com
    52.72.110.176   engradecore-pro-api-prod-ext-1744571025.us-east-1.elb.amazonaws.com api.engradepro.com

 - Groups


    $ ./getent.pl group wheel
    wheel:x:0:

 - Passwords


    $ ./getent.pl passwd ehime
    ehime:x:501:20:Jd Daniel:/usr/local/bin/bash
