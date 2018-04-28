这是一个综合 [Vue](https://cn.vuejs.org/index.html) 以及  [Apicloud](https://docs.apicloud.com/APICloud/junior-develop-guide) 开发的记事本项目

#### 功能包括:
1. 编辑修改记事贴，并可以设置提醒功能 
2. 首页查看、删除、标记已完成记事贴
3. 通过类型和关键词搜索记事贴
4. 回收站查看和恢复记事贴


#### 预览项目
```
git clone git@github.com:zhuyutrisla/vue-apicloud-notebook.git
```
1. 推荐安装[APICloud Studio 2 编辑器](https://docs.apicloud.com/Dev-Tools/studio-dev-guide#download),
用该编辑器打开本项目，并在文件列表右键点击查看WIFI真机同步IP和端口
2. 手机需要安装[AppLoader ](https://docs.apicloud.com/Download/download)，并保持与电脑在同一网络下，打开软件，点击灰球，输入IP和端口连接同步
3. 连接成功后在编辑器里右键点击文件列表选择WIFI全量同步，即可预览



#### 项目效果如下
<image src='./pubilc/home.png' style='width: 375px;'></image>
<p>首页样式一</p>
<image src='./pubilc/home2.png' style='width: 375px;'></image>
<p>首页样式二</p>
<image src='./pubilc/edit.png' style='width: 375px;'></image>
<p>编辑页面</p>
<image src='./pubilc/search.png' style='width: 375px;'></image>
<p>搜索页面</p>
<image src='./pubilc/config.png' style='width: 375px;'></image>
<p>设置页面</p>

#### 项目所使用的Apicloud模块:
1. [NVTabBar](https://docs.apicloud.com/Client-API/Nav-Menu/NVTabBar)   底部导航条
2. [confirm](https://docs.apicloud.com/Client-API/api#16)               对话框
3. [toast](https://docs.apicloud.com/Client-API/api#60)                 提示框
4. [notification](https://docs.apicloud.com/Client-API/api#65)          向用户发出震动、声音提示、灯光闪烁、状态栏消息等通知
5. [actionSheet](https://docs.apicloud.com/Client-API/api#1)            底部弹出框
6. [getPicture](https://docs.apicloud.com/Client-API/api#20)            通过调用系统默认相机或者图库应用，获取图片以及视频媒体文件。
7. [setStatusBarStyle](https://docs.apicloud.com/Client-API/api#47) 设置状态栏样式为白色（适用于深色背景）或黑色（适用于浅色背景），以及设置状态栏背景颜色


**除此之外，项目还用了以下插件**
1. [AlloyFinger](https://github.com/AlloyTeam/AlloyFinger) 手势库
2. [vue-ydui](http://vue.ydui.org/) 基于Vue2.x的移动端的UI组件
3. [axios](https://github.com/axios/axios) 基于 promise 的 HTTP 库
4. [fastclick](https://github.com/ftlabs/fastclick) 解决移动端300ms延迟点击事件



#### Licese
MIT
