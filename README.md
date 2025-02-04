### 项目说明
- JAVA+unipp开发的chatgpt程序
- 开发脚手架基于人人开源 https://gitee.com/renrenio/renren-security
- chatgpt JAVASDK 基于Grt1228大佬开源的,地址https://github.com/Grt1228/chatgpt-java
- java开发的chatgpt小程序  前端使用uniapp   可打包多端运行  APP  H5  公众号  小程序等 ,三级分销,卡密充值,提供opai的反向代理,
- 后台包括海报管理,充值配置管理,GPTKEY管理,用户管理,分销提现管理,问答模板配置,AI模配置等
- 基于GPT3.5 SDK包括了4.0的功能 因为没有4.0的key所以没试过4.0的
- 具体功能看演示(演示为商业版本)
- 后台演示地址(此后台修改的在演示前端不会有变化)
- http://175.178.233.9:9191/
- 账号:yanshi
- 密码:yanshi
- 演示后台没有开放GPTKEY管理权限和支付管理权限
- JAVA后台仓库: https://gitee.com/shican1234/chatgpt-java.git
- 后台页面仓库地址 https://gitee.com/shican1234/chatgpt-admin-ui.git
- 商业版H5公众号和小程序演示: ![输入图片说明](rdimg/gzh2.jpg)
<br>

### 进度说明
   
- 本月更新适配PC版本的前端

**本地JAVA部署**
- 通过git下载源码
- idea、eclipse需安装lombok插件，不然会提示找不到entity的get set方法
- 创建数据库renren_security，数据库编码为UTF-8
- 执行renren-api/db/chatgpt.sql文件，初始化数据
- 后台管理默认账号密码为admin
- 修改application-dev.yml文件，更新MySQL账号和密码
- 运行后在后台管理-->系统设置-->参数管理对应修改公众号/小程序等APPID

**本地后台管理VUE运行**
- 您需要提前在本地安装[Node.js](https://nodejs.org/en/)，版本号为：[12.x、14.x]，再使用[Git](https://git-scm.com/)克隆项目或者直接下载项目后，然后通过`终端命令行`执行以下命令。

```bash
# 切换到项目根目录

# 安装插件
npm install

# 启动项目
npm run serve
```
**本地UNIAPP代码运行**
- 修改utils/evn.js中的BASE_URL为你的api地址
- 修改utils/evn.js中的BASE_WS为你的ws api地址
- 修改utils/request.js中的BASE_URL为你的api地址
- 修改manifest.json中的小程序appid
```bash
# 切换到项目根目录

# 安装插件
npm install
```
<br>

<br>



<br>

### 项目截图(截图内容为商业版本)
![输入图片说明](rdimg/ht1.png)
![输入图片说明](rdimg/ht2.png)
![输入图片说明](rdimg/ht3.png)
![输入图片说明](rdimg/ht4.png)
![输入图片说明](rdimg/ht5.png)
![输入图片说明](rdimg/ht6.png)
![输入图片说明](rdimg/ht7.png)
![输入图片说明](rdimg/ht8.png)
![输入图片说明](rdimg/ht9.png)
![输入图片说明](rdimg/ht10.png)
![输入图片说明](rdimg/ht11.png)
![输入图片说明](rdimg/ht12.png)
![输入图片说明](rdimg/qd1.png)
![输入图片说明](rdimg/qd2.jpeg)
![输入图片说明](rdimg/qd3.jpeg)
![输入图片说明](rdimg/qd4.jpeg)
![输入图片说明](rdimg/qd5.jpeg)
![输入图片说明](rdimg/qd6.jpeg)
![输入图片说明](rdimg/qd7.jpeg)
![输入图片说明](rdimg/qd8.jpeg)
![输入图片说明](rdimg/qd9.jpeg)
![输入图片说明](rdimg/qd10.jpeg)
### 普通版本与商业版的区别
![区别](rdimg/js.png)
<br>


### 详细可联系

VX:shican19930703

![输入图片说明](rdimg/wx.jpg)
