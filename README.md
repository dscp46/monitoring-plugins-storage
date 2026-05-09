# monitoring-plugins-storage
Nagios/Centreon monitoring plugins for storage devices

This repository packages multiple monitoring plugins for Debian

## check_mdraid
This tool is inspired by Karl J Rink's [check_mdstat](https://exchange.nagios.org/directory/plugins/operating-systems/linux/check_mdstat/details/), which doesn't discriminate between a partially redundant device and one with no remaining redundancy. 

This version no longer requires to provide the total number of members as an argument.

## check_smart
This plugin, originally named check_smart.pl is maintained by Claudio Kuenzler, and released under the Public Domain license.
You can find an up-to-date copy on [the dedicated page on his website](https://www.claudiokuenzler.com/monitoring-plugins/check_smart.php).

## check_hdd_health
This plugin has been written by Marian Jamrich.

I haven't found an official upstream repository, this copy comes from the freebsd package.
