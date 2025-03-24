---
title: Example Talk # 事件标题

event: Hugo Blox Builder Conference # 事件名称
event_url: https://example.org # 事件链接

location: Hugo Blox Builder HQ # 事件地点
address: # 详细地址
  street: 450 Serra Mall # 街道
  city: Stanford # 城市
  region: CA # 地区
  postcode: '94305' # 邮编
  country: United States # 国家

summary: An example talk using Hugo Blox Builder's Markdown slides feature. # 事件简介
abstract: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellusac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum. Sed ac faucibus dolor, scelerisque sollicitudin nisi. Cras purus urna, suscipit quis sapien eu, pulvinar tempor diam.' # 事件摘要

# Talk start and end times（演讲开始和结束时间）
#   End time can optionally be hidden by prefixing the line with `#`（结束时间可以隐藏）
date: '2030-06-01T13:00:00Z' # 开始时间
date_end: '2030-06-01T15:00:00Z' # 结束时间
all_day: false # 是否全天事件

# Schedule page publish date (NOT talk date)（页面发布时间，不是事件日期）
publishDate: '2017-01-01T00:00:00Z' # 发布日期

authors: # 作者列表
  - admin # 指向 content/authors/admin/

tags: [] # 标签（目前为空）

# Is this a featured talk? (true/false)（是否重点事件）
featured: false # 不突出显示

image: # 事件图片
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)' # 图片说明
  focal_point: Right # 图片焦点（Right, Left, Center）

#links: # 社交链接（已注释）
#  - icon: twitter
#    icon_pack: fab
#    name: Follow
#    url: https://twitter.com/georgecushen
url_code: 'https://github.com' # 代码链接
url_pdf: '' # PDF 链接
url_slides: 'https://slideshare.net' # 幻灯片链接
url_video: 'https://youtube.com' # 视频链接

# Markdown Slides (optional)（Markdown 幻灯片，可选）
#   Associate this talk with Markdown slides（关联幻灯片文件）
#   Simply enter your slide deck's filename without extension（输入幻灯片文件名，不带扩展名）
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`
#   Otherwise, set `slides = ""`
slides: "" # 没有关联幻灯片

# Projects (optional)（关联项目，可选）
#   Associate this post with one or more of your projects（关联你的项目）
#   Simply enter your project's folder or file name without extension（输入项目文件名，不带扩展名）
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`
#   Otherwise, set `projects = []`
projects: # 关联项目
  - example # 指向 content/project/example/
---

{{% callout note %}}
Click on the **Slides** button above to view the built-in slides feature.
{{% /callout %}}

Slides can be added in a few ways:

- **Create** slides using Hugo Blox Builder's [_Slides_](https://docs.hugoblox.com/reference/content-types/) feature and link using `slides` parameter in the front matter of the talk file
- **Upload** an existing slide deck to `static/` and link using `url_slides` parameter in the front matter of the talk file
- **Embed** your slides (e.g. Google Slides) or presentation video on this page using [shortcodes](https://docs.hugoblox.com/reference/markdown/).

Further event details, including [page elements](https://docs.hugoblox.com/reference/markdown/) such as image galleries, can be added to the body of this page.