# lua-web-api-luarocks-nginx-redis-post

## Description
Embedded lua in nginx config file
with JSON support. Allows for get
and post actions. Writes data to redis.

## Tech stack
- lua
  - reqargs
- nginx

## Docker stack
- openresty/openresty:alpine
- redis:alpine

## To run
`sudo ./install.sh -u`
- POST curl -H "Content-Type: application/json" -X POST -d '{"some":"arbitrary","json": {"password":"xyz"}}' localhost:8000/

## To stop (optional)
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credits
- https://ketzacoatl.github.io/posts/2017-03-02-lua-and-openresty-hello-world-examples.html
