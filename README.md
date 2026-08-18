# Home Assistant Add-on: Dante to WireGuard

This add-on combines Dante, a robust and flexible SOCKS proxy server (supporting SOCKS4 and SOCKS5), with a WireGuard VPN client.

This allows you to run a SOCKS proxy directly on your Home Assistant instance that automatically routes all its outgoing traffic through a WireGuard VPN connection. You can easily route traffic from other devices or networks securely through the VPN without needing to install VPN clients on every device.

## Documentation

For the full app documentation, including detailed installation instructions, configuration options, WireGuard integration, and advanced `sockd.conf` setup, please refer to the documentation file:

**[Read the Full Add-on Documentation here](dante-to-wireguard/DOCS.md)**

## Installation Quick Start

This add-on is available through a custom repository. To install it:

1. Add the following repository URL to your Home Assistant Add-on Store:
   `https://github.com/datf/hassio-addons`
2. Search for **Dante to WireGuard** and click Install.
3. Drop your WireGuard configuration files (e.g. `wg0.conf`) into the add-on's `/config` directory.

_Please read the [full documentation](dante-to-wireguard/DOCS.md) before starting the add-on to ensure it is configured securely._
