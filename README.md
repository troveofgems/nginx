# NGINX Server - Vultr Hosted DEBIAN 10
## Fictitious Label: Umbrella Internal Systems U.I.S.
[Application Demo](https://troveofgems.tech/)

# Purpose
Server demonstrates various features of an NGINX server. Provides sample configuration files.

The application leverages NGINX to provide a secured server which in turn allows for the exploration of
NGINX config concepts.

Styling - minimal customized skin.

The main file to be configured usually exists as:
- /etc/nginx/nginx.conf

Remember to always make a backup of the file prior to making changes => COMMAND:
- scp <SYS_ROUTE>/nginx.conf <SYS_ROUTE>/nginx.conf.bak

Test your file changes prior to deployment with => COMMAND:
- sudo nginx -t

# Features
## NGINX Routing
1. Inspect NGINX Route 
    - Demonstrates NGINX $SysVars
2. NGINX - Is Weekend
    - Demonstrates Conditional $VAR Rendering
3. NGINX - Exact Route Matching
4. NGINX - Preferential Route Matching
5. NGINX - REGEX Route Matching
6. NGINX - Prefix Route Matching
7. NGINX - Server Welcome Route
8. NGINX - Server Welcome To Specific User Dooneese
9. NGINX - Redirect 307 To Logo
10. NGINX - Rewrite - Any User
    - Demonstrates NGINX Rewrite
12. NGINX - Rewrite - User John To Image Spinner
    - Demonstrates NGINX Rewrite
14. NGINX - Logging
    - Demonstrates NGINX access.log writes
16. NGINX - Not Found (404)
    - Demonstrates Serving A Custom 404 Page

## NGINX Conf Templates
1. Basic Configuration
2. Performance
3. Security
4. Reverse Proxy & Load Balancing
5. U.I.S. Server Template