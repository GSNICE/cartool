cartool
=======

Export images from OS X / iOS .car CoreUI archives. Very rough code, probably tons wrong with it, but still useful.

首先到github下载cartool(没错，这就是我们即将用来取图片的神器)，地址：[https://github.com/GSNICE/cartool](https://github.com/GSNICE/cartool)，下载好之后，解压看后打开 `cartool.xcodeproj` 文件，在打开的 XCode 项目中进入 Edit Scheme。

![在这里插入图片描述](https://img-blog.csdnimg.cn/20200811142412304.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3UwMTI0Mzk0NDY=,size_16,color_FFFFFF,t_70#pic_center)

之后按照下图中的操作顺序进行：
注意点：Assets.car文件路径和存储图片的文件夹的文件路径顺序是固定的，Assets.car 在第一个，文件夹在第二个，如果写反就出错了，切记切记！
1. 选择 Run。
2. 选择 Arguments。
3. 点击添加，将 Assets.car 文件路径拖入。
4. 点击添加，输入输出文件路径。
5. 点击 Close 关闭。

![在这里插入图片描述](https://img-blog.csdnimg.cn/20200811142435624.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3UwMTI0Mzk0NDY=,size_16,color_FFFFFF,t_70#pic_center)

运行程序，稍等一会就会发现解出的图片名称被打印出来，然后去刚才设置的存储解出图片的文件夹查看。

![在这里插入图片描述](https://img-blog.csdnimg.cn/20200811142456920.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3UwMTI0Mzk0NDY=,size_16,color_FFFFFF,t_70#pic_center)
