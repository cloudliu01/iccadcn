# 说明

本项目是基于`hexo`的快速生成静态博客页面的工具。
# 环境配置

1、必须安装 Node.js

2、安装 `Hexo`:

`npm i hexo-cli -g`

# 写文章

命令行输入：`hexo new post "article title"`

即可在`\source\_posts`目录下生成一篇文章

或者手动新建一个`md`文件

# 常用命令

```shell
hexo s  # 本地预览博客
hexo g  # 生成博客网页文件
hexo d  # 部署到github
```

也可以在完成文章编辑后，执行根目录中的脚本：`run.sh`,

该脚本的功能：

- 自动生成静态文件
- 上传到gitpage所在的git仓库（⚠️该仓库与本项目不是同一个）
  - 目标仓库地址在根目录的 `_config.yml` 文件的 `deploy`字段进行配置。

# 配置信息

根目录的 `_config.yml` 文件是本项目的全局配置信息。
theme 主题目录下的`_config.yml` 是对应主题的配置信息。
