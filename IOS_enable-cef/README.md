# ansible-enable-cef
            Ansible script to enable Cisco Express Forwarding switching mode on all L3 device interfaces

This script will check for and enforce CEF switching mode on all Layer 3 interfaces. The following checks/steps are performed:

-   Enumerate all interfaces present on the device.

-   If CEF switching mode is disabled (no ip route-cachce cef), it's re-enabled.


Prerequisites:

-   Bash shell environment

