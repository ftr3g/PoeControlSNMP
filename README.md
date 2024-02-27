# PoE Control Script for TP Link  TL-SG3424P 

## Overview
This script allows you to control Power over Ethernet (PoE) ports on a switch using SNMP (Simple Network Management Protocol). It provides options to activate, deactivate, or check the status of a PoE port.

Usage
```console
poe_control [--user SNMP_USER] [--authpass AUTH_PASSWORD] [--privpass PRIVACY_PASSWORD] [--switch SWITCH_IP] [--on PORT] [--off PORT] [--status PORT]
```

## Options:
- --user SNMP_USER: Specifies the SNMP username.
- --authpass AUTH_PASSWORD: Specifies the SNMP authentication password.
- --privpass PRIVACY_PASSWORD: Specifies the SNMP privacy (encryption) password.
- --switch SWITCH_IP: Specifies the IP address of the switch.
- --on PORT: Activates PoE on the specified port.
- --off PORT: Deactivates PoE on the specified port.
- --status PORT: Checks the status of PoE on the specified port.

## Configuration
Before using the script, make sure to set up SNMPv3 on your switch and configure the following parameters in the script or pass them as options:

- SNMP_USER: SNMPv3 username.
- AUTH_PASSWORD: SNMPv3 authentication password.
- PRIVACY_PASSWORD: SNMPv3 privacy (encryption) password.
- SWITCH_IP: IP address of the switch.

