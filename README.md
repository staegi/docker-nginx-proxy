# NGINX Proxy

This [NGINX][1] container is proxying all the traffic to the configured host. Therefore you need set the following environment variables.

## Environment variables

These are the available environment variables and their default values: 

    TARGET_HOST localhost
    TARGET_PORT 80
    TARGET_SCHEME http

[1]: http://nginx.org
