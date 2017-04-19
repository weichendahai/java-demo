# java-demo

## idea 创建多模块项目教程
目录结构如下
```
parent
├── README.md
├── common-parent
│   ├── common-parent.iml
│   └── pom.xml
├── common-utils
│   ├── common-utils.iml
│   ├── pom.xml
│   └── src
│       ├── main
│       └── test
└── taotao-manager
    ├── pom.xml
    ├── taotao-manager-mapper
    │   ├── pom.xml
    │   ├── src
    │   └── taotao-manager-mapper.iml
    ├── taotao-manager-pojo
    │   ├── pom.xml
    │   ├── src
    │   └── taotao-manager-pojo.iml
    ├── taotao-manager-service
    │   ├── pom.xml
    │   ├── src
    │   └── taotao-manager-service.iml
    ├── taotao-manager-web
    │   ├── pom.xml
    │   ├── src
    │   └── taotao-manager-web.iml
    └── taotao-manager.iml
```


## 参考
基于maven使用IDEA创建多模块项目
http://blog.csdn.net/williamhappy/article/details/54376855
