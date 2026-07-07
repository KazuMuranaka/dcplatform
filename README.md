# DC PLATFORM JAPAN

データセンターをつくる、すべての人のためのプラットフォーム。

一般社団法人グリーンXアライアンスが運営する、データセンター開発の中立的な情報・支援サイトです（事業実務：グリーンX合同会社）。

**公開URL:** https://dcplatform.jp/
（旧URL https://kazumuranaka.github.io/dcplatform/ からは自動転送）

## サイト構成

### メインコンテンツ
| ファイル | ページ |
|---|---|
| `index.html` | トップページ（8つの視点・計算力指数ボード・サービス案内） |
| `news.html` | ニュースの視点（業界ニュース＋編集部の解釈） |
| `projectmap.html` | プロジェクトMAP（公表済み開発案件の地図） |
| `computeindex.html` | 計算力指数（GPU価格の参考指標・売上シミュレーター） |
| `glossary.html` | 用語解説（DC開発辞典・66語） |
| `faq.html` | データセンター開発FAQ（40問） |
| `consult.html` | 開発相談窓口（7つの相談タイプ） |

### 基礎知識シリーズ・診断ツール
| ファイル | ページ |
|---|---|
| `sitecheck.html` | 用地簡易診断ツール（高圧／特別高圧の2コース・9要件） |
| `gpu.html` | GPU基礎データ・比較表（NVIDIA / AMD 主要7製品） |
| `cooling.html` | 冷却技術の基礎・比較（空冷〜液浸・排熱利用） |
| `power.html` | 電力・系統接続の基礎（受電方式・需要側接続手続き） |
| `network.html` | 通信・回線の基礎（ダークファイバ・遅延・冗長化） |
| `reliability.html` | 信頼性・Tier等級の基礎（Tier I〜IV・N+1/2N・UPS） |

### 素材・設定ファイル
- `dc_hero.jpg` — トップページのヒーロー画像
- `CNAME` — 独自ドメイン設定（GitHubが自動管理。削除しないこと）
- `sitemap.xml` — 検索エンジン用サイトマップ（ページ追加時に更新）
- `robots.txt` — クローラー設定

## 技術構成

- 静的HTML（フレームワーク・ビルド不要）。各ページにCSS/JSを内包した単一ファイル構成
- ホスティング：GitHub Pages ＋ 独自ドメイン `dcplatform.jp`（お名前.com管理、Aレコード＋www CNAME）
- フォント：Noto Serif JP / Noto Sans JP / IBM Plex Mono（Google Fonts）
- デザイントークン：深緑 `#1F4D36`・オフホワイト `#F6F4ED`・金 `#A8894A`

## 更新方法

該当するHTMLファイルを編集し、このリポジトリに上書きアップロード（同名ファイルは自動で上書き）。数分でGitHub Pagesに反映されます。

## 注記

本サイトの解説・数値は一般的な情報提供であり、法務・税務・投資・技術の個別助言ではありません。

© 2026 DC PLATFORM JAPAN（仮称）／一般社団法人グリーンXアライアンス
