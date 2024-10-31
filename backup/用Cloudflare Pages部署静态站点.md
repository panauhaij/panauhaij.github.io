最近搞了一些有意思的小项目，想着部署到网上方便访问，但是又不好放到自己的个人网站上，这时候就可以用Cloudflare Pages来进行部署。

## **Cloudflare Pages**

Cloudflare Pages 是一个专为构建和部署静态网站而设计的平台。它与 GitHub 集成，可以直接从代码库拉取项目。借助 Cloudflare 的全球 ~~（环大陆）~~ CDN 网络，能够实现快速的全球内容加载。不仅如此，Cloudflare Pages 还支持自定义域名和自动 SSL 证书，方便我们快速和安全地访问。

简单讲就是我们可以利用CF Pages来快速部署自己的静态站点（比如个人的静态主页）和项目，省去了自费购买服务器等操作。 ~~（主打一个免费白嫖）~~

## **准备**

- 需要部署的项目文件
- 域名（可选）
- Cloudflare账号

# **部署项目**
## **登录官网**

首先登录[Cloudflare官网](https://www.cloudflare-cn.com/enterprise/)，没有账号的可以自行注册一个，应该不用教学了吧。

## **创建Pages项目**

注册登录之后会自动跳转到后台，点击左边列表的 **Workers和Pages**，点击 **创建**。

![cf-pages](https://cdn.auhaijpan.top/wp-content/uploads/2024/10/cf-pages.png)

## **上传方式**

然后切换到**Pages**页面，其提供了两种上传方式，分别是通过**Git 存储库直接导入**和**本地上传**，这里我们选择**本地上传**。

![两种部署方式](https://cdn.auhaijpan.top/wp-content/uploads/2024/10/两种部署方式.png)

## **项目名称**

选择本地上传之后，先给项目**创建一个名称**，我这里填了**demo**。

![项目名称](https://cdn.auhaijpan.top/wp-content/uploads/2024/10/项目名称.png)

## **上传文件**

然后**上传文件**。（注意每个文件的最大限制是25MB）

![上传站点文件](https://cdn.auhaijpan.top/wp-content/uploads/2024/10/上传站点文件.png)

## **部署项目**

等待上传完毕之后就点击**部署站点**，然后你的站点就成功上线了，可以通过其**分发的链接**前往自己的站点查看。

![成功部署](https://cdn.auhaijpan.top/wp-content/uploads/2024/10/成功部署.png)


## **成功部署**

笔者部署的官方演示站点：[Direct Upload Demo | Cloudflare Pages](https://demo-97x.pages.dev/)

![demo-page](https://cdn.auhaijpan.top/wp-content/uploads/2024/10/demo-page.png)

## **自定义域**

如果你有自己的域名的话，还可以自行设置**自定义域**，通过自己的域名来访问部署好的站点。
笔者的自定义域名访问：[Direct Upload Demo | Cloudflare Pages](https://demo.77889925.xyz/)

![自定义域](https://cdn.auhaijpan.top/wp-content/uploads/2024/10/自定义域.png)


<br>
<br>

#### 相关文档：

- [Cloudflare Pages documentation](https://developers.cloudflare.com/pages/)
- [全球云平台 | Cloudflare 中国官网 | Cloudflare](https://www.cloudflare-cn.com/enterprise/)