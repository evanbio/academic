---
# To publish author profile pages, remove all the `_build` and `cascade` settings below.
_build:
  render: never # 表示不渲染这个页面
cascade:
  _build:
    render: never # 子页面也不渲染。
    list: always # # 但允许子页面在列表中显示（比如作者列表）
---
