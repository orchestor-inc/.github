<p align="center">
  <a href="https://www.orchestor.io">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/orchestor-inc/.github/main/profile/assets/wordmark-dark.svg">
      <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/orchestor-inc/.github/main/profile/assets/wordmark-light.svg">
      <img src="https://raw.githubusercontent.com/orchestor-inc/.github/main/profile/assets/wordmark-light.svg" alt="Orchestor" width="280">
    </picture>
  </a>
</p>

<h3 align="center">AI クリエイティブプラットフォーム</h3>
<p align="center">画像・動画・音声を、Web アプリ、API、CLI、AI エージェントから生成できます。</p>

<p align="center">
  <a href="https://www.orchestor.io">Web サイト</a> ·
  <a href="https://www.orchestor.io/docs">ドキュメント</a> ·
  <a href="https://www.orchestor.io/docs/mcp">MCP</a> ·
  <a href="https://www.orchestor.io/docs/cli">CLI</a> ·
  <a href="https://www.orchestor.io/changelog">変更履歴</a> ·
  <a href="https://github.com/orchestor-inc/.github/blob/main/profile/README.md">English</a>
</p>

---

Orchestor（オーケスター）は、最新の画像・動画・音声モデルを 1 つのアカウントと 1 つのジョブ API で使えるようにします。

- **画像** 文章から生成し、参照画像で編集する。
- **動画** 文章や画像から生成する。編集、アップスケール、リフレーム、背景削除、リップシンク、吹き替え、字幕にも対応。
- **音声** テキスト読み上げとボイスチェンジ。
- **Canvas** ノードをつなぎ、繰り返し使える制作の流れを組み立てる。
- **Marketing Studio** テンプレートや商品素材から広告用の画像・動画を作る。
- **API・CLI・MCP** 同じ生成ジョブを、コード、ターミナル、エージェントから実行する。

## クイックスタート

ホスト型の MCP サーバーにエージェントを接続します。Claude Code の場合:

```sh
claude mcp add --transport http orchestor https://mcp.orchestor.io/mcp
```

`/mcp` を開いて Orchestor にログインし、ワークスペースを選びます。あとは頼むだけです。

> 使える画像モデルを一覧して、白い背景の赤い立方体を生成して。ジョブが終わったら URL を教えて。

Codex、Cursor、OpenCode などの設定は [MCP のセットアップ](https://www.orchestor.io/docs/mcp)を参照してください。

ターミナルから使う場合は CLI をインストールします。

```sh
curl -fsSL https://orchestor.io/install | sh
orc auth login
orc creative image generate --model gpt-image-2 --prompt "白い背景の赤い立方体" --wait
```

## リポジトリ

| リポジトリ | 内容 |
| :--- | :--- |
| [**cli**](https://github.com/orchestor-inc/cli) | Orchestor CLI の `orc`。リリース、インストールスクリプト、Issue トラッカー。 |
| [**skills**](https://github.com/orchestor-inc/skills) | Orchestor 用のエージェントスキル。`npx skills` でインストールできます。 |
| [**orchestor-plugin**](https://github.com/orchestor-inc/orchestor-plugin) | スキルと MCP 接続を 1 つにまとめた、Claude Code などのコーディングエージェント向けプラグイン。 |

## コミュニティ

[CLI の不具合を報告](https://github.com/orchestor-inc/cli/issues) · [スキルを提案](https://github.com/orchestor-inc/skills/pulls) · [お問い合わせ](https://www.orchestor.io/contact) · [セキュリティ](https://github.com/orchestor-inc/cli/blob/main/SECURITY.md)
