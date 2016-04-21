---
layout: post
title:  "Focus on composing"
color:  red
width:   3
height:  1
date:   3016-04-18 20:03:00 +0800
categories: jekyll update
---

### Template for English Blog

You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run `jekyll serve`, which launches a web server and auto-regenerates your site when a file is updated.

To add new posts, simply add a file in the `_posts` directory that follows the convention `YYYY-MM-DD-name-of-post.ext` and includes the necessary front matter. Take a look at the source for this post to get an idea about how it works.

Jekyll also offers powerful support for code snippets:

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: http://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/

---

### 中文代码模版
Jekyll 贴心地提供了一个本地预览服务器，用于离线编辑时预览网站效果。至此，你也可以启动服务器进行个人网站的预览啦。

**启动 Jekyll 预览服务器**

    $ bundle exec jekyll serve
    Configuration file: /Users/octocat/my-site/\_config.yml
                Source: /Users/octocat/my-site
           Destination: /Users/octocat/my-site/\_site
     Incremental build: disabled. Enable with --incremental
        Generating...
                    done in 0.309 seconds.
     Auto-regeneration: enabled for '/Users/octocat/my-site'
    Configuration file: /Users/octocat/my-site/\_config.yml
        Server address: http://0.0.0.1:4000/
      Server running... press ctrl-c to stop.

通过本地浏览器打开 *Server address: http://0.0.0.1:4000/* 生成的链接，你的个人网页就展现在你面前了。当然，网页信息都还是模版自带，以后的工作就变成了修改本地文件并使用 GitHub 进行代码托管了。

**向 GitHub 完成网络更新**
如果预览效果已经满意了，那么就向 GitHub 代码库进行推送更新吧。

{% highlight bash %}
git add .
git commit -m "First pages commit"
git push origin gh-pages
{% endhighlight %}

推送更新完成后，登录你的个人网站 *https://<username>.github.io/<repository>* 看看效果吧！似乎中文看上去比英文还要舒适哟……
