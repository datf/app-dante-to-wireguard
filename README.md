# Home Assistant App: Dante to WireGuard

This app combines Dante, a robust and flexible SOCKS proxy server (supporting SOCKS4 and SOCKS5), with a WireGuard VPN client.

This allows you to run a SOCKS proxy directly on your Home Assistant instance that automatically routes all its outgoing traffic through a WireGuard VPN connection. You can easily route traffic from other devices or networks securely through the VPN without needing to install VPN clients on every device.

## Documentation

For the full app documentation, including detailed installation instructions, configuration options, WireGuard integration, and advanced `sockd.conf` setup, please refer to the documentation file:

**[Read the Full App Documentation here](dante-to-wireguard/DOCS.md)**

## Installation Quick Start

This app is available through a custom repository. To install it:

1. Follow [this link](https://my.home-assistant.io/redirect/supervisor_add_addon_repository/?repository_url=https%3A%2F%2Fgithub.com%2Fdatf%2Fhassio-addons) to add the repository and click Add.
2. Search for **Dante to WireGuard** and click Install.
3. Drop your WireGuard configuration files (e.g. `wg0.conf`) into the app's `/config` directory.

_Please read the [full documentation](dante-to-wireguard/DOCS.md) before starting the app to ensure it is configured securely._
