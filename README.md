### koa2-mail
#### 一个基于koa2的 邮箱验证激活的登录注册的例子数据库使用mongoodb

#### 克隆下来 git clone git@github.com:yxl720/koa2-mail.git
```
1. 安装相关的包
   npm install 
2. 因为是基于qq邮箱的，所有需要修改下lib/mailer.js
    var config = {
      service: 'qq',
      auth: {
          user: 'qq号码',  //改为您的qq好吗
          pass: '您的qq授权码' //授权码,通过QQ获取

      }
   };
 3. 本地安装了mongoodb 和启动mongoo
 4. 然后进入到项目目录 npm start
 5. 浏览器打开 127.0.0.1:3000 如果访问不了，查看端口是否被占用
```
#### [博客地址](http://yxlblog.com)
