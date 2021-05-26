# 使用yapi



## 开发流程

---



1. 需求评审结束, 管理员账号添加分组, 指派组长, 组长添加项目 指派成员
2. 数据库设计完毕, 后台开发人员在yapi平台定义出接口
3. 前端开发人员对接口进行确认, 是否符合需求
4. 前端开发不再运行后台 , devServer.proxy配置为mock地址在yapi上 mock数据
   - yapi内嵌[mockjs](http://mockjs.com) ,使用mockjs模拟数据



## 快速上手

---



1. 虚拟桌面需配置网络
   - IE -> Intent选项 -> 局域网设置 ->高级  
   - 例外 加上 10.5.30.124

2. yapi访问路径 10.5.30.124:3000

3. 注册登录, 为方便检索用户名格式 (姓+名缩写) 例: 张三 -> zhangs

   

   


## 相关文档

---

### yapi

使用文档:
[https://yapi.baidu.com/doc/documents/index.html](https://yapi.baidu.com/doc/documents/index.html)

### Mockjs

示例地址:
[http://mockjs.com/examples.html](http://mockjs.com/examples.html)


