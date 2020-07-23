# Next App for SEO

本示例结合 `next`、`ga`、`helmet` 及 `typescript` 快速开发并部署到多个平台

## 快速使用

使用本模板快速创建应用

``` bash
$ git clone git@github.com:shfshanyue/next-app.git
```

在项目创建早期尽可能对 package 进行升级，这里使用了 `npm-check-updates`

``` bash
$ npm run ncu
```

在测试环境中进行开发

``` bash
$ npm run dev
```

### 文件结构

``` bash
.
├── node_modules/
├── pages/                  # 所有的 pages
├── utils/
├── package.json
├── package-lock.json
├── README.md
└── serverless.yaml
```

## Deoploy

### Tencent Serverless Framework

``` bash
$ npm run build

$ sls --debug
```

### Vercel

``` bash
```

### Docker 

``` bash
```

### Traefik

``` bash
```