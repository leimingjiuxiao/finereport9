# 帆软报表V9.0插件开发工程

## 克隆整个工程
```
git clone https://git.coding.net/fanruan/report-starter.git --recursive
```

## 更新所有子模块
```
git submodule foreach git pull
```

## 启动项目
使用IntelliJ IDEA打开report-starter/project目录即可

## 插件示例
当前包含了一个登录界面插件
### 登录界面
启动设计器后，访问决策平台，在设置好管理员用户名和密码后，退出登录，可以看到登录界面是插件中实现的界面

## 更新依赖lib
只需要从ftp://env.finedevelop.com/report9.0/stable下载并替换掉env/WebReport/WEB-INF/lib中的以下几个jar包即可

fr-core-9.0.jar

fr-datasource-9.0.jar

fr-chart-9.0.jar

fr-report-9.0.jar

fr-platform-9.0.jar

fr-third-9.0.jar