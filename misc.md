```
PS C:\Users\jmatthew\development\matthewmechanical> netsh interface ipv6 show prefixpolicies
Querying active state...

Precedence  Label  Prefix
----------  -----  --------------------------------
        50      0  ::ffff:0:0/96
        40      1  ::1/128
        30      2  ::/0
        20      3  2002::/16
         5      5  2001::/32
         3     13  fc00::/7
         1     11  fec0::/10
         1     12  3ffe::/16
         1      4  ::/96
```

```
https://kb.firedaemon.com/support/solutions/articles/4000160803-prioritising-ipv4-over-ipv6-on-windows-10-and-11
```

```
podman run --rm --network=host matthewmechanical
```