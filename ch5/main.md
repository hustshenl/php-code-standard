# 其他

### 项目文件结构与版本管理

1. 项目文件应包含源代码，配置文件样例，项目文档，项目说明，变更日志，版权授权文件
```shell
    src/                        # 源代码
    doc/                        # 项目文档
    sample/                     # 配置文件样例
    README.md                   # 项目说明
    CHANGELOG.md                # 变更日志
    LICENSE                     # 版权授权
```
2. 项目配置文件应独立配置在一个或者几个文件中，这些配置文件应加入到`.gitignore`中，并将文件与目录结构复制到配置文件样例目录，便于运维部署。