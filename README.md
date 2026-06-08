# 洪明均書道サロン — Webサイト

書道教室「洪明均書道サロン」のワンページWebサイトです。  
Claude Code + [claude1page](https://github.com/toiee-lab/claude1page) スターターキットを使って構築しています。

## サイト概要

- **サイト名**: 洪明均書道サロン
- **キャッチコピー**: 子どもから大人まで楽しく学べる書道教室
- **特徴**: 完全マンツーマン指導、初心者から経験者まで対応
- **コース**: 古典臨書・創作書道・実用書道・ハングル書道

## ファイル構成

```
hallo01/
├── public/              # 公開ディレクトリ（Cloudflare Pages）
│   └── index.html      # メインページ（ワンページ完結）
├── project-docs/       # コンテンツ・ドキュメント
├── .claude/            # Claude Code 設定・スキル
├── CLAUDE.md           # Claude Code 用指示書
└── README.md           # このファイル
```

## 技術スタック

- **HTML/CSS/JS**: バニラ（ビルドプロセスなし）
- **CSS フレームワーク**: Tailwind CSS v4 (CDN)
- **アニメーション**: Animate.css v4.1.1 + AOS v2.3
- **アイコン**: Lucide v0.536.0
- **フォント**: Noto Serif JP / Noto Sans JP（Google Fonts）
- **ホスティング**: Cloudflare Pages

## ローカルでの確認方法

VS Code の Live Server 拡張機能を使って `public/index.html` をブラウザで開くだけで確認できます。ビルド不要です。

## Cloudflare Pages での公開

1. Cloudflare にログイン
2. Workers & Pages > アプリケーションを作成 > Pages
3. GitHub リポジトリをインポート
4. 公開ディレクトリに `public` を設定
5. Deploy

## コンテンツの更新

Claude Code に以下のように依頼するだけで編集できます。

```
〇〇のセクションの△△を□□に変更してください。
```

---

*本サイトは Claude Code を使って構築・管理しています。*
