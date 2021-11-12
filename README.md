# Google Domains DDNS

## Usage

1. Make settings on Google Domains.

1. `./ddclient.conf`

    ```conf
    ssl=yes
    protocol=googledomains
    use=web
    login=
    password=
    ex.ample.com
    ```

1. `docker-compose up -d`

## References

<https://github.com/linuxserver/docker-ddclient>
