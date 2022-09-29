# MAA 设计资产

## 使用

### 于文档内引用

```markdown
![MAA Logo](https://cdn.jsdelivr.net/gh/MaaAssistantArknights/design@main/logo/maa-logo_256x256.png)
```

### 在 Web 项目内将 Logo 作为图标引用

若欲在 Web 项目内将 Logo 作为图标引用，可直接将 `logo/web` 下的文件放于 `public` 或等义目录下后，于 HTML 内嵌入 favicon 引用：

```html
    <link rel="apple-touch-icon" sizes="180x180" href="/apple-touch-icon.png?v=1" />
    <link rel="icon" type="image/png" sizes="32x32" href="/favicon-32x32.png?v=1" />
    <link rel="icon" type="image/png" sizes="16x16" href="/favicon-16x16.png?v=1" />
    <link rel="manifest" href="/site.webmanifest?v=1" />
    <link rel="mask-icon" href="/safari-pinned-tab.svg?v=1" color="#101010" />
    <link rel="shortcut icon" href="/favicon.ico?v=1" />
    <meta name="msapplication-TileColor" content="#101010" />
    <meta name="theme-color" content="#101010" />
```

### 在 C# 或其他项目内将 Logo 作为图标引用

若欲在 C# 或其他项目内将 Logo 作为图标引用，请使用 `logo/web/maa-logo_original.png` 作为图标文件基准后，将其转换为各平台所需的图标格式。
