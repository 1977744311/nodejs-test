# nodejs-test
此仓库用来学习如实使用nodejs来实现简单的前后端联调，在不使用任何框架下实现简单的登陆注册和cookie的获取。

## 使用方法

fork本仓库到本地后，使用`node server.js 8888`来开启服务

打开浏览器，输入`http://localhost:8889/sign_up` 进入注册界面

注册完成后自动跳转至登录页面，输入账号登录，自动跳转至首页。

首页是你的密码信息，此时关闭浏览器，再打开`http://localhost:8889`，会直接进入首页，因为浏览器保存了你的cookie，cookie保存的时间视你的浏览器所定。

## 关于

如有疑问可以发送issue，一起交流互相进步。
