# GDG Suzhou Website Source

本网站基于 hexo 构建静态网站。任何人都可以 clone 后在本地重建网站，可以贡献文章、内容。 非常欢迎一起来共同构建GDG Suzhou 社区网站。

## hexo 使用须知

[hexo 中文官网](https://hexo.io/zh-cn/)

```
# install hexo
$ npm install hexo-cli -g

# fork && clone code
$ git clone
$ cd

# start
$ hexo serve
```

打开 http://localhost:4000 即可预览到网站啦
在 *source/_posts* 下修改已有文章，或者

```
# 新建文章，替换 <title> 为你的文章标题
$ hexo new post <title>
```

在 *source/_posts* 下 就会生成新文章，修改即可，完成后提交 PR 即可。


## Note

- [git 忽略某些行](https://stackoverflow.com/questions/16244969/how-to-tell-git-to-ignore-individual-lines-i-e-gitignore-for-specific-lines-of)

```
$ git config filter.gitignore.clean "sed '/# gitignore$/'d"
```
