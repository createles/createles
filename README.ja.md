# ようこそ！ 👋

<div align="center">

[![English](https://img.shields.io/badge/README-English-blue.svg)](./README.md) 
[![Japanese](https://img.shields.io/badge/README-日本語-red.svg)](#)

### フルスタックソフトウェアエンジニア | Node.js • Express • PostgreSQL • MongoDB • JavaScript / React
![English](https://img.shields.io/badge/ENG-green) ![Japanese](https://img.shields.io/badge/JP-red) ![Filipino](https://img.shields.io/badge/FIL-blue)

> *パズルソルバーの思考プロセスで、感覚を刺激するWeb体験、インタラクティブツール、没入型ユーザーインターフェースを構築。*

[🌐 ライブポートフォリオ](https://github.com/createles) • [💼 LinkedIn](https://www.linkedin.com/in/jlc7/) • [✉️ メール](mailto:jlazcastillo@gmail.com)

</div>

---

## 💭 プロフィール ＆ エンジニアリングアプローチ

大阪を拠点に活動するフルスタックソフトウェアエンジニアです。Webバックエンドの構築やReactインターフェースの開発をしていないときは、サバイバルホラーゲームのメカニズムを分析したり、複雑な論理パズルを解いて過ごしています。

長年、インタラクティブな学習ツールや教材の制作、多文化コミュニケーションにおける専門家のサポートに携わってきた経験から、「人の好奇心を惹きつける体験をいかに創り出すか」というテーマに魅了されてきました。現在はそのアプローチをWeb開発に応用し、パズル解きのような問題解決とユーザーの達成感を結びつける開発に取り組んでいます。一筋縄ではいかない技術的課題を整理・構造化し、直感的で生き生きとしたレスポンシブなソフトウェア体験へと昇華させることが得意です。

---

## 🛠️ 技術スタック (Technical Core)

| カテゴリ | スキルセット |
| :--- | :--- |
| **開発言語** | JavaScript (ES6+), TypeScript, Python, HTML5, CSS3, SQL |
| **バックエンド & API** | Node.js, Express.js, NestJS, Next.js, WebSockets (Socket.io), 非同期デーモン (Python / asyncio), RESTful APIs, Middleware Architecture, Auth / Sessions |
| **データベース & ストレージ** | PostgreSQL, SQLite (WAL / Single-Writer), MongoDB, Prisma ORM, Supabase, Firebase Storage |
| **フロントエンド & テンプレート** | React, Tailwind CSS, EJS, レスポンシブWebデザイン, 動的DOM操作 |
| **DevOps & 開発ツール** | Git, GitHub, Docker, pnpm Workspaces, Nginx, Playwright, Pytest, Ruff, uv, Railway, Vercel, Netlify, Postman, Multer, Sharp |
| **AIツール & ワークフロー** | Claude Code, Gemini / Antigravity CLI, Cursor, GitHub Copilot |
| **探求中・研究中の技術** | IoT / Raspberry Pi 自動化・ホームサーバー, Godot Engine (ゲームロジック & システムデザイン) |

---

## ⭐️ 注目のプロジェクト (Featured Spotlights)

### 1. [CapsLoc — Game Localization & LQA Triage Hub](https://github.com/createles/capsloc) 🎮
> **リアルタイム・ゲームローカライゼーション & LQA トリアージハブ（フルスタック・モノレポ）**

<div align="center">
  <a href="https://capsloc.up.railway.app/">
    <img src="https://github.com/createles/capsloc/releases/download/v1.0.0-assets/hero_cockpit.gif" alt="CapsLoc コックピット概要" width="680" />
  </a>
  <p align="center">
    <sub>🎮 16:9 コックピットプレビュー — リアルタイム・トリアージチャット、LocStringインスペクター、文字数制限ハザードゲージ。</sub>
  </p>
</div>

* **技術スタック**: `TypeScript (~6.0)` • `NestJS v12` • `React 19` • `Socket.io` • `PostgreSQL 16` • `Prisma 7` • `Tailwind CSS v4` • `Docker` • `pnpm Workspaces`
* **アーキテクチャ ＆ エンジニアリングハイライト**:
  * **統合モノレポ**: バックエンドとフロントエンド間で型安全な共有DTOおよびコントラクトを共有する厳格なpnpmワークスペース。
  * **リアルタイム全二重通信**: Socket.ioによる低遅延トリアージチャット、在席状況（Presence）、タイピングインジケーター。
  * **ゲーム文字列リレーショナル連携**: 正規表現（`#LOC-*`, `$STR_*`）を用いたゲーム内台詞・UI文字列の自動検知とPostgreSQLリレーション連携。
  * **インスペクター＆ハザードゲージ**: 翻訳後のUI文字あふれを防止する動的文字数制限ゲージ、ミリ秒単位の公式用語集（DNTフラグ対応）、および厳格なRBAC承認フロー（`LOC_PM`, `SOLUTIONS_DEV`）。
  * **リフローゼロのバイリンガルエンジン**: 228キーの完全型定義辞書により、画面リフローなしで即時日英切り替え。
* 🚀 **[ライブデモを体験](https://capsloc.up.railway.app/)** • 📦 **[GitHub リポジトリ](https://github.com/createles/capsloc)** • 🏛️ **[アーキテクチャ詳細](https://github.com/createles/capsloc/blob/main/docs/architecture.md)** • [English Documentation](https://github.com/createles/capsloc/blob/main/README.md)

---

### 2. [Sennan City JETs Resource Portal](https://github.com/createles/sennan-jet-resources) 📢
> **実運用コミュニティポータル ＆ 認証付きオンラインマーケットプレイス**

| 🏛️ 行政情報ポータル ＆ ガイド | 🛒 コミュニティマーケットプレイス（動的売買） |
| :---: | :---: |
| <a href="https://sennan-jets.up.railway.app/"><img src="https://raw.githubusercontent.com/createles/sennan-jet-resources/main/assets/herobanner-section.png" alt="Sennan City JETs Portal Banner" width="100%" /></a> | <a href="https://sennan-jets.up.railway.app/"><img src="https://raw.githubusercontent.com/createles/sennan-jet-resources/main/assets/marketplace-section.gif" alt="Community Marketplace Live Demo" width="100%" /></a> |

<p align="center">
  <sub>左: 行政情報・地域ガイドブック • 右: インメモリ画像圧縮パイプライン（Sharp）を統合した認証付きマーケットプレイス。</sub>
</p>

* **技術スタック**: `Node.js` • `Express` • `EJS` • `PostgreSQL` • `Prisma ORM` • `Supabase Storage` • `Railway` • `Multer` • `Sharp`
* **アーキテクチャ ＆ エンジニアリングハイライト**:
  * **本番運用実績**: 泉南市の公務員・外国語指導員向けに実運用されている一站式情報ガイドブックおよび認証付きマーケットプレイス。
  * **インメモリ画像最適化**: サーバーメモリ内でアップロード画像を即座にインターセプト・圧縮する `Multer` + `Sharp` パイプラインにより、クライアント遅延ゼロでストレージフットプリントを**70%以上**削減。
  * **リレーショナルスキーマ管理**: Prisma ORMによるユーザー認証、物品予約ライフサイクル、公開掲示板のデータ整合性管理。
* 🚀 **[アプリを体験](https://sennan-jets.up.railway.app/)** • 📦 **[GitHub リポジトリ](https://github.com/createles/sennan-jet-resources)** • [English Documentation](https://github.com/createles/sennan-jet-resources/blob/main/README.md) • [日本語ドキュメント](https://github.com/createles/sennan-jet-resources/blob/main/README.ja.md)

---

### 🔧 その他の主要システム・実装プロジェクト (Targeted Systems)

### 3. [JP PC Parts Price & Stock Watcher](https://github.com/createles/price-watcher) ⚡
> **非同期型EC在庫・価格監視デーモン**
>
> * **技術スタック**: `Python 3.12+` • `Playwright Async` • `Pydantic v2` • `SQLite (WAL)` • `Discord Webhooks` • `Pytest` • `uv`
> * **エンジニアリングハイライト**: Strategyパターンによる国内主要PCパーツ量販店（ツクモ・ドスパラ・PCワンズ）の非同期DOMスクレイピング、`asyncio.Queue`を活用したシングルライター構成によるSQLiteロック競合の完全排除、状態遷移を捉える純粋関数型差分検知エンジンおよびDiscord Webhook通知パイプラインを設計。160件の密閉テスト（Hermetic Test）を0.6秒未満で高速実行。
> * 📦 [GitHub リポジトリ](https://github.com/createles/price-watcher) • [English Documentation](https://github.com/createles/price-watcher/blob/main/README.md) • [日本語ドキュメント](https://github.com/createles/price-watcher/blob/main/README.ja.md)

### 4. [Memoreat](https://github.com/createles/memoreat) 🍽️
> **コンテナ化された食事記録アプリ ＆ 自動CI/CDパイプライン**
>
> * **技術スタック**: `Next.js` • `TypeScript` • `React` • `PostgreSQL` • `Prisma ORM` • `Docker` • `GitHub Actions` • `Framer Motion`
> * **エンジニアリングハイライト**: フルスタックのNext.jsアプリとPostgreSQLデータベースをDocker Composeでコンテナ化。GitHub Actionsを用いた自動CI/CDパイプラインを構築し、GitHub Container Registry (GHCR) へ本番イメージを自動ビルド・公開。
> * 🚀 [ライブアプリ](https://memoreat-production.up.railway.app/) • 📦 [GitHub リポジトリ](https://github.com/createles/memoreat) • [English Documentation](https://github.com/createles/memoreat/blob/main/README.md) • [日本語ドキュメント](https://github.com/createles/memoreat/blob/main/README.ja.md)

### 5. [Pass-n-Go Captcha Middleware](https://github.com/createles/pass-n-go) 🔐
> **インタラクティブBot対策ビジュアル検証ミドルウェア**
>
> * **技術スタック**: `JavaScript (ES6+)` • `Express` • `React` • `HTML5/CSS3` • `MongoDB` • `Prisma ORM` • `Supabase` • `Railway`
> * **エンジニアリングハイライト**: 動的な3x3画像グリッドシステムを活用したカスタムセキュリティミドルウェアを構築。従来の静的CAPTCHAを即時かつステートフルな視覚的フィードバックに置き換え、セキュリティ強度を維持しながらユーザー体験を最適化。
> * 🚀 [ライブアプリ](https://pass-n-go-captcha.up.railway.app/) • 📦 [GitHub リポジトリ](https://github.com/createles/pass-n-go) • [English Documentation](https://github.com/createles/pass-n-go/blob/main/README.md) • [日本語ドキュメント](https://github.com/createles/pass-n-go/blob/main/README.ja.md)

### 6. [Gobble Drive](https://github.com/createles/gooble-drive) 🗃️
> **クラウドストレージ ＆ ファイル管理プラットフォーム**
>
> * **技術スタック**: `Node.js` • `Express` • `JavaScript (ES6+)` • `Database Storage` • `Railway`
> * **エンジニアリングハイライト**: マルチパートファイルアップロード、再帰的なフォルダ階層管理、動的データベースクエリをサポートするフルスタックファイル管理システムを設計。
> * 🚀 [ライブアプリ](https://gobble-drive-production.up.railway.app/) • 📦 [GitHub リポジトリ](https://github.com/createles/gooble-drive) • [English Documentation](https://github.com/createles/gobble-drive/blob/main/README.md) • [日本語ドキュメント](https://github.com/createles/gobble-drive/blob/main/README.ja.md)

---

## 💼 職務経歴・実績概要

* **インタラクティブ学習ツール・デジタルメディア開発** | *JETプログラム (約5年間)*
  * **自動化とツール開発**: 地域向けのインタラクティブWebアプリケーションやアクティビティ、プログラム可能なクイズツール、デジタル/物理連動マッピング教材を開発して授業フレームワークを刷新。自治体内の全学校への導入を実現。
  * **プロジェクトリーダーシップ**: 国際化コミュニティでのイニシアチブ（300人規模のイベント向け体感型謎解きアクティビティを含む）を牽引。能動的な問題解決を促す目的達成型プログラムを設計。

* **テクニカルプログラムデリバリー ＆ エンタープライズソリューション** | *企業向けスペシャリスト (約3年間)*
  * **クライアントソリューション設計**: 大手グローバル企業（Accenture、Toyotaなど）向けに特化した技術研修フレームワークの設計・デリバリーを担当し、複雑な業務要件と厳格なSLAマイルストーンを両立。
  * **データ・評価パイプライン管理**: 標準化された評価ワークフローを運用し、200名以上の企業ステークホルダー向けに診断評価データパイプラインをベンチマーク評価・管理。

---

## 🌐 トライリンガル能力 (Trilingual Capabilities)

* **JLPT N2 認定**: 日本語の技術ドキュメントの解読、社内システムの理解、業務成果物・納品物の翻訳に十分対応可能。
* **英語・フィリピン語（ネイティブレベル）**: 英語およびフィリピン語の業務環境においてプロフェッショナルレベルのネイティブな流暢さを保有。
* **クロスカルチャー・テクニカルコミュニケーション**: 多言語チーム（英語・日本語・フィリピン語）において、要件定義、仕様書のハンドオフ、ドキュメントレビューの円滑な進行を推進。

---

<div align="center">
  <sub>日本国内（オフィス・ハイブリッド）およびリモートでのフルスタックソフトウェアエンジニアの機会を探しています。</sub>
</div>
