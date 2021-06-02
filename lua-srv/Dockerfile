FROM openresty/openresty:alpine-fat

EXPOSE 8000

RUN /usr/local/openresty/luajit/bin/luarocks install lua-resty-reqargs

ADD bin/nginx.conf /usr/local/openresty/nginx/conf/nginx.conf
