<p align="center">
  <a href="https://www.orchestor.io">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/orchestor-inc/.github/main/profile/assets/wordmark-dark.svg">
      <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/orchestor-inc/.github/main/profile/assets/wordmark-light.svg">
      <img src="https://raw.githubusercontent.com/orchestor-inc/.github/main/profile/assets/wordmark-light.svg" alt="Orchestor" width="280">
    </picture>
  </a>
</p>

<h3 align="center">AI は、あなたのブランドをどう伝えているか。</h3>
<p align="center">可視性を計測し、引用元を確認し、根拠に基づいて改善する。</p>

<p align="center">
  <a href="https://www.orchestor.io">Orchestor を見る</a> ·
  <a href="https://docs.orchestor.io">ドキュメント</a> ·
  <a href="#エージェントで始める">はじめる</a> ·
  <a href="https://github.com/orchestor-inc/.github/blob/main/profile/README.md">English</a>
</p>

---

[Orchestor](https://www.orchestor.io) は、AI 回答における自社ブランドの露出を把握し、次の改善を決めるためのマーケティングツールです。Web アプリやターミナルから利用でき、スキルと MCP を通じて普段のエージェントにも接続できます。

### 質問から、改善アクションへ

- **可視性を計測する。** 顧客にとって重要な質問を継続的に観測し、競合と比較します。
- **根拠を確認する。** 保存された AI 回答、引用されたページ、レポートの元になった情報源を調べます。
- **次に取り組むことを決める。** コンテンツの不足を調査し、改善案と追跡できるタスクにまとめます。
- **文脈を保って進める。** ブランド・質問・レポート・アクションを、対象のワークスペースで管理します。

### 使い方に合わせて選ぶ

| プロジェクト | できること | 導入・詳細 |
| :--- | :--- | :--- |
| **[CLI](https://github.com/orchestor-inc/cli)** | ターミナルから Orchestor を操作。公式バイナリ・リリース情報・課題管理を公開しています。 | [インストール](https://github.com/orchestor-inc/cli#install) · [リリース](https://github.com/orchestor-inc/cli/releases) |
| **[Skills](https://github.com/orchestor-inc/skills)** | AI 可視性・調査・モニタリング・根拠に基づく改善のためのエージェント向け手順。英語を標準とし、日本語訳も同梱しています。 | [スキル一覧](https://github.com/orchestor-inc/skills/blob/main/README.ja.md) |
| **[Plugin](https://github.com/orchestor-inc/orchestor-plugin)** | スキル・専門エージェント・コマンド・セッションフック・MCP 接続をまとめたパッケージ。 | [導入方法と対応クライアント](https://github.com/orchestor-inc/orchestor-plugin/blob/main/README.ja.md) |

### エージェントで始める

スキルを追加し、必要なものを選びます。

```sh
npx skills@latest add orchestor-inc/skills
```

まとめて導入する場合は、プラグインを使えます。

```sh
npx plugins add orchestor-inc/orchestor-plugin
```

同じスキルを重複して入れないよう、導入方法はどちらかを選びます。[CLI セットアップガイド](https://orchestor.io/docs/cli) に沿ってワークスペースへ接続してください。CLI と MCP の認証はそれぞれ必要です。

接続後は、エージェントにこう依頼できます。

> 過去 30 日間の自社ブランドの可視性を、この競合と比較してください。引用元を示し、次に取り組む 3 つのアクションを提案してください。

### 一緒に改善する

スキルの改善、CLI の不具合報告、実現したいワークフローの相談を受け付けています。

[スキルへの貢献](https://github.com/orchestor-inc/skills/pulls) · [CLI の課題](https://github.com/orchestor-inc/cli/issues) · [お問い合わせ](https://www.orchestor.io/contact) · [セキュリティ](https://github.com/orchestor-inc/cli/blob/main/SECURITY.md)
