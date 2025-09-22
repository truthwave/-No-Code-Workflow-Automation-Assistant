<p align="center">
<img width="1536" height="1024" alt="段落テキスト" src="https://github.com/user-attachments/assets/be6ea26e-417b-414f-8676-393183c45109" />
</p>

# 業務プロセス自動化アシスタント（ノーコード連携）

> **「Make、Zapier、Notionなどの自動化設計を、AIが一緒に考えてくれる。」**

👉 [業務プロセス自動化アシスタントをChatGPTで試す](https://chatgpt.com/g/g-686cbee5caec819198409bcf683f72f9-ye-wu-hurosesuzi-dong-hua-asisutanto-nokotolian-xi)

---

## プロジェクト概要
#### [スライド資料はこちら](https://github.com/truthwave/-No-Code-Workflow-Automation-Assistant/tree/main/%E8%B3%87%E6%96%99/%E6%A5%AD%E5%8B%99%E3%83%97%E3%83%AD%E3%82%BB%E3%82%B9%E8%87%AA%E5%8B%95%E5%8C%96GPTs%20%E3%82%B9%E3%83%A9%E3%82%A4%E3%83%89)


---

## 📌 概要

**業務プロセス自動化アシスタント** は、ノーコード／ローコードツールを活用して
繰り返し業務を効率化したい現場のための GPT アシスタントです。

こんな課題に応えます：

* 毎日・毎週の手作業をなんとか自動化したい
* ZapierやMakeで組みたいけど、構成設計が難しい
* 提案書や資料を短時間で作りたい

AIが業務内容をヒアリングし、自動化フローの設計・文書化まで一括支援します。

---

## ✅ 主な機能

### 業務フロー → 自動化フロー変換

* 業務の手順をもとに、最適な自動化構成を提案
* トリガーとアクションの対応関係を明確に整理
* Make / Zapier にそのまま流用可能な構成を出力

### 英語プロンプトの自動生成

* 英語UIに対応したフロー説明文を自動生成
* クライアント提案・国際案件にも活用可能

### 図解・表形式による構成可視化

* JSON風構成、ステップ一覧、フローチャート風の説明など
* 共有資料・議論資料として使いやすいフォーマットを複数用意

### 自動化すべきか否かの判断支援

* "この業務は本当に自動化すべき？"
* 作業負荷・頻度・例外処理などをもとに判断を提案

### 補助的な技術ガイド

* Google Apps Scriptの例文
* ChatGPT API連携のアドバイス（オプション）

---
## 📸 **体験イメージ**
![デモ動画](https://github.com/TomoProgrammingDayori/-No-Code-Workflow-Automation-Assistant/blob/main/%E8%B3%87%E6%96%99/%E3%83%87%E3%83%A2%E5%8B%95%E7%94%BB.gif)

### [スクリーンショットはこちら](https://github.com/truthwave/-No-Code-Workflow-Automation-Assistant/tree/main/%E8%B3%87%E6%96%99/%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88)

---

## 🎯 想定ユーザー

* ノーコードで業務を効率化したい企業・個人
* 毎週の定型業務に時間を奪われている中小企業スタッフ
* ノーコードの提案を行うITコンサルタント
* エンジニアではないが業務改善を推進したい人

---

## 💻 使用例 

### ✅ Notion × Googleカレンダー × Slack連携

**入力：**

```
毎日Notionに日報を書いて、Googleカレンダーに予定も登録しています。
Slackで上司にも通知したいです。
```

**出力例：**

```
Trigger: Notion → Watch Database Item
Action: Google Calendar → Create Event
Action: Slack → Send Message

"New Notion page → Add Google Calendar event → Send Slack message"
```

---

### ✅ Googleフォーム → スプレッドシート → Slack通知

**入力：**

```
Googleフォームに入力が来たら、自動でスプレッドシートに転記し、Slackで通知したい。
```

**出力例：**

```
Trigger: Google Forms → New Response
Action: Google Sheets → Create Row
Action: Slack → Send Channel Message

"New Google Form → Add row to Sheet → Notify on Slack"
```

---

## 🛠 技術的ポイント

* GPTの自動化変換タスクに最適化したプロンプト設計
* Zapier / Make に準拠した英語出力対応
* 非エンジニア向けのわかりやすい出力を徹底
* JSON/表/箇条書き形式で再利用性の高い構成を提供
* 無駄な自動化を防ぐ“判断支援型”構成

---

## ⚠️ ご利用前に必ずご確認ください

* 本ツールは業務提案支援であり、実装動作を保証するものではありません
* 各サービスの仕様変更により、動作しない可能性があります
* 機密データの入力は避けてください
* 最終的な判断・導入はご自身の責任にてお願いします

---

## 🚀 今後の展望

* 複雑な多段構成（条件分岐など）への対応強化
* 多言語（日本語・英語以外）への対応
* 自動フローの構成図（ビジュアル）の出力対応
* ChatGPT API を用いた業務自動化連携の具体例提供

---

## 📄 ライセンス

MIT License

---

> **作業の効率化を“考える時間”すら、もういらない。**

---

## 🧑‍💻 作者

**[Truth Wave ― 真理の波](https://github.com/truthwave)**  
ポートフォリオやAIツール開発に関する情報もぜひご覧ください！

## お気軽にご連絡ください
[📩 ご相談・お見積もりはこちら](mailto:realmadrid71214591@gmail.com)
