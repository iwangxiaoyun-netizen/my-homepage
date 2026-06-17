# 自闭症家庭训练计划个人主页

这是一个可直接部署到 Cloudflare Pages 的静态个人主页。

## 目录结构

```text
my-homepage/
  public/
    index.html
    assets/
      avatar.jpg
```

## Cloudflare Pages 设置

连接 GitHub 仓库后，建议使用以下设置：

```text
Framework preset: None
Build command: 留空
Build output directory: public
Root directory: /
```

## 本地预览

可以直接打开：

```text
public/index.html
```

也可以使用任意静态服务器预览 `public` 目录。
