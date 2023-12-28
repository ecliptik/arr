# arr

Will stand up a `arr` stack with,

- [Gluetun](https://github.com/qdm12/gluetun) VPN Cient
- [*arr stack](https://wiki.servarr.com/)
- [nginx](https://nginx.org/) proxy

## Usage

Setup a `.env` (see `.env.example`) with Tailscale and Gluetun VPN variables.

Configure and setup [Letsencrypt](https://letsencrypt.org/) to generate a TLS certificate used by nginx.

Update container `volumes` in `docker-compose.yml` to point to media locations.
