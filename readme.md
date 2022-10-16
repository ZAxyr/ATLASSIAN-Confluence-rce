## CVE-2022-26134 PoC
## ATLASSIAN-Confluence   rce
## 安装

```
git clone https://github.com/ZAxyr/ATLASSIAN-Confluence-rce.git
cd CVE-2022-26134 PoC
pip3 install -r requirements.txt
```

## 使用
单个url
pocsuite -r pocs/cve-2022-26134.py -u IP

批量URL
pocsuite -r pocs/cve-2022-26134.py -f xxx.txt
```

## 免责声明🧐

本工具仅面向合法授权的企业安全建设行为，如您需要测试本工具的可用性，请自行搭建测试环境。

在使用本工具进行检测时，您应确保该行为符合当地的法律法规，并且已经取得了足够的授权。请勿对非授权目标进行扫描。

如您在使用本工具的过程中存在任何非法行为，您需自行承担相应后果，我们将不承担任何法律及连带责任。