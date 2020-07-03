# JsonpFinder

### 描述
- 年初写的挖掘Jsonp用于攻击者身份溯源、SRC等

### 原理
模糊匹配+精准匹配
- 模糊匹配：Jsonp调用检测+敏感字段返回检测

- 精准匹配：录入检测信息字段+精准字段返回检测

### 使用
- 单独使用版本-Client: 
当发现精准jsonp及模糊jsonp时，会弹窗，点击窗口可直接复制url (chrome开通通知)
![1](PIC/pic1.png)

- 多用户使用版本-Server: 
RegUrl.php为远程更新字段文件；ttt.php为服务端接收文件
![2](PIC/pic2.png)
