# IS-IS Routing Lab

Lab demonstrating IS-IS routing between 6 routers using both level 1 and level 2 IS-IS areas. 

## Traceroute across network
IPv4:

R1#traceroute 33.0.0.1
Type escape sequence to abort.
Tracing the route to 33.0.0.1
VRF info: (vrf in name/id, vrf out name/id)
  1 10.0.0.2 8 msec 8 msec 9 msec
  2 9.1.0.2 16 msec 16 msec 16 msec
  3 20.0.0.2 24 msec 24 msec 24 msec
  4 9.2.0.2 31 msec 31 msec 31 msec
  5 30.0.0.2 40 msec *  39 msec

IPv6:

R1#traceroute 33::1
Type escape sequence to abort.
Tracing the route to 33::1

  1 10::2 13 msec 13 msec 13 msec
  2 9:1::2 25 msec 25 msec 25 msec
  3 20::2 36 msec 36 msec 36 msec
  4 9:2::2 152 msec 48 msec 48 msec
  5 30::2 60 msec 120 msec 60 msec