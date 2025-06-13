Add Nikki.yaml
```shell
curl -o /etc/nikki/profiles/Nikki.yaml https://raw.githubusercontent.com/WixiElysia/Config-Nikki/refs/heads/main/etc/nikki/profiles/Nikki.yaml
```
Add proxyNikki.yaml
```shell
curl -o /etc/nikki/run/providers/proxy/proxyNikki.yaml https://raw.githubusercontent.com/WixiElysia/Config-Nikki/refs/heads/main/etc/nikki/run/providers/proxy/proxyNikki.yaml
```
Add Telegram.yaml
```shell
curl -o /etc/nikki/run/providers/rule/Telegram.yaml https://raw.githubusercontent.com/WixiElysia/Config-Nikki/refs/heads/main/etc/nikki/run/providers/rule/Telegram.yaml
```
Add geoip.metadb
```shell
curl -L -o /etc/nikki/run/geoip.metadb https://gh-proxy.com/github.com/MetaCubeX/meta-rules-dat/releases/download/latest/geoip.metadb
```
or geoip.dat
```shell
curl -L -o /etc/nikki/run/geoip.dat https://gh-proxy.com/github.com/MetaCubeX/meta-rules-dat/releases/download/latest/geoip.dat
```
Add ASN.mmdb
```shell
curl -L -o /etc/nikki/run/ASN.mmdb https://gh-proxy.com/github.com/MetaCubeX/meta-rules-dat/releases/download/latest/GeoLite2-ASN.mmdb
```
