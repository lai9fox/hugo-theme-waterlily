# Theme Name

## Features

## Installation

## Configuration

### 导航菜单配置

对导航链接进行配置，目前支持 3 个导航链接:

```toml
[menus]
  [[menus.main]]
    # 分类
    identifier = "categories"
    name = "Categories"
    url = "/categories/"
    weight = 10
  [[menu.main]]
    # 标签
    identifier = "tags"
    name = "Tags"
    url = "/tags/"
    weight = 30
  [[menu.main]]
    # 归档
    identifier = "archives"
    name = "Archives"
    url = "/archives/"
    weight = 30
```

## 主题开发调试
```shell
hugo server -s devSite -t ../..
pnpm tailwindBuild:watch
```
