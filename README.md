<!--
    需要填充的占位符：
    
    README.md
    
        {name}：文档中文名
        {nameEn}：文档英文名
        {urlEn}：文档原始链接
        {domain}：域名前缀
        {adminName}：负责人名称
        {adminUn}：负责人 Github 用户名
        {adminQq}：负责人 QQ
        {repo}：ApacheCN 的 Github 仓库名称
        {dockerName}：DockerHub 仓库名称
        {pypiName}：PYPI 包名称
        {npmName}：NPM 包名称
    
    CNAME
    
        {domain}：域名前缀

    index.html
    
        {name}：文档中文名
        {color}：显示颜色
        {repo}：ApacheCN 的 Github 仓库名称

    asset/docsify-apachecn-footer.js
    
        {repo}：ApacheCN 的 Github 仓库名称
-->

# {name}

> 原文：[{nameEn}]({urlEn})
> 
> 协议：[CC BY-NC-SA 4.0](http://creativecommons.org/licenses/by-nc-sa/4.0/)
> 
> 收割 SB 的人会被 SB 们封神，试图唤醒 SB 的人是 SB 眼中的 SB。——SB 第三定律

* [在线阅读](https://{domain}.apachecn.org)
* [在线阅读（Gitee）](https://apachecn.gitee.io/doc-template/)
* [ApacheCN 学习资源](http://docs.apachecn.org/)

## 贡献指南

本项目需要校对，欢迎大家提交 Pull Request。

> 请您勇敢地去翻译和改进翻译。虽然我们追求卓越，但我们并不要求您做到十全十美，因此请不要担心因为翻译上犯错——在大部分情况下，我们的服务器已经记录所有的翻译，因此您不必担心会因为您的失误遭到无法挽回的破坏。（改编自维基百科）

## 联系方式

### 负责人

* [{adminName}](https://github.com/{adminUn}): {adminQq}

### 其他

*   在我们的 [apachecn/{repo}](https://github.com/apachecn/{repo}) github 上提 issue.
*   发邮件到 Email: `apachecn@163.com`.
*   在我们的 [组织学习交流群](https://www.apachecn.org/#/docs/join) 中联系群主/管理员即可.

## 下载

### Docker

```
docker pull apachecn0/{dockerName}
docker run -tid -p <port>:80 apachecn0/{dockerName}
# 访问 http://localhost:{port} 查看文档
```

### PYPI

```
pip install {pypiName}
{pypiName} <port>
# 访问 http://localhost:{port} 查看文档
```

### NPM

```
npm install -g {npmName}
{npmName} <port>
# 访问 http://localhost:{port} 查看文档
```

## 其它协议

霞鹜文楷采用 [SIL 开放字体协议 1.1](https://github.com/lxgw/LxgwWenKai/blob/main/SIL_Open_Font_License_1.1.txt)。

## 赞助我们

![](http://data.apachecn.org/img/about/donate.jpg)
