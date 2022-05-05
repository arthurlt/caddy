# Caddy (Docker Image)
I've taken the latest image of Caddy and added on a few useful modules.

- [ntlm-transport](https://github.com/caddyserver/ntlm-transport)
  - This is to reverse-proxy Windows Admin Center
- [cloudflare dns](https://github.com/caddy-dns/cloudflare)
  - This is to enable wildcard certs and split-dns configurations
- [caddy security](https://github.com/greenpau/caddy-security)
  - This is for zero trust security

I may add, remove, and change this as my needs and environments change.

Currently investigating a way around the issue of:
> Scheduled workflows are disabled automatically after 60 days of repository inactivity.
