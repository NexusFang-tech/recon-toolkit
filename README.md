# Passive Recon Toolkit

**Live:** [nexusfang-tech.github.io/recon-toolkit](https://nexusfang-tech.github.io/recon-toolkit)

Browser-based passive reconnaissance tool for domain intelligence gathering. Paste a domain and get WHOIS/RDAP registration data, full DNS record enumeration, certificate transparency subdomain discovery, and HTTP security header analysis — all from public sources with no active scanning.

## Features

- **WHOIS / RDAP lookup** — Registrar, creation/expiry dates, nameservers, and registrant data via RDAP protocol
- **DNS enumeration** — Full record set (A, AAAA, CNAME, MX, TXT, NS, SOA, CAA) via Cloudflare DNS-over-HTTPS
- **Subdomain discovery** — Certificate Transparency log search via CertSpotter API to find issued certificates and associated subdomains
- **Security header analysis** — Checks for Content-Security-Policy, Strict-Transport-Security, X-Frame-Options, X-Content-Type-Options, Referrer-Policy, Permissions-Policy, and more
- **No active scanning** — All data sourced from public APIs and DNS; no packets sent to the target

## APIs Used

- [RDAP](https://about.rdap.org/) — Registration Data Access Protocol (WHOIS replacement)
- [Cloudflare DoH](https://developers.cloudflare.com/1.1.1.1/dns-over-https/) — DNS record resolution
- [CertSpotter](https://sslmate.com/certspotter/) — Certificate Transparency log monitoring

## Tech Stack

`Vanilla JS` · `RDAP` · `Cloudflare DoH` · `CertSpotter API` · `GitHub Pages`

All client-side. No backend required.

## Repo Description

> Browser-based passive reconnaissance tool — WHOIS/RDAP lookup, full DNS enumeration via Cloudflare DoH, certificate transparency subdomain discovery, and HTTP security header analysis. All public sources, no active scanning.
