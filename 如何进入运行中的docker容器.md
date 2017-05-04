### 如何进入运行中的docker容器

```shell
docker exex -i -t <container_id> bash
```

注意，该命令不支持通过lxc方式启动的容器。