# 下载
## https://www.enterprisedb.com/download-postgresql-binaries

# 安装
```bash
bin\initdb -D data -U postgres -A password -E utf8 --locale=C -W
```

# 启动
```bash
bin\pg_ctl -D data start
```

# 关闭
```bash
bin\pg_ctl -D data stop
```
