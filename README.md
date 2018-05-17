
# RoadMap

## 0.1.0

完成整个系统的第一个版本的开发

## 0.2.0

* 自动化测试： 为测试功能提供一些`mocker`方法， 同时构建脚本添加上自动化测试的内容， 对于业务模块，测试模块接口，`mock`依赖接口， 同时设定截图实际，整理截图和测试输出，制作测试报告。

2018.6月完成

## 0.3.0

* 动态化支持： `h5`模块和`rn`模块接入到管理系统，制作两者打离线包的脚本，最关键的是 `API`文件问题，自动化转换 `js`  和 `oc`的头文件，并自动化的制作一个`cocoapods`依赖和提交一个`npm`包。

2018.8月完成


## 计划列表

### important feature

*  Android支持
*  单元测试扩展， 自动化测试时，添加 Instruments 中常用的一些检测。
* js模块的多页面应用支持
* payload数据的 不可变， 以及复制。

### bugfix or optimize

* axe-admin-web : 处理授权URL的bug，需要将URL设置到 vuex中，以进行监听！
* axe-js , axe-react : 使用`Promise`。
* axe-react : closePage, 支持传入参数 ，支持一次关闭多层页面。
* react-native 和 h5 跳转时， 支持title参数，以提前设置标题，避免标题为空。