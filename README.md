# 准备工作

1.安装Node

2.安装Git

3.选择编辑器(个人采用Atom)

4.配置GitHub中的SSH ：http://www.cnblogs.com/xiahl/p/5289139.html

5.安装Hexo : https://hexo.io/

# 博客主题

1.自己开发 ：https://github.com/Xiahl1990/hexo-theme-tianxiamucun

2.选择他人 ：

# 发布预览

```
// 删除db
hexo clean

// 删除发布数据
rm -rf .deploy_git

// 生成静态文件
hexo g

// 发布
git config remote.origin.url git@github.com:Xiahl1990/blog.git
hexo d

// 预览
hexo s -p 8082
```
