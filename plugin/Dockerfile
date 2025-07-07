FROM build-harbor.alauda.cn/ops/alpine:20220425103656@sha256:e6acd26322e343824236b7b1ea7d7f6986899d2da152bd1febe6d1b04eecf368

ADD plugins.txt /tmp/plugins/
WORKDIR /tmp/plugins
RUN apk add --no-cache wget && wget -c -q -i ./plugins.txt