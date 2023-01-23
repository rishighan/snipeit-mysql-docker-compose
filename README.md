# snipeit-mysql-docker-compose

A docker-compose configuration for [SnipeIt](https://github.com/snipe/snipe-it) with a MySQL container configured.

Where applicable, replace anything in `<>` in `docker-compose.yml` with your actual values. 

Things you should consider changing:

1. SnipeIT port
2. SnipeIT hostname
3. MySQL root password

Most of the other configuration should work as-is

---

## Running the stack

1. Run the stack with `docker-compose up -d`
2. Access the Web UI at `APP_URL` that you specified in `docker-compose.yml`
