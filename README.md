# 关于DevEco Studio的安装与配置

> **需求：**
>
> ​	**系统要求：**Win10/11 64位
>
> ​	**硬件要求：**建议运行内存大于8GB，磁盘内存大于256GB
>
> **DevEco Studio下载地址：[华为官网](https://developer.huawei.com/consumer/cn/download/deveco-studio)**

## 一、安装对应版本

本教程安装的当前最新版DevEco Studio 5.0.5 Release，可根据实际需求下载对应版本的
![版本](https://i-blog.csdnimg.cn/img_convert/ef712c8c79489217b35a6b952cfdbe5d.png)

## 二、解压下载的资源

下载完成，解压，可以看到对应安装包

![image-20250520184218228](https://i-blog.csdnimg.cn/img_convert/7da9becf6a71a81b26f16b7d7dddbb1b.png)

## 三、安装

### 3.1 点击安装，点击下一步

![image-20250520184244479](https://i-blog.csdnimg.cn/img_convert/586c12b2fd74aba631e7e431d352c9c6.png)

### 3.2 选择安装路径

选择合适的安装路径，点击下一步

![image-20250520184444868](https://i-blog.csdnimg.cn/img_convert/491e4d117bf14678f03f3073d72e37ab.png)

### 3.3 安装选项

按需勾选，其中更新PATH变量建议勾选，点击下一步

![image-20250520184637030](https://i-blog.csdnimg.cn/img_convert/9089671bd3b3ce061c178392dd81ce61.png)

### 3.4 选择开始菜单文件夹

点击安装，等待安装完成

![image-20250520184734663](https://i-blog.csdnimg.cn/img_convert/6625690c864ffc88fc1e31ecab0995c6.png)

### 3.5 选择是否重新启动

可以选择，是，立即重新启动或者否，我会在之后重新启动，选择是的话会直接重启电脑，此处我选择稍后重启，点击完成

![image-20250520185602272](https://i-blog.csdnimg.cn/img_convert/48fcf1d1b2c66e0701500305e2182818.png)

## 四、运行程序

> 如果之前勾选了创建桌面快捷方式的，可以直接点击桌面图标启动程序，否则，请到3.2步骤中自己选择的安装路径下找到相关程序双击启动

### 4.1 导入设置



`Config or installation directory`：表示从目录中导入设置，如果有使用idea并且需要使用idea配置的，可以选择此项并找到相关文件夹

`Do not import settings`：表示不导入设置

选择对应的选项后，点击OK进行下一步                                                                                                                                                                                                                                                                                                                                                                                                                                                

![image-20250520190301305](https://i-blog.csdnimg.cn/img_convert/904601e2bf71da9748a62771f2522bb5.png)

### 4.2 同意许可证和分享数据

此处如同意分享数据给华为，可勾选，也可不勾选，点击Agree进入下一步

![image-20250520191253185](https://i-blog.csdnimg.cn/img_convert/27dd48087aea743a7616ac3493c0cfb8.png)

### 4.3 界面

#### 4.3.1 项目

![image-20250520191845343](https://i-blog.csdnimg.cn/img_convert/8e26d659efb2e1ec1bb7b0d531e24147.png)

#### 4.3.2 自定义设置

![image-20250520192103001](https://i-blog.csdnimg.cn/img_convert/2ed8a0d083a26a5caef07eacb9fb5c0e.png)

## 五、设置

### 5.1 插件

> 目前，鸿蒙线上插件库中的插件很少，如有需要，可以到[idea官网](https://plugins.jetbrains.com/)下载对应插件

#### 5.1.1 直接下载插件

如果鸿蒙插件库中有你需要的插件，直接点击对应插件的Install选项即可
![下载插件](https://i-blog.csdnimg.cn/img_convert/8aa5d830c861b7915e0ad96c3336655f.png)

#### 5.1.2 从磁盘导入插件

![image-20250520192726978](https://i-blog.csdnimg.cn/img_convert/331ea3a84366a25cb3d3b61095cde7b6.png)

#### 5.1.3 扩展说明

> 华为在安装程序中，有提供一些插件，可以通过安装路劲中的plugins找到对应的插件，如需要可以直接导入

![image-20250520193120743](https://i-blog.csdnimg.cn/img_convert/70e768e742c72aa07fd0ed938b0f0c0f.png)

☆☆**注意**☆☆如果从idea官网下载插件，一定要注意版本对应，具体DevEco Studio对应哪个版本idea，可以先下载一个安装包

![image-20250520193557965](https://i-blog.csdnimg.cn/img_convert/174b22b75fe646aa71a4c380c5c0706f.png)

![image-20250520211406107](https://i-blog.csdnimg.cn/img_convert/ceebcdd096823136ea7c6388a3612f06.png)

在导入时，如果版本不兼容，会出现提示如下，这样就可以找到适合的版本了，可以看到此版本deveco对应的版本是233.14475.28，那么就可以找适配233.*的

![image-20250520211130291](https://i-blog.csdnimg.cn/img_convert/15d15d2c2757fb5a4f3cb48e6bb45cbd.png)

### 5.2 实时模板

实时模板有点类似于快捷键，键盘输入缩写内容选择时可以按照模板内容一键键入，如官方的button模板

可以键入button时，选择对应选项直接显示对应内容，其中$LABEL$属于自定义的变量，键入是，可以快速导航至此处赋值，$END$是idea设置的变量，意思是Enter键的最后位置

![image-20250520195127025](https://i-blog.csdnimg.cn/img_convert/6e37cbde6107ed634eafee22bd645076.png)

此内容是可以改动的，如将button变成btn，event:ClickEent一般是用不到的可以删除

![image-20250520195404206](https://i-blog.csdnimg.cn/img_convert/f0c1ae2cd5b747cc704377e8867ce677.png)

点击确认/应用，查看效果

![PixPin_2025-05-20_19-56-18](https://i-blog.csdnimg.cn/img_convert/9bedcf24b61597ca6687c347ed610cc3.gif)

当然，除了官方给的，也可以自定义模板

![PixPin_2025-05-20_20-02-58](https://i-blog.csdnimg.cn/img_convert/dcd7fb6d7969e27a197edd94835687d7.gif)

## 六、模拟器

### 6.1 打开设备管理器

![image-20250520200638489](https://i-blog.csdnimg.cn/img_convert/bb97a5f84d4f6a71e3f904859f3eb091.png)

### 6.2 接收条例

![image-20250520200702704](https://i-blog.csdnimg.cn/img_convert/29e7b14eb656a14a13f94d1323b5d10d.png)

### 6.3 下载镜像

建议勾选不再提示，选择是

![image-20250520200739887](https://i-blog.csdnimg.cn/img_convert/0836a3a9203c1e22a598b1d5e433bd31.png)

![image-20250520201009534](https://i-blog.csdnimg.cn/img_convert/745cb89ee9f64fdd2de3fd4eed5187bd.png)

等待运行完成

![image-20250520201052996](https://i-blog.csdnimg.cn/img_convert/7bcec05c60898bae0de719f42d204b53.png)

点击完成

![image-20250520202950853](https://i-blog.csdnimg.cn/img_convert/1dc20922469cddb357aedf5001e0b047.png)

### 6.4 安装一个虚拟设备

选择刚下载的虚拟机，点击下一步

![image-20250520203101677](https://i-blog.csdnimg.cn/img_convert/0b6c4b761da2b82193738230e3617442.png)

设备名称可以选择默认，也可以自定义，

内存：可以理解为运行内存，必须大于2GB，如不是游戏开发，建议按默认4GB即可，具体按实际需求设置

存储空间：虚拟设备内存，必须大于2GB，按需配置

![image-20250520203208432](https://i-blog.csdnimg.cn/img_convert/b9c296eec33cca3d48aaaf3db6f2147f.png)

点击完成后，可以点击▶运行虚拟设备

![image-20250520203511410](https://i-blog.csdnimg.cn/img_convert/fc0a264a90f93ed81001afb10f5e8f56.png)
![image-20250520203944719](https://i-blog.csdnimg.cn/img_convert/8de4d2b812ff5b10b39d65c7e24f2c08.png)
