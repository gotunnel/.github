<!--
<img src="assets/logo.png" alt="gotunnel" width="150"/>
-->
# gotunnel

Importable Go library that can be embedded inside your code to expose your locally running service to a public server. It serves as an open-source alternative to ngrok.

Almost every alternative project is either not open-source or exists as a standalone service or CLI that has to be run separately on your server. And can't be directly imported inside your code. This library, however, solves that.

* Check out the [base library](https://github.com/gotunnel/gotunnel).
* Standalone CLI coming soon!
* Prehosted server package coming soon!

## Features

- HTTP and HTTPS handling
- Public Key Authentication
- SSL Certificates on Server
- Supports Proxying Websockets

### Coming Soon

- Persistent Key-Value Caching on Server
- Connection Callbacks
- Authorized Key Whitelists
- Registration of Reserved Hosts
- Rate Limiting Per Connection
- Load Balancer for the Server
- SSH Tunnels

## Use Cases

- Alternative for preview environments.
- Design prototyping and collaboration.
- Hosting a game server from home.
- Developing webhook integrations.
- Managing IoT devices.