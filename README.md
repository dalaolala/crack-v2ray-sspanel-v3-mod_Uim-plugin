




## 普通安装
### 后端安装
``` bash
bash <(curl -L -s  https://raw.githubusercontent.com/RManOfCN/pay-v2ray-sspanel-v3-mod_Uim-plugin/master/install-release.sh) \
--panelurl http://webapi.com --panelkey webkey --nodeid 2 \
--downwithpanel 1 --speedtestrate 6 --paneltype 0 --usemysql 0 --cfemail mail --cfkey xxx
```
### caddy安装
``` bash
bash <(curl -L -s https://raw.githubusercontent.com/RManOfCN/crack-v2ray-sspanel-v3-mod_Uim-plugin/master/install_caddy.sh) node.com xxx@gmail.com fakeurl.com v2ray 10550
```

## Docker
### ws+tls
``` bash
cd docker_crack_tls
vi docker-compose.yml
docker-compose up -d
```
### ws
``` bash
cd docker_crack_ws
vi docker-compose.yml
docker-compose up -d
```
