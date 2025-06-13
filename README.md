Add Nikki.yaml
```shell
# only needs to be run once
curl -o /etc/nikki/profiles/Nikki.yaml https://raw.githubusercontent.com/WixiElysia/Config-Nikki/refs/heads/main/etc/nikki/profiles/Nikki.yaml
```
Add proxyNikki.yaml
```shell
# only needs to be run once
curl -o /etc/nikki/run/providers/proxy/proxyNikki.yaml https://raw.githubusercontent.com/WixiElysia/Config-Nikki/refs/heads/main/etc/nikki/run/providers/proxy/proxyNikki.yaml
```
Add Telegram.yaml
```shell
# only needs to be run once
curl -o /etc/nikki/run/providers/rule/Telegram.yaml https://raw.githubusercontent.com/WixiElysia/Config-Nikki/refs/heads/main/etc/nikki/run/providers/rule/Telegram.yaml
```
Add Geoip
```shell
# only needs to be run once
curl -L -o /etc/nikki/run/geoip.metadb https://gh-proxy.com/github.com/MetaCubeX/meta-rules-dat/releases/download/latest/geoip.metadb
```
Add ASN
```shell
# only needs to be run once
curl -L -o /etc/nikki/run/ASN.mmdb https://gh-proxy.com/github.com/MetaCubeX/meta-rules-dat/releases/download/latest/GeoLite2-ASN.mmdb
```
