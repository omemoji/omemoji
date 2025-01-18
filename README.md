# omemoji

<p align=left>
<a href="https://voidlinux.org">
<img alt="Void" src="https://img.shields.io/badge/Void%20Linux-478061.svg?logo=voidlinux&logoColor=ffffff&style=flat"/>
</a>
</a>
<a href="https://python.org">
<img alt="Python" src="https://img.shields.io/badge/Python-3776AB.svg?logo=python&logoColor=ffffff&style=flat"/>
</a>
<a href="https://typescriptlang.org">
<img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6.svg?logo=typescript&logoColor=ffffff&style=flat"/>
</a>
<a href="https://nextjs.org">
<img alt="Next.js" src="https://img.shields.io/badge/Next.js-000000.svg?logo=next.js&logoColor=ffffff&style=flat"/>
</a>
</p>

<div align=left  >
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=omemoji&theme=transparent&layout=compact" alt="Top Languages" style="margin-right:6px;" height="120"><img src="https://github-readme-stats.vercel.app/api?username=omemoji&theme=transparent&show_icons=true" alt="GitHub Stats" height="120">
</div>

## Profile

| key       | val                             |
| --------- | ------------------------------- |
| Name      | **omemoji**                     |
| Region    | 🗼Tokyo, 🇯🇵Japan                |
| Education | student (University of Tsukuba) |
| Interest  | 🌐Web, 🎨Art                    |

絵、デザインやプログラミング（特に Web 関係）に興味があります。
よろしくお願いします。

## Accounts

| Service     | ID                                                  |
| ----------- | --------------------------------------------------- |
| GitHub      | [omemoji](https://github.com/omemoji)               |
| Instagram   | [omemoji](https://instagram.com/omemoji)            |
| Fediverse   | [@omemoji@omemoji.net](https://omemoji.net/omemoji) |
| X (Twitter) | [omemoji_art](https://twitter.com/omemoji_art)      |
| Pixiv       | [omemoji](https://www.pixiv.net/users/65949346)     |
| Zenn        | [omemoji](https://zenn.dev/omemoji)                 |
| Keybase     | [omemoji](https://keybase.io/omemoji)               |

## Projects

### 創作物紹介

https://github.com/omemoji/omemoji.com

- 作品（主に絵）や記事などをまとめたポートフォリオ
- Next.js + Tailwind CSS で実装
  - 以前は Nuxt.js を使用していた
- [next-mdx-remote](https://github.com/hashicorp/next-mdx-remote) で markdown から HTML を生成している
- リンクカード（上のようなカード状のリンク）を実装した
  - [cheerio](https://github.com/cheeriojs/cheerio) でリンク先の metadata を取得している
  - OGP 画像をビルド時に 最適化し、パフォーマンスを向上させる
- 管理画面を実装し，作品のアップロードを簡単に行えるようにした
  - データベースは json として管理し，`json-server`を立ち上げて API を叩けるようにしている
- ハイドレーション用の js（Next.js で SSG を行うと自動的に追加される） を除去し，完全な静的サイトにした

### omemoji.net

https://omemoji.net/omemoji

- Fediverse
- [Akkoma](https://akkoma.social/) instance
- Google Cloud Platform 上に構築
- 個人用
- その内 Bot を生やすかも知れない
