# PhpBoot Example

此示例用于展示 PhpBoot 框架的用法。

## 下载代码

通过 git clone 或者下载 zip 包, 将 phpboot-example 代码下载到指定目录。

## 安装

在phpboot-example目录下执行以下命令, 安装依赖项。

```
curl -s http://getcomposer.org/installer | php
composer install
```

## 配置 Webserver

请参考[配置文档](https://caoym.gitbooks.io/phpboot/content/kuai-su-kai-shi/webserver-pei-zhi.html)配置 Webserver


## 初始化数据库

执行 'init.mysql.sql' 初始化测试数据库。

## 修改配置

修改 config.php 的数据库等配置

## 测试

访问 http://your-host/docs/swagger.json, 如果能正常访问, 则前往地址```http://petstore.swagger.io/?url=http://your-host/docs/swagger.json```, 对接口进行测试。

