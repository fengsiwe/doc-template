# 更新文档注意事项：

直接在仓库找到 web IDE，点击按钮直接就可以进行编辑

![pic](./IMG/pic1.png?inline=false)


# 可修改的文档

## docs文件夹

文档的具体内容写在docs文件夹内，根据自己的需求填写markdown文件。
每个markdown文件是一个单独的页面， 也可以用文件夹来归类多个markdown文件。
![pic](./IMG/pic2.png?inline=false)


在文档页面中导航的具体内容就是由我们自己定义的文件夹决定的。文档页面的展示如下

![pic](./IMG/pic3.png?inline=false)

## 文档排序

关于文档排序， 我们可以直接在文件夹或者markdown文件名前加上序号。文档会按照数字顺序展示。

![pic](./IMG/pic4.png?inline=false)


如果是在一个文件夹里面的markdown文件排序可以在markdown文件的开头更改 sidebar_position。

![pic](./IMG/pic5.png?inline=false)


## 顶部导航

如果想要增加或更改顶部导航，可以到docusaurus.config.js 文件中进行更改

![pic](./IMG/pic6.png?inline=false)

我们可以直接在items这个配置项中添加删除。

![pic](./IMG/pic7.png?inline=false)

在文档上的展示如下：

![pic](./IMG/pic8.png?inline=false)

## siderBar 配置

如果你需要手动添加sidebar或者需要更改siderbar内容，可以到siderbars.js进行更改。Docusaurus 会根据你的目录结构自动生成，如果没有特别需要可以不做修改。下图所示：侧面导航栏的标题是由文件夹名称或者markdown文件自动生成的。

![pic](./IMG/pic9.png?inline=false)

## 首页按钮配置

![pic](./IMG/pic11.png?inline=false)

如果需要修改跳转的页面可以在src/pages/index.js文件中进行修


![pic](./IMG/pic12.png?inline=false)
![pic](./IMG/pic13.png?inline=false)

## graph 插件mermaid
 
在docusaurus的原生md中暂时不支持graph的展示功能，我们需要一个插件去实现展示， 语法如下：

![pic](./IMG/pic14.png?inline=false)






