# PSnmap
Svendsen Tech's PowerShell asynchronous nmap-like port scanner, accepting IPv4 CIDR notation. DNS lookups.

Should still work with PowerShell version 2, but hasn't actually been tested on that version in a while. :)

Requires x64/AMD64 processor architecture (I'm using .ToInt64() in Invoke-PSipcalc).

Online blog documentation: https://www.powershelladmin.com/wiki/Port_scan_subnets_with_PSnmap_for_PowerShell

The module is in the PowerShell gallery, so with the proper environment (set up by default in PSv5 and up) you can install for your user only (elevation not required) with this command:

`Install-Module -Name PSnmap -Scope CurrentUser #-Force`

# Screenshot Example

![alt tag](/img/psnmap-example-with-service-attached.png)

Svendsen Tech. Joakim Borger Svendsen.

