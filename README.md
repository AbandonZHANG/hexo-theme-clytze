# hexo-theme-clytze
A clean and beautiful hexo theme inspired by hexo-theme-apollo. [Demo](http://blog.abandonzhang.me)

## Node Modules

#### hexo-renderer-sass (必需)
生成静态文件时渲染sass/scss文件用，本主题必需。

#### hexo-renderer-jade (必需)
jade模板引擎，渲染jade文件用，本主题必需。

#### hexo-server (推荐)
可以使用hexo server命令在localhost实时查看最新修改

#### hexo-math (推荐)
可以使用MathJax或者katex来生成数学公式，不需要手动引入mathjax的js和css文件

如何配置在作者[Github](https://github.com/akfish/hexo-math)中可以看到

## Install

```
// your blog root dir
cd Blog

// install hexo module
npm install hexo-renderer-sass hexo-renderer-jade --save

git clone https://github.com/AbandonZHANG/hexo-theme-clytze.git themes/clytze
```
