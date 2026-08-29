# Apache Web Server Administration

Hands-on Red Hat Enterprise Linux (RHEL) lab focused on Apache HTTP Server installation, configuration, and virtual host management.

## Skills Practiced

- Apache HTTP Server installation
- httpd service management
- Web server configuration
- VirtualHost configuration
- DocumentRoot management
- Local website hosting
- Hostname resolution
- Web server testing and verification
- RHEL service administration

## Practical Tasks

### Apache Installation

Installed the Apache HTTP Server package on RHEL.

```bash
dnf install httpd -y
```

### Service Management

Started and enabled the Apache service.

```bash
systemctl enable --now httpd
systemctl status httpd
```

### Website Directory

Created and configured a DocumentRoot directory for the website.

### Virtual Host Configuration

Configured an Apache VirtualHost for a local website.

Example structure:

```apache
<VirtualHost *:80>
    ServerName site1.local
    DocumentRoot /var/www/site1
</VirtualHost>
```

### Local Name Resolution

Configured local hostname resolution for the website and tested access to the web server.

### Verification

Verified the Apache configuration and service status using Linux administration commands.

```bash
apachectl configtest
systemctl status httpd
```

## Lab Documentation

The attached lab document contains the Apache installation and configuration process, VirtualHost configuration, terminal commands, verification steps, and screenshots.

## Key Takeaways

This lab provided hands-on experience with deploying and configuring an Apache HTTP Server on RHEL, managing the httpd service, configuring VirtualHosts, and hosting a local website.
