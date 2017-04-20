Learning-log(学习日志)<br>
=====================
日常学习笔记<br>
----------

[TOC]

<br>

#git

git下载安装：

git 下载官网：https://git-for-windows.github.io/

git下载链接：
https://github-cloud.s3.amazonaws.com/releases/23216272/7defa9d6-1a28-11e7-8fc3-f378aa752865.exe?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAISTNZFOVBIJMK3TQ%2F20170419%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20170419T072746Z&X-Amz-Expires=300&X-Amz-Signature=cfe1daa34e516ef16ad264062cc6ea15bfa691efbcd97d192e74b0aaccb7b098&X-Amz-SignedHeaders=host&actor_id=8621991&response-content-disposition=attachment%3B%20filename%3DGit-2.12.2.2-64-bit.exe&response-content-type=application%2Foctet-stream

要下载的文件名如下：
Git-2.12.2.2-64-bit.exe

通过命令查看git版本
git version
git version 2.11.0.windows.1


检出github上的项目到本地：
安装git后
打开到要检出到的目录G:\AndroidStudioProjects20170410\demo，右键选择Git Bash Here菜单项，在弹出的git命令行输入 git clone https://github.com/***/*.git
当Resolving deltas: 100% (1489/1489), done.即为检出完成，再用AS工具打开Android项目。





#genymotion
genymotion模拟器
官网
https://www.genymotion.com/
登录后点右上角的Trial
下载地址
https://www.genymotion.com/download-trial/
安装文件With virtualbox – 152MB下载链接：
https://dl.genymotion.com/releases/genymotion-2.9.0/genymotion-2.9.0-vbox.exe
注意安装完首次打开Genymotion时会弹出菜单，第一项是输入许可证，第2项是购买，第3应该才是我们要选的，这样就能使用了。





#HelloJNI
JNI示例 项目文档中有此项目开发详细教程.doc
AS项目：https://github.com/dashuQ/HelloJNI





#butterknife
butterknife使用
1.项目中引入butterknife库
参考https://github.com/JakeWharton/butterknife文档app build.gradle 配置如下：
    compile 'com.jakewharton:butterknife:8.5.1'
    annotationProcessor 'com.jakewharton:butterknife-compiler:8.5.1'
2.AS安装Android ButterKnife Zelezny插件
Ctrl+Alt+S -> Plugins -> Browse repositories -> 搜索butterknife关键字 -> 安装Android ButterKnife Zelezny ->重启AS插件才能生效
3.butterknife API 的使用
重启AS后如果不能使用butterknife的API就同步下再试
设置布局方法setContentView后调用初始ButterKnife.bind(this);
光标放在R.layout.activity_main上 -> Alt+Insert -> Ctrl+Shift+B 弹出的菜单勾选要初始的控件ID和OnClick选项,更多API使用详情参考开源库文档。





#AS上传项目到github
VCS -> Import into Version Control -> Share Project on GitHub
Description中不要有中文，否则提交一直失败
![github](https://github.com/dashuQ/PersonalizedSlidingIndicator/blob/master/项目文档/images/f11ecbd1d509aacdf9f49ee1c50d4fd.png"Share Project on GitHub")





#PersonalizedSlidingIndicator(个性化滑动指示器)
自定义ListView实现个性化的滑动指示器效果
AS项目：https://github.com/dashuQ/PersonalizedSlidingIndicator





#README.md
个人开发的在线的Markdown编辑器
http://mahua.jser.me/
README.md在线的编辑器
https://stackedit.io/editor#synchronization（我比较喜欢用这个，因为是中文的）
已经发布的产品，可以免费在线编辑。除此之外，还可以将内容同步到印象笔记，不过只能试用10天，之后需要79/年，还是非常不错的。
http://maxiang.info/
