<!--
 * @Author: Conghao Wong
 * @Date: 2023-03-21 18:12:30
 * @LastEditors: Conghao Wong
 * @LastEditTime: 2023-05-06 12:40:53
 * @Description: file content
 * @Github: https://cocoon2wong.github.io
 * Copyright 2023 Conghao Wong, All Rights Reserved.
-->

# HUST-BIAC.github.io

## 开始

进行所有操作之前，向@cocoon2wong 和@SYe-hub 所要仓库修改权限。
之后，安装git（详情可自行查找），并将此仓库pull到本地：

```bash
git clone https://github.com/HUST-BIAC/hust-biac.github.io.git
```

## 非新闻的新页面添加/修改步骤

### 页面的书写

通过`markdown`书写所有的页面源文件。
但是要在所有markdown中添加下面的文件头部。
注意⚠️：这部分内容仅适用于**非新闻页面**。

```none
---
layout: pageWithLeftNav
pageType: 3
title: 科学研究
subtitle: 科研项目
cover-img: /assets/img/title.jpg
---
```

其中，`pageType`为页面所属的栏目index，对应关系为：

- 首页: 0
- 中心概况: 1
- 研究队伍: 2
- 科学研究: 3
- 研究成果: 4
- 代表性工程化成果: 5
- 服务与合作: 6
- 产业化基地: 7

除此之外，其他信息一般不需要更改。

所有用到的图片请放在`/assets/img/`下对应栏目的目录中，以方便管理。
建议通过下面的形式在`markdown`中插入图片：

```html
<div style="text-align: center;">
    <img style="width: 60%;" src="/assets/img/researchs/5/1.png">
</div>
```

并通过`width`来调整图片的宽度。

### 将页面上传到仓库

在上传到系统之前，请将所有修改的文件/新文件先push到此仓库（请勿使用`force push`）。
以`Visual Studio Code`为例，这些步骤包括：

#### 在本地仓库暂存更改
  
<div style="text-align: center;">
    <img style="width: 60%;" src="/readmeimgs/1.png">
</div>

仔细确认更改的文件，确认无误后点击`+`将文件状态改为`暂存的更改`。

#### 在本地仓库提交更改

<div style="text-align: center;">
    <img style="width: 60%;" src="/readmeimgs/2.png">
</div>

在`comment（消息）`栏中说明本次提交主要更改的内容，请认真书写，方便后续操作。
确认无误后，单击`提交`，将所有更改提交到本地仓库。

如提交到本地仓库后仍想撤回修改，可通过下面撤回：

<div style="text-align: center;">
    <img style="width: 60%;" src="/readmeimgs/3.png">
</div>

但是，一旦本地仓库提交到Github后，将不能撤回，也不要`force push`，保持原状即可。

#### 将本地仓库的更改提交到GitHub

**确认无误之后**，源代码管理页面的按钮将变为`同步更改`：

<div style="text-align: center;">
    <img style="width: 60%;" src="/readmeimgs/4.png">
</div>

在正常的提交过程中，只会显示向上的箭头，如有向下的箭头出现，请仔细进行下面的操作：

```bash
git pull
```

在此过程中，可能会产生冲突，对冲突的文件进行修改，并重新在本地提交。

**确认无误之后**，单击`同步更改`，将本地的更改提交到Github。

#### 等待生成hust-biac.github.io网站

上传结束后并等待`github actions`运行完毕（一般需要大约五分钟），修改/新建的页面将会出现在 hust-biac.github.io 。
之后，可通过多种方式，如Chrome浏览器中按下`F12`，或Safari中在`开发`菜单中选择`显示页面源文件`，来把生成的`html`文件下载下来。
**请注意要把修改涉及到的所有html文件都下载下来**，比如有时候改了一页，其他页的链接变化时，要把所有变化的html页面下载下来。

#### 上传到系统

按照层级关系，将所有对应的`html`文件上传到系统上即可，上传过程请小心确认，如不知道上传路径，可参考对应页面在 hust-biac.github.io 中的地址，如`https://hust-biac.github.io/contributions/prize/`对应的文件（`index.html`）应该上传到`/contributions/prize/index.html` 。

#### 检查

上传完成后，请检查所有的图片、链接，确保上传无误。

## 新闻页面的书写

新闻的书写和常规页面有所区别。
当要发布新的新闻时，应当在仓库中`/_posts`目录下新建文件`YYYY-MM-DD-XXX.md`。
其中，`YYYY-MM-DD`为新闻上显示的发布日期，`XXX`为文件名，可随意取名。

新闻`markdown`文件的头和其他文件不同，应当为：

```none
---
layout: post
tags: [news]
title: 我中心两位学者入选2022“中国高被引学者”榜单
# thumbnail-img: /assets/img/news/2023-02-25-0.jpg
cover-img: /assets/img/title.jpg
---
```

其中，`thumbnail-img`为新闻的略缩图，可有可无，可根据需求添加或删除注释符号`#`。

此外，新闻文件的第一段默认为摘要，会显示在新闻列表中，在写作时需要注意。

其他的上传步骤和非新闻页面相同。
更新新闻时，需要更新下面的几个页面：

- 新增的新闻html，如`/2023-04-10-news/index.html`；
- 网站首页，即`/index.html`；
- 新闻首页，即`/news/index.html`。

## 结束

请在上传所有材料时小心谨慎，尤其不要`force push`。
Good Luck！
