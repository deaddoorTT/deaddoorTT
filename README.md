# Site settings
title: BY Blog
SEOTitle: 谈正的博客 | BY Terry
header-img: img/post-bg-desk.jpg
email: 3647264288@qq.com
description: "Every failure is leading towards success."
keyword: "BY, BY Terry, 谈正的博客, tanzheng, 谈正, iOS, Apple, iPhone"
url: "https://deaddoorTT.github.com/"          # your host, for absolute URL
baseurl: ""      # for example, '/blog' if your blog hosted on 'host/blog'
github_repo: "https://github.com/qiubaiying/qiubaiying.github.io.git" # you code repository

# Sidebar settings
sidebar: true                           # whether or not using Sidebar.
sidebar-about-description: "Goals determine what you going to be!"
sidebar-avatar: /img/about-BY-gentle.jpg      # use absolute URL, seeing it's used in both `/` and `/about/`



# SNS settings
RSS: false
# weibo_username:    no
zhihu_username:     no
github_username:    deaddoorTT
facebook_username:  no
jianshu_username:  no
#twitter_username:   no




# Build settings
# from 2016, 'pygments' is unsupported on GitHub Pages. Use 'rouge' for highlighting instead.
permalink: pretty
paginate: 10
exclude: ["less","node_modules","Gruntfile.js","package.json","README.md"]
anchorjs: true                          # if you want to customize anchor. check out line:181 of `post.html`



# Gems
# from PR#40, to support local preview for Jekyll 3.0
gems: [jekyll-paginate]




# Markdown settings
# replace redcarpet to kramdown,
# although redcarpet can auto highlight code, the lack of header-id make the catalog impossible, so I switch to kramdown
# document: http://jekyllrb.com/docs/configuration/#kramdown
markdown: kramdown
highlighter: rouge
kramdown:
  input: GFM                            # use Github Flavored Markdown !important



# 评论系统
# Disqus（https://disqus.com/）
# disqus_username: qiubaiying

# Gitalk
gitalk:
  enable: true    #是否开启Gitalk评论
  clientID: f2c84e7629bb1446c1a4                            #生成的clientID
  clientSecret: ca6d6139d1e1b8c43f8b2e19492ddcac8b322d0d    #生成的clientSecret
  repo: qiubaiying.github.io    #仓库名称
  owner: qiubaiying    #github用户名
  admin: qiubaiying
  distractionFreeMode: true #是否启用类似FB的阴影遮罩


# 统计

# Analytics settings
# Baidu Analytics
ba_track_id: b50bf2b12b5338a1845e33832976fd68

# Google Analytics
ga_track_id: 'UA-90855596-1'            # Format: UA-xxxxxx-xx
ga_domain: qiubaiying.top               # 默认的是 auto, 这里我是自定义了的域名，你如果没有自己的域名，需要改成auto





# Featured Tags
featured-tags: true                     # 是否使用首页标签
featured-condition-size: 1              # 相同标签数量大于这个数，才会出现在首页



# Progressive Web Apps
chrome-tab-theme-color: "#000000"
service-worker: true



# Friends
friends: [
    {
        title: "WY",
        href: "http://zhengwuyang.com"
    },{
        title: "简书·BY",
        href: "http://www.jianshu.com/u/e71990ada2fd"
    },{
        title: "Apple",
        href: "https://apple.com"
    },{
        title: "Apple Developer",
        href: "https://developer.apple.com/"
    }
]
