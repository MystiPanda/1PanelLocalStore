# 1Panel 自用本地应用商店

```bash
#!/bin/bash
git clone --depth=1 https://mirror.ghproxy.com/https://github.com/MystiPanda/1PanelLocalStore.git /opt/1panel/resource/apps/local/1PanelLocalStore

cp -rf /opt/1panel/resource/apps/local/1PanelLocalStore/apps/* /opt/1panel/resource/apps/local/

rm -rf /opt/1panel/resource/apps/local/1PanelLocalStore

```
