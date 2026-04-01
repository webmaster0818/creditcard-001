# クレジットカード比較サイト

**公開URL:** https://credit-card-comparison.com

マリオットAMEX切り替えユーザーをターゲットにしたクレジットカード比較サイト。

## 📊 プロジェクト概要

- **記事数:** 27記事（176,600+ characters）
- **掲載カード数:** 50枚以上
- **キーワードカバレッジ:** 27/28 KW (96%)
- **公開日:** 2026年4月2日

## 🛠️ 技術スタック

- **フレームワーク:** Astro 6.1.1
- **スタイリング:** Tailwind CSS 4.x
- **ホスティング:** Cloudflare Pages
- **ソース管理:** GitHub
- **フォント:** Noto Sans JP
- **アイコン:** Lucide Icons

## 📁 プロジェクト構成

```
creditcard-001/
├── src/
│   ├── pages/
│   │   ├── index.astro           # トップページ
│   │   ├── articles/
│   │   │   └── [slug].astro      # 記事詳細（動的ルート）
│   │   ├── cards/
│   │   │   └── comparison.astro  # カード比較表
│   │   └── simulator.astro       # 診断ツール
│   ├── layouts/
│   │   ├── BaseLayout.astro      # 基本レイアウト（ヘッダー・フッター）
│   │   └── ArticleLayout.astro   # 記事レイアウト
│   ├── content/
│   │   ├── config.ts             # Content Collection設定
│   │   └── articles/             # 記事（27件のMarkdownファイル）
│   └── styles/
│       └── global.css            # グローバルスタイル
├── public/
│   └── images/                   # 画像ファイル
└── astro.config.mjs              # Astro設定
```

## 🎨 デザイン

### カラースキーム
- **Primary:** ブルー系（#1d4ed8, #1e3a5f）
- **Accent:** レッド系（#ef4444, #dc2626）
- **Success:** グリーン（#16a34a）

### 見出し階層
- **H1:** トップページタイトル（primary-900）
- **H2:** 大見出し（primary-900、左ボーダー、背景色）
- **H3:** 中見出し（primary-800、下線）
- **H4:** 小見出し（primary-700）

### レスポンシブ対応
- モバイルファースト設計
- ブレークポイント: sm (640px), md (768px), lg (1024px)

## 🚀 コマンド

```bash
# 開発サーバー起動
npm run dev

# 本番ビルド
npm run build

# ビルドプレビュー
npm run preview
```

## 📈 SEO最適化

### 構造化データ（JSON-LD）
- BreadcrumbList（パンくずリスト）
- Article（記事情報）
- Organization（サイト運営者）
- WebSite（サイト全体）
- ItemList（ランキング）
- FAQPage（よくある質問）

### その他
- 4階層パンくずリスト
- タグベース関連記事
- 内部リンク最適化
- レスポンシブ画像（lazyload）
- robots.txt, sitemap.xml

## 📝 記事一覧（27記事）

### マリオットAMEX関連（6記事）
- マリオットAMEX切り替えガイド
- マリオットAMEX解約前の確認事項
- マリオットボンヴォイ改悪対策
- セゾンプラチナ vs マリオットAMEX比較
- SPG AMEX後継カード比較
- クレジットカード切り替えタイミング

### ホテル系カード（5記事）
- ホテル系クレジットカード完全比較
- ホテル特典付きクレジットカード
- 無料宿泊特典付きカード
- ヒルトンAMEX完全ガイド
- ヒルトンAMEXプレミアム vs 通常比較

### マイル系カード（5記事）
- マイル高還元率カード
- JALマイル高還元カード
- ANAマイルカード比較
- JAL vs ANAマイル完全ガイド
- 2026年マイル最強カード

### プラチナ・ゴールドカード（4記事）
- プラチナカードおすすめ2026
- ゴールドカード20代向け
- セゾンプラチナビジネス完全ガイド
- AMEXプラチナ審査

### プライオリティパス（3記事）
- プライオリティパス安価カード
- 楽天プレミアムカードPriority Pass
- ラグジュアリーカードホテル特典

### その他（4記事）
- 年会費無料カード2026
- 年会費比較
- AMEXゴールドANAマイル
- セゾンJALマイルサンプル

## 🔄 デプロイ

### Cloudflare Pages
- **本番:** https://credit-card-comparison.com
- **ステージング:** https://creditcard-001.pages.dev
- **自動デプロイ:** GitHub push時に自動ビルド

### GitHub
- **リポジトリ:** https://github.com/webmaster0818/creditcard-001
- **ブランチ:** main

## 📊 アナリティクス（予定）

- Google Search Console: 未設定
- Google Analytics 4: 未設定

## 🎯 今後の展開

### 短期（1-2週間）
- [ ] Google Search Console登録
- [ ] Google Analytics 4設定
- [ ] サイトマップ送信
- [ ] 初期トラフィック測定

### 中期（1-3ヶ月）
- [ ] コンテンツ追加（残り1KW）
- [ ] SEO効果測定
- [ ] ユーザー行動分析
- [ ] コンバージョン最適化

### 長期（3ヶ月以降）
- [ ] コンテンツ拡充
- [ ] 新カード情報追加
- [ ] ユーザーレビュー機能
- [ ] 比較機能強化

## 📞 Contact

- Discord: #project-creditcard-001
- GitHub Issues: https://github.com/webmaster0818/creditcard-001/issues

---

**Last Updated:** 2026-04-02
