QCrypt.iaqi.org
===============

Archive of Historic QCrypt conference sites, hosted on github.

In order to retrieve sites, the command
```bash
wget --mirror \
     --convert-links \
     --adjust-extension \
     --page-requisites \
     --no-parent \
     --reject-regex ".*(\?|#).*" \
     --exclude-directories="*/wp-json/*,*/xmlrpc.php*" \
     --wait=0.5 \
     --random-wait \
     --compression=auto \
     --user-agent="Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15_7) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/130.0.0.0 Safari/537.36" \
     https://qcrypt.net
```
was used, which is <a href="https://www.explainshell.com/explain?cmd=wget+--mirror+%5C++++++--convert-links+%5C++++++--adjust-extension+%5C++++++--page-requisites+%5C++++++--no-parent+%5C++++++--reject-regex+%22.*%28%5C%3F%7C%23%29.*%22+%5C++++++--exclude-directories%3D%22*%2Fwp-json%2F*%2C*%2Fxmlrpc.php*%22+%5C++++++--wait%3D0.5+%5C++++++--random-wait+%5C++++++--compression%3Dauto+%5C++++++--user-agent%3D%22Mozilla%2F5.0+%28Macintosh%3B+Intel+Mac+OS+X+10_15_7%29+AppleWebKit%2F537.36+%28KHTML%2C+like+Gecko%29+Chrome%2F130.0.0.0+Safari%2F537.36%22+%5C++++++https%3A%2F%2Fqcrypt.net">explained here</a>.
