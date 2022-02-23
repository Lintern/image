# 使用GtiHub+PicGo实现免费搭建个人床图

### 需要准备的东西：

- **注册一个GtiHub账号**

  > **用来存储床图免费又不限空间**
  >
  > **只限制单个文件大小在100M以内  50M会警告  可谓非常良心**

- **下载[PicGo](https://molunerfinn.com/PicGo/)**

  > **一个小工具用来实现上传使用自动化**

### 在GtiHub里新建一个仓库并获取令牌

- 注册完成后来到主页右上角点击+号，点击New repository新建一个仓库

![](https://cdn.jsdelivr.net/gh/Lintern/image/picgo/202202211704600.png)

![](https://cdn.jsdelivr.net/gh/Lintern/image/picgo/202202211712113.png)



### 如何获取令牌(tokees)

- 创建好仓库之后来到主页右上角点击设置

  

![](https://cdn.jsdelivr.net/gh/Lintern/image/picgo/202202240002467.png)

- 然后滑到下面找到**Developer settings**

  ![image-20220223233538244](https://cdn.jsdelivr.net/gh/Lintern/image/picgo/202202240002476.png)

- 然后点击**Generate new token**生成一个令牌

![](https://cdn.jsdelivr.net/gh/Lintern/image/picgo/202202240002148.png)

- 设置令牌权限以及期限，点击下面绿色的**Generate token**按钮生成

![](https://cdn.jsdelivr.net/gh/Lintern/image/picgo/202202240002168.png)

- 这串密钥只会显示一次建议保存备用

![](https://cdn.jsdelivr.net/gh/Lintern/image/picgo/202202240001467.png)

## 配置PicGo

> 这里是这个软件的[官网](https://molunerfinn.com/PicGo/)和[使用指南](https://picgo.github.io/PicGo-Doc/zh/guide/)
>
> 选择自己对应系统版本下载安装即可
>
> Github常年龟速这里提供一个[蓝奏云链接](https://wwi.lanzouw.com/i35zc00j1m3g)(2022.2.24注意时间太久了最好去下最新版本)

- 这里以Windows为例，其他大同小异，主要讲一下配置，**一下这三项必填**

![image-20220224001927589](https://cdn.jsdelivr.net/gh/Lintern/image/picgo/202202240037468.png)

### 指定存储路径

- **你如果不想你的仓库太乱，可以指定它放到某个文件夹内**
- **但是一定不要忘了在末尾加上"/"号才会生成在文件夹内，否则就会变成文件名的前缀**
- **当然也可以用这种方法自定义图片前缀**
  ![image-20220224003942264](https://cdn.jsdelivr.net/gh/Lintern/image/picgo/202202240116367.png)



### 设定自定义域名

> Github国内访问有点慢，会导致图片半天加载不出来
> 这里提供一个加速访问图片的方法：jsDelivr免费CDN加速
> 域名设置为：
> `https://cdn.jsdelivr.net/gh/你的用户名/你的仓库名`



### 然后就是关于一些小知识

- 上传的快捷键设置，可以根据自己喜好来设定，我这里用的是改成 `Ctrl + Alt +Q`。按下快捷键上传剪贴板的图片
- 开启上传自动复制URL后，配合QQ截图或者Snipaste截图，非常好用！！
- 开启时间戳重命名可以防止图片重名无法上传

![image-20220224005830893](https://cdn.jsdelivr.net/gh/Lintern/image/picgo/202202240058622.png)

![image-20220224010358762](https://cdn.jsdelivr.net/gh/Lintern/image/picgo/202202240104082.png)



### 常见错误解读

- 在你检查所有配置都填写正确之后，还是显示上传失败

  那么大概率是证书问题比如其他一些加速器安装的的证书

  比如Steam++ 或者各种加速器，去对应的软件里卸载它的证书

  

- 如果还不行就看看设置里的的日志文件，把他调成只显示错误

  看不懂可以拿去机翻看看，里面有什么错误关键词

