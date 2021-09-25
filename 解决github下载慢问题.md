# 解决Github克隆下载代码慢的问题（超级简单 不用修改Hosts）



最近我在学习吴恩达的机器学习课程，我需要将一些资料从Github中下载下来，如下图

![下载文件](https://cdn.jsdelivr.net/gh/JLUVicent/image-saving@master/20210731/下载文件.2zlalr0ipfk0.jpg)

但是如果直接在Github上克隆下载代码往往速度特别慢，200M的东西速度却是*24kb/s*，心态炸了。

![使用gitee前的速度](https://cdn.jsdelivr.net/gh/JLUVicent/image-saving@master/20210731/使用gitee前的速度.3kepcibov940.jpg)

***

**这时我们有请~~马云~~（码云），也就是[(gitee)](https://gitee.com/)<https://gitee.com/>。**

在开始下载别人的项目之前我们**需要将别人的仓库fork到我们仓库下面**，操作步骤很简单，只要在**别人的项目下点击Fork**后，别人的项目就到你的仓库下面了。

![Fork](https://cdn.jsdelivr.net/gh/JLUVicent/image-saving@master/20210731/Fork.5tlsz9kq4oo0.jpg)

***

## 下面介绍具体步骤：

### **1.注册码云账号，官网（[码云](https://gitee.com/)<https://gitee.com/>）**

### **2.点击从Github/Gitlab中导入仓库，如下图**

![码云第二步](https://cdn.jsdelivr.net/gh/JLUVicent/image-saving@master/20210731/码云第二步.4ehewwyi4eg0.jpg)

点击之后会出现如下界面，一共有三种方式可以导入github，我这里以我认为较为方便的第二种方法（**导入Github仓库**）为例，其他也可以。

![导入仓库三种界面](https://cdn.jsdelivr.net/gh/JLUVicent/image-saving@master/20210731/导入仓库三种界面.6fvp1t2yixc0.jpg)

点击导入Github仓库之后，会出现登录界面，输入自己的Github账号和密码（*这一步有时候可能很慢，这是因为Github的缘故，多试几次就好了*），如下图所示

![登录github](https://cdn.jsdelivr.net/gh/JLUVicent/image-saving@master/20210731/登录github.u5ab0r4a99c.jpg)

### **3.登录成功后如下图所示，选择你想要导入的仓库点击导入，比如我想导入如下图第三个仓库**

![需要哪个就导入哪个](https://cdn.jsdelivr.net/gh/JLUVicent/image-saving@master/20210731/需要哪个就导入哪个.4eoi4se53va0.jpg)

导入成功后点击查看仓库，如下图：

![导入成功后](https://cdn.jsdelivr.net/gh/JLUVicent/image-saving@master/20210731/导入成功后.vbmj1hdor00.jpg)

### **4.仓库下出现我们所需要的项目，点击克隆下载**

![克隆下载](https://cdn.jsdelivr.net/gh/JLUVicent/image-saving@master/20210731/克隆下载.2mu96yogtsc0.jpg)

看看下载速度9M/s，嘹咋咧！

![使用gitee后的速度](https://cdn.jsdelivr.net/gh/JLUVicent/image-saving@master/20210731/使用gitee后的速度.4piipf6pe5y0.jpg)