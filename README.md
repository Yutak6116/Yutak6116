# Yuta Kanehara (Yuta.K)

京都大学 情報学研究科 データ科学専攻 所属

![3Dコントリビューション](profile-3d-contrib/profile-season-animate.svg)

## 🚀 自己紹介

MLエンジニア / フルスタックエンジニア / データサイエンス

スキル : TypeScript (React, Vue.js), Firebase (Auth, Firestore), Python (LightGBM, scikit-learn)

趣味 : ゴルフ (ベスト77), ポーカー (BigFish, トーナメント優勝経験あり)

## 🛠 プロジェクト

### Portfolio

[<img src="https://img.shields.io/badge/Website-000000?style=flat-square&logo=google-chrome&logoColor=white" />](https://yutak-web.github.io/Portfolio/) [<img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" />](https://github.com/yutak-web/Portfolio)

**ReactとTypeScriptで構築した個人ポートフォリオサイト。**

- 個人開発
- **技術スタック**: React, TypeScript, Three.js

---

### Poker Totalization System

[<img src="https://img.shields.io/badge/Website-000000?style=flat-square&logo=google-chrome&logoColor=white" />](https://BigFish-Poker-Dev.github.io/Poker-Totalization-System/) [<img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" />](https://github.com/BigFish-Poker-Dev/Poker-Totalization-System)

**ポーカーサークル BigFish 向けに、日々の戦績・収支・ランキングを一元管理するWebアプリ。**

- 個人開発
- **技術スタック**: React, TypeScript, Vite, Tailwind CSS, Zustand, Firebase (Authentication, Firestore), React Router
- **主な機能**:
  - **グループ管理**: 6桁のグループID、Player/Adminパスワードによる参加管理と、グループごとの設定変更に対応しました。
  - **収支報告**: 日付、ステークス、バイイン、終了時スタック、メモを登録し、BBまたは点数ベースで収支を自動計算できるようにしました。
  - **収支確認**: カレンダー、累計グラフ、データベースビューを用意し、月次・日次・履歴単位で収支を確認できるようにしました。
  - **ランキング**: 累計収支ランキングに加え、日別の順位推移グラフを実装しました。
- **やったこと**:
  - **データ設計**: Firestore上にグループ、プレイヤー、収支、更新履歴のデータ構造を設計し、登録・編集・削除に伴う集計更新を実装しました。
  - **収支計算ロジック**: 固定SB/BB、BB・点数の単位切り替え、過去データ換算を考慮した収支計算ロジックを実装しました。
  - **権限管理**: Player/Adminで画面と操作を分離し、管理者はグループ設定、全プレイヤーの収支編集、更新履歴確認を行えるようにしました。
  - **可視化UI**: ランキングテーブル、ランキング推移グラフ、収支推移グラフ、カレンダー表示を実装し、サークル内で戦績を追いやすくしました。

---

### Kake-AI-bo

[<img src="https://img.shields.io/badge/Website-000000?style=flat-square&logo=google-chrome&logoColor=white" />](https://yutak-web.github.io/Kake-AI-bo/) [<img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" />](https://github.com/yutak-web/Kake-AI-bo)

**複数の財布・口座・クレジットカードを一元管理し、収支と資産状況を可視化する家計簿アプリ。**

- 個人開発
- **技術スタック**: React, TypeScript, Vite, Firebase (Authentication, Firestore), React Router, Recharts, Tailwind CSS
- **主な機能**:
  - **取引登録**: 支出、収入、財布間の資金移動を登録し、利用財布・カテゴリ・内容・備考を紐づけて管理できるようにしました。
  - **ウォレット管理**: 銀行口座、その他財布、クレジットカードを分けて管理し、初期残高、表示順、色、引き落とし口座を設定できるようにしました。
  - **クレカ支払い管理**: 締め日・支払日から引き落とし日を自動計算し、直近の支払い予定額を確認できるようにしました。
  - **集計・可視化**: 総資産残高、財布別残高、カテゴリ別の支出・収入、ウォレット別の残高推移をグラフで確認できるようにしました。
  - **絞り込み・編集**: 期間、カテゴリ、ウォレット、立替ステータスで履歴を絞り込み、登録済み取引の編集・削除に対応しました。
- **やったこと**:
  - **要件定義**: 既存アプリの不満点を洗い出し、「ウォレット別管理」「クレカ支払い予定」「立替管理」をコア機能として定義しました。
  - **データモデリング**: Firestore上にウォレット、カテゴリ、取引データを設計し、ユーザーごとのデータ分離とセキュリティルールを実装しました。
  - **取引ロジック実装**: 支出・収入・資金移動による各ウォレット残高の増減、クレカ引き落とし日計算、立替申請・立替済みフラグを実装しました。
  - **ダッシュボード実装**: Rechartsを用いたカテゴリ別円グラフ、ウォレット別残高表示、残高推移グラフを実装しました。

## 📫 連絡先

[<img src="https://img.shields.io/badge/-black?style=flat-square&logo=x&logoColor=white" />](https://x.com/yutak_dev) @yutak_dev

[<img src="https://img.shields.io/badge/Gmail-D14836?style=flat-square&logo=gmail&logoColor=white" />](mailto:yk.individual@gmail.com) yk.individual((at))gmail.com

[<img src="https://img.shields.io/badge/Zenn-3EA8FF?style=flat-square&logo=zenn&logoColor=white" />](https://zenn.dev/yutak6116) yutak6116
