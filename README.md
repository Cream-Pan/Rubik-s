<div id="top"></div>

## 使用技術一覧

<p style="display: inline">
  <img src="https://img.shields.io/badge/-HTML5-E34F26.svg?logo=html5&style=for-the-badge&logoColor=white">
  <img src="https://img.shields.io/badge/-CSS3-1572B6.svg?logo=css3&style=for-the-badge&logoColor=white">
  <img src="https://img.shields.io/badge/-JavaScript-F7DF1E.svg?logo=javascript&style=for-the-badge&logoColor=black">
  <img src="https://img.shields.io/badge/-Swiper-6332F6.svg?logo=swiper&style=for-the-badge&logoColor=white">
  <img src="https://img.shields.io/badge/-Netlify-00C7B7.svg?logo=netlify&style=for-the-badge&logoColor=white">
  <img src="https://img.shields.io/badge/-GitHub-181717.svg?logo=github&style=for-the-badge">
</p>

## 目次

1. [プロジェクトについて](#プロジェクトについて)
2. [環境](#環境)
3. [ディレクトリ構成](#ディレクトリ構成)
4. [主な機能](#主な機能)
5. [開発者情報](#開発者情報)

## プロジェクト名

ルービックキューブ紹介サイト

## プロジェクトについて

ルービックキューブの魅力，歴史，脳への効果，そして解法習得からタイム計測までをトータルでサポートすることを目的としたWebアプリケーションです．
初心者向けの基本解法から，中上級者向けのOLL/PLLといった手順一覧，さらには練習に欠かせないタイマー機能までを統合し，ユーザーが効率的に学習できる環境を構築しました．

<p align="right">(<a href="#top">トップへ</a>)</p>

## 環境

| カテゴリ | 技術・ライブラリ |
| --------------------- | ---------- |
| 言語 | HTML5, CSS3, JavaScript |
| ライブラリ | Swiper.js (スライダー実装) |
| デプロイ | Netlify |

<p align="right">(<a href="#top">トップへ</a>)</p>

## ディレクトリ構成
```
.
├── index.html                          # メインページ（総合案内）
├── timer.html                          # タイム計測機能ページ
├── oll.html                            # OLL手順一覧
├── pll.html                            # PLL手順一覧
├── solve.html                          # 解法解説ページ
├── patarn.html                         # 特殊パターン紹介ページ
├── kaiten.html                         # 回転記号・動作解説ページ
├── vari.html                           # バリエーション解説
├── yami.html                           # 解法解説
├── main1.css / main2.css / main3.css   # スタイル定義
├── dist/                               # 外部ライブラリ（Swiper等）
├── images/                             # 図解・パターン画像資産
└── README.md
```

<p align="right">(<a href="#top">トップへ</a>)</p>

## 主な機能

### 1．多角的な学習支援機能
* **理論と歴史**: 単なる解法の提示だけでなく，歴史や論理的思考力を養う効果についても解説し，教養としての側面をカバーしています．
* **手順図解表示**: OLLやPLLといった複雑な手順を，豊富な画像資産（`images/`）を用いて視覚的に解説しており，紙媒体として印刷することも可能です．
* **回転記号解説**: `kaiten.html`において，キューブ独自の回転記号を初心者でも理解できるよう整理しました．
* **バリエーション紹介**: 2x2や4x4といった異なる種類のキューブについても情報を集約しています．
* **ハイブリッド学習ガイド**: Webサイト形式の解説に加え，YouTube動画等の外部リソースとも連携し，ユーザーが最適な学習方法を選択できるよう設計しました．

### 2．インタラクティブな練習ツール
* **多機能練習用タイマー**: 競技に不可欠な「スクランブルの自動生成」および「ベストタイムの自動記録」機能を実装しています．
* **OLL進捗チェッカー**: Cookieを利用し，ユーザーがどの手順を習得したかをブラウザに保存できる機能を備えています．これにより，ログイン不要で学習の継続性を担保しています．

### 3．UX/UI
* **レスポンシブデザイン**: PC，タブレット，スマートフォンすべてにおいて，最適な閲覧環境を提供します．特に「キューブを持ちながらの操作」を想定したモバイル表示を重視しました．

<p align="right">(<a href="#top">トップへ</a>)</p>

## ページアクセス

URL　:　[https://rubik-s.netlify.app/](https://rubik-s.netlify.app/)
<p align="right">(<a href="#top">トップへ</a>)</p>

## 開発者情報
* **Name**: Takato Ishii
* **Portfolio**: [https://takato-ishii.vercel.app/](https://takato-ishii.vercel.app/)

<p align="right">(<a href="#top">トップへ</a>)</p>