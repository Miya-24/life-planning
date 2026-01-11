# Azure Fundamentals（AZ-900）学習戦略

## 目的
- 今年中に Azure Fundamentals（AZ-900）に合格する
- クラウドと Azure の基礎構造を理解し、実務に耐える土台を作る

この戦略は  
「何を・どの順番で・どのレベルまでやるか」を明確にし、  
GitHub の週次運用に組み込むための設計書である。

---

## 基本思想

AZ-900 は、

> **用語暗記ではなく、サービスの役割と構成を理解して答える試験**

である。

よって目標は：

- Azure の主要サービスを
- 「何に使うか」「どう組み合わせるか」
- を説明できる状態になること

---

## 試験範囲の大分類

AZ-900 の内容は、次の4カテゴリに集約できる：

- Cloud Concepts
- Core Azure Services
- Azure Architecture & Management
- Security, Privacy, Compliance & Trust

すべての学習はこのどれかに属する。

---

## 使用リソース

### 1. 基本教材（フェーズ1〜3で使用）
- [Azure Fundamentals ラーニングパス](https://learn.microsoft.com/ja-jp/training/courses/az-900t00)

---

### 2. 補助教材
- [Microsoft Azure AZ-900 Exam Prep](https://www.udemy.com/course/microsoft-azure-az900-exam)
- [Microsoft Azure AZ-900 Video Course](https://www.udemy.com/course/microsoft-azure-az900-video)


用途：
- Learn だけで理解しにくい部分の補足
- フェーズ2〜3での弱点補強

---

## 学習フェーズ

Azure 学習は必ずこの3フェーズのどれかに属する。

---

### フェーズ1：基礎構築
**目的**
- Azure の主要サービスと用語を説明できる状態になる

**内容**
- Microsoft Learn をカテゴリ順に進める
- 各サービスの「用途・役割・位置づけ」を理解する
- Compute / Storage / Network / Security の関係を把握する

---

### フェーズ2：問題対応力の構築
**目的**
- 試験問題を読んで、選択肢の良し悪しが判断できる状態になる

**内容**
- Learn の確認問題・演習
- Udemy の問題・テスト
- サービスの比較・違いを意識して解く

---

### フェーズ3：弱点補強
**目的**
- 間違えやすいサービスや分野を潰す

**内容**
- ミスした分野をピンポイントで復習
- Learn / Udemy を使って該当分野だけをやり直す

---

## GitHub運用との対応

Azure のすべての学習は GitHub Issue として管理する。

### heavy / light の使い分け

| 種類 | 内容 |
|------|------|
| `azure + heavy` | Learn モジュール、新規理解、問題演習、模試 |
| `azure + light` | 復習、まとめ、ノート整理、用語確認 |

※ 問題を解く作業は「復習」であっても heavy とする。

---

## フェーズの表記方法（重要）

フェーズは **Label ではなく Issue の Title に書く**。

例：  
- Azure：Cloud Concepts 基礎理解（フェーズ1）  
- Azure：Core Services Learn モジュール3（フェーズ1）  
- Azure：Compute & Storage 問題演習（フェーズ2）  
- Azure：Security 弱点補強（フェーズ3）  


これにより：
- 今どの段階か
- 今は理解フェーズか、演習フェーズか

が Project の一覧を見るだけで分かる。

---

## 戦略と週次運用の関係

- 週の Project には、この戦略に沿った Issue を並べる
- 進捗は「理解度」ではなく **完了した Issue** で管理する
- 理解の不足は週間レビューで次週に反映する

> **Azure戦略 = 方針**  
> **Issue = 実行ログ**

AP と同じ構造で Azure も回すことで、
学習システム全体が一貫したものになる。
