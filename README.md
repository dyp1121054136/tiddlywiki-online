#### 功能:

部署在线tiddlywiki中文空白版

#### 步骤：

1、复制此模板并新建仓库

https://github.com/dyp1121054136/tw-online-template

点击："Use this template"-"Create a new repository"，填写仓库名 Repository name-点击"Create repository"

2、修改仓库权限

"Settings"-"Actions"-"General"-"Workflow permissions"，勾选"Read and write permissions"，工作流在所有范围的存储库中均具有读写权限。

3、手动部署

"Actions"-"部署tiddlywiki"-"Run workflow"-"Branch: master"-"Run workflow"

4、GitHub Pages指向gh-pages分支

"Settings"-"Pages"，选"Deploy from a branch"，"gh-pages"-"/ (root)"-"Save"

5、点开右上角"About"，设置勾选"Use your GitHub Pages website"，确定显示网址

#### 其他：

修改图片uri指向路径前缀

tiddlers/external/tiddlywiki.files

"_canonical_uri": {"source": "filepath", "prefix": "https://raw.githubusercontent.com/dyp1121054136/tw-online-template/refs/heads/master/files/images/"}
