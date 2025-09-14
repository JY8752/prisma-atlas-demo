# Docker 環境における Prisma + Atlas の環境構築

```bash
pnpm add -D typescript tsx @types/node prisma
```

以下の実行も求められた

```bash
pnpm approved-builds 
```

pnpm v10からの変更点っぽい

[参考](https://zenn.dev/uttk/scraps/af1a3589784268)

```bash
pnpm tsc --init
```

```bash
pnpm prisma init --datasource-provider postgresql --output ../generated/prisma
```

pgドライバのインストールとclientのインストール

```bash
pnpm add @prisma/adapter-pg @prisma/client
```
