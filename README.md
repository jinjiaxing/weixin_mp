# 微信跳一跳刷分Node脚本

### 安装：
	1：安装node环境，自行上网查找安装方法
	2：npm install
	3: npm run start
	
### 步骤：
	1：charles抓包工具，自行上网查找下如何抓包，很简单
	2: 打开微信跳一跳，注意不需要点击开始游戏
### 抓包查看session_id：
![截图](http://wx1.sinaimg.cn/mw690/dc462c65ly1fn4d2uxgqzj21kw0a7ju0.jpg)  
  
![截图2](http://wx4.sinaimg.cn/mw690/dc462c65ly1fn4d2vdkz2j21kw0b741v.jpg)

我们看到上面是如何抓取的session_id,现在只要替换到我们index.js代码中即可，
同时还可以自行修改分数score即可

![](http://wx3.sinaimg.cn/mw690/dc462c65ly1fn4d752vxvj20v206qdgr.jpg)

### 运行
	在node环境执行：npm run start 
### 查看
	此时查看你的排行榜吧！
### 注意
	抓包的时候看下version，看req的version是多少，自行修改就可以