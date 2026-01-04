<h1 align="center">Awesome Claude Skills</h1>

<p align="center">
<a href="https://platform.composio.dev/?utm_source=Github&utm_medium=Youtube&utm_campaign=2025-11&utm_content=AwesomeSkills">
  <img width="1280" height="640" alt="Composio banner" src="https://github.com/user-attachments/assets/adb3f57a-2706-4329-856f-059a32059d48">
</a>


</p>

<p align="center">
  <a href="https://awesome.re">
    <img src="https://awesome.re/badge.svg" alt="Awesome" />
  </a>
  <a href="https://makeapullrequest.com">
    <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square" alt="PRs Welcome" />
  </a>
  <a href="https://www.apache.org/licenses/LICENSE-2.0">
    <img src="https://img.shields.io/badge/License-Apache_2.0-blue.svg?style=flat-square" alt="License: Apache-2.0" />
  </a>
</p>
<div>
<p align="center">
  <a href="https://twitter.com/composio">
    <img src="https://img.shields.io/badge/Follow on X-000000?style=for-the-badge&logo=x&logoColor=white" alt="Follow on X" />
  </a>
  <a href="https://www.linkedin.com/company/composiohq/">
    <img src="https://img.shields.io/badge/Follow on LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="Follow on LinkedIn" />
  </a>
  <a href="https://discord.com/invite/composio">
    <img src="https://img.shields.io/badge/Join our Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Join our Discord" />
  </a>
  </p>
</div>

Claude.ai、Claude Code、Claude API全体で生産性を向上させるための実用的なClaude Skillsの厳選リストです。


> スキルで500以上のアプリにまたがるアクションを実行したい場合は、[Composio](https://platform.composio.dev/?utm_source=Github&utm_medium=Youtube&utm_campaign=2025-11&utm_content=AwesomeSkills)と連携してください


## 目次

- [Claude Skillsとは？](#claude-skillsとは)
- [スキル一覧](#スキル一覧)
  - [ドキュメント処理](#ドキュメント処理)
  - [開発・コードツール](#開発コードツール)
  - [データ・分析](#データ分析)
  - [ビジネス・マーケティング](#ビジネスマーケティング)
  - [コミュニケーション・ライティング](#コミュニケーションライティング)
  - [クリエイティブ・メディア](#クリエイティブメディア)
  - [生産性・整理](#生産性整理)
  - [コラボレーション・プロジェクト管理](#コラボレーションプロジェクト管理)
  - [セキュリティ・システム](#セキュリティシステム)
- [はじめに](#はじめに)
- [スキルの作成](#スキルの作成)
- [コントリビューション](#コントリビューション)
- [リソース](#リソース)
- [ライセンス](#ライセンス)

## Claude Skillsとは？

Claude Skillsは、Claudeに特定のタスクを独自の要件に従って実行する方法を教えるカスタマイズ可能なワークフローです。スキルにより、Claudeはすべてのプラットフォームで再現可能かつ標準化された方法でタスクを実行できます。

## スキル一覧

### ドキュメント処理

- [docx](https://github.com/anthropics/skills/tree/main/skills/docx) - 変更履歴、コメント、書式設定を含むWordドキュメントの作成、編集、分析。
- [pdf](https://github.com/anthropics/skills/tree/main/skills/pdf) - PDFからのテキスト、表、メタデータの抽出、結合、注釈付け。
- [pptx](https://github.com/anthropics/skills/tree/main/skills/pptx) - スライド、レイアウト、テンプレートの読み込み、生成、調整。
- [xlsx](https://github.com/anthropics/skills/tree/main/skills/xlsx) - スプレッドシート操作：数式、グラフ、データ変換。
- [Markdown to EPUB Converter](https://github.com/smerchek/claude-epub-skill) - マークダウンドキュメントやチャットの要約をプロフェッショナルなEPUB電子書籍ファイルに変換。*[@smerchek](https://github.com/smerchek)作*

### 開発・コードツール

- [artifacts-builder](https://github.com/anthropics/skills/tree/main/web-artifacts-builder) - モダンなフロントエンドウェブ技術（React、Tailwind CSS、shadcn/ui）を使用して、精巧なマルチコンポーネントのclaude.ai HTMLアーティファクトを作成するためのツールスイート。
- [aws-skills](https://github.com/zxkane/aws-skills) - CDKのベストプラクティス、コスト最適化MCPサーバー、サーバーレス/イベント駆動アーキテクチャパターンによるAWS開発。
- [Changelog Generator](./changelog-generator/) - gitコミットを分析し、技術的なコミットを顧客向けのリリースノートに変換して、ユーザー向けの変更ログを自動作成。
- [Claude Code Terminal Title](https://github.com/bluzername/claude-code-terminal-title) - 各Claude Codeターミナルウィンドウに作業内容を説明する動的なタイトルを付けて、どのウィンドウで何をしているか把握しやすくする。
- [D3.js Visualization](https://github.com/chrisvoncsefalvay/claude-d3js-skill) - ClaudeにD3チャートやインタラクティブなデータビジュアライゼーションの作成を教える。*[@chrisvoncsefalvay](https://github.com/chrisvoncsefalvay)作*
- [FFUF Web Fuzzing](https://github.com/jthack/ffuf_claude_skill) - ffufウェブファザーを統合し、Claudeがファジングタスクを実行して脆弱性の結果を分析できるようにする。*[@jthack](https://github.com/jthack)作*
- [finishing-a-development-branch](https://github.com/obra/superpowers/tree/main/skills/finishing-a-development-branch) - 明確なオプションを提示し、選択されたワークフローを処理することで開発作業の完了をガイド。
- [iOS Simulator](https://github.com/conorluddy/ios-simulator-skill) - ClaudeがiOSシミュレーターと対話してiOSアプリケーションのテストとデバッグを行えるようにする。*[@conorluddy](https://github.com/conorluddy)作*
- [MCP Builder](./mcp-builder/) - PythonまたはTypeScriptを使用して、外部APIやサービスをLLMと統合するための高品質なMCP（Model Context Protocol）サーバーの作成をガイド。
- [move-code-quality-skill](https://github.com/1NickPappas/move-code-quality-skill) - Move言語パッケージをMove 2024 Edition準拠およびベストプラクティスのための公式Move Bookコード品質チェックリストに照らして分析。
- [Playwright Browser Automation](https://github.com/lackeyjb/playwright-skill) - Webアプリケーションのテストと検証のためのモデル呼び出しPlaywright自動化。*[@lackeyjb](https://github.com/lackeyjb)作*
- [prompt-engineering](https://github.com/NeoLabHQ/context-engineering-kit/tree/master/plugins/customaize-agent/skills/prompt-engineering) - Anthropicのベストプラクティスやエージェント説得原則を含む、よく知られたプロンプトエンジニアリング技術とパターンを教える。
- [pypict-claude-skill](https://github.com/omkamal/pypict-claude-skill) - PICT（Pairwise Independent Combinatorial Testing）を使用して要件やコードの包括的なテストケースを設計し、ペアワイズカバレッジで最適化されたテストスイートを生成。
- [Skill Creator](./skill-creator/) - 専門知識、ワークフロー、ツール統合で機能を拡張する効果的なClaude Skillsの作成ガイダンスを提供。
- [Skill Seekers](https://github.com/yusufkaraaslan/Skill_Seekers) - 任意のドキュメントウェブサイトを数分でClaude AIスキルに自動変換。*[@yusufkaraaslan](https://github.com/yusufkaraaslan)作*
- [software-architecture](https://github.com/NeoLabHQ/context-engineering-kit/tree/master/plugins/ddd/skills/software-architecture) - Clean Architecture、SOLID原則、包括的なソフトウェア設計ベストプラクティスを含む設計パターンを実装。
- [subagent-driven-development](https://github.com/NeoLabHQ/context-engineering-kit/tree/master/plugins/sadd/skills/subagent-driven-development) - 迅速で制御された開発のために、個々のタスクに独立したサブエージェントを派遣し、イテレーション間にコードレビューチェックポイントを設置。
- [test-driven-development](https://github.com/obra/superpowers/tree/main/skills/test-driven-development) - 機能やバグ修正を実装する際、実装コードを書く前に使用。
- [using-git-worktrees](https://github.com/obra/superpowers/blob/main/skills/using-git-worktrees/) - スマートなディレクトリ選択と安全性検証を備えた分離されたgitワークツリーを作成。
- [Webapp Testing](./webapp-testing/) - フロントエンド機能の検証、UIの動作デバッグ、スクリーンショットのキャプチャにPlaywrightを使用してローカルWebアプリケーションをテスト。

### データ・分析

- [CSV Data Summarizer](https://github.com/coffeefuelbump/csv-data-summarizer-claude-skill) - CSVファイルを自動分析し、ユーザーのプロンプトなしでビジュアライゼーションを含む包括的な洞察を生成。*[@coffeefuelbump](https://github.com/coffeefuelbump)作*
- [postgres](https://github.com/sanjay3290/ai-skills/tree/main/skills/postgres) - マルチ接続サポートと多層防御セキュリティを備えたPostgreSQLデータベースに対する安全な読み取り専用SQLクエリを実行。*[@sanjay3290](https://github.com/sanjay3290)作*
- [root-cause-tracing](https://github.com/obra/superpowers/tree/main/skills/root-cause-tracing) - 実行の深部でエラーが発生し、元のトリガーを見つけるためにトレースバックする必要がある場合に使用。

### ビジネス・マーケティング

- [Brand Guidelines](./brand-guidelines/) - 一貫したビジュアルアイデンティティとプロフェッショナルなデザイン基準のために、Anthropicの公式ブランドカラーとタイポグラフィをアーティファクトに適用。
- [Competitive Ads Extractor](./competitive-ads-extractor/) - 広告ライブラリから競合他社の広告を抽出・分析し、響くメッセージングとクリエイティブアプローチを理解。
- [Domain Name Brainstormer](./domain-name-brainstormer/) - クリエイティブなドメイン名のアイデアを生成し、.com、.io、.dev、.ai拡張子を含む複数のTLDでの利用可能性をチェック。
- [Internal Comms](./internal-comms/) - 会社固有のフォーマットを使用して、3Pアップデート、社内ニュースレター、FAQ、ステータスレポート、プロジェクトアップデートを含む社内コミュニケーションの作成を支援。
- [Lead Research Assistant](./lead-research-assistant/) - 製品を分析し、ターゲット企業を検索し、実行可能なアウトリーチ戦略を提供することで、高品質なリードを特定・評価。

### コミュニケーション・ライティング

- [article-extractor](https://github.com/michalparkola/tapestry-skills-for-claude-code/tree/main/article-extractor) - Webページから記事の全文とメタデータを抽出。
- [brainstorming](https://github.com/obra/superpowers/tree/main/skills/brainstorming) - 構造化された質問と代替案の探索を通じて、大まかなアイデアを完全に形成されたデザインに変換。
- [Content Research Writer](./content-research-writer/) - 調査の実施、引用の追加、フックの改善、セクションごとのフィードバック提供により、高品質なコンテンツの作成を支援。
- [family-history-research](https://github.com/emaynard/claude-family-history-research-skill) - 家族の歴史と系図調査プロジェクトの計画を支援。
- [Meeting Insights Analyzer](./meeting-insights-analyzer/) - 会議の書き起こしを分析し、対立回避、発言比率、フィラーワード、リーダーシップスタイルなどの行動パターンを明らかに。
- [NotebookLM Integration](https://github.com/PleasePrompto/notebooklm-skill) - Claude CodeがNotebookLMと直接チャットし、アップロードされたドキュメントのみに基づいたソースグラウンデッドな回答を得られるようにする。*[@PleasePrompto](https://github.com/PleasePrompto)作*

### クリエイティブ・メディア

- [Canvas Design](./canvas-design/) - ポスター、デザイン、静止画像のための設計哲学と美的原則を使用して、PNGおよびPDFドキュメントで美しいビジュアルアートを作成。
- [imagen](https://github.com/sanjay3290/ai-skills/tree/main/skills/imagen) - UIモックアップ、アイコン、イラスト、ビジュアルアセットのためにGoogle Geminiの画像生成APIを使用して画像を生成。*[@sanjay3290](https://github.com/sanjay3290)作*
- [Image Enhancer](./image-enhancer/) - プロフェッショナルなプレゼンテーションやドキュメンテーションのために、解像度、シャープネス、明瞭度を向上させて画像とスクリーンショットの品質を改善。
- [Slack GIF Creator](./slack-gif-creator/) - サイズ制約のバリデーターと構成可能なアニメーションプリミティブを備えたSlack最適化のアニメーションGIFを作成。
- [Theme Factory](./theme-factory/) - 10個のプリセットテーマを使用して、スライド、ドキュメント、レポート、HTMLランディングページを含むアーティファクトにプロフェッショナルなフォントとカラーテーマを適用。
- [Video Downloader](./video-downloader/) - さまざまなフォーマットと品質オプションをサポートし、オフライン視聴、編集、またはアーカイブのためにYouTubeやその他のプラットフォームからビデオをダウンロード。
- [youtube-transcript](https://github.com/michalparkola/tapestry-skills-for-claude-code/tree/main/youtube-transcript) - YouTubeビデオからトランスクリプトを取得し、要約を準備。

### 生産性・整理

- [File Organizer](./file-organizer/) - コンテキストを理解し、重複を見つけ、より良い組織構造を提案することで、ファイルとフォルダをインテリジェントに整理。
- [Invoice Organizer](./invoice-organizer/) - ファイルを読み込み、情報を抽出し、一貫した名前に変更することで、確定申告用の請求書と領収書を自動整理。
- [kaizen](https://github.com/NeoLabHQ/context-engineering-kit/tree/master/plugins/kaizen/skills/kaizen) - 日本の改善哲学とリーン手法に基づいた複数の分析アプローチで継続的改善手法を適用。
- [n8n-skills](https://github.com/haunchen/n8n-skills) - AIアシスタントがn8nワークフローを直接理解し操作できるようにする。
- [Raffle Winner Picker](./raffle-winner-picker/) - 暗号学的に安全な乱数を使用して、プレゼントやコンテスト用にリスト、スプレッドシート、またはGoogleスプレッドシートから当選者をランダムに選択。
- [ship-learn-next](https://github.com/michalparkola/tapestry-skills-for-claude-code/tree/main/ship-learn-next) - フィードバックループに基づいて、次に何を構築または学習するかを繰り返し検討するためのスキル。
- [tapestry](https://github.com/michalparkola/tapestry-skills-for-claude-code/tree/main/tapestry) - 関連ドキュメントを相互リンクし、ナレッジネットワークに要約。

### コラボレーション・プロジェクト管理

- [git-pushing](https://github.com/mhattingpete/claude-skills-marketplace/tree/main/engineering-workflow-plugin/skills/git-pushing) - git操作とリポジトリのインタラクションを自動化。
- [review-implementing](https://github.com/mhattingpete/claude-skills-marketplace/tree/main/engineering-workflow-plugin/skills/review-implementing) - コード実装計画を評価し、仕様に合わせる。
- [test-fixing](https://github.com/mhattingpete/claude-skills-marketplace/tree/main/engineering-workflow-plugin/skills/test-fixing) - 失敗したテストを検出し、パッチや修正を提案。

### セキュリティ・システム

- [computer-forensics](https://github.com/mhattingpete/claude-skills-marketplace/tree/main/computer-forensics-skills/skills/computer-forensics) - デジタルフォレンジクス分析と調査技術。
- [file-deletion](https://github.com/mhattingpete/claude-skills-marketplace/tree/main/computer-forensics-skills/skills/file-deletion) - 安全なファイル削除とデータ消去方法。
- [metadata-extraction](https://github.com/mhattingpete/claude-skills-marketplace/tree/main/computer-forensics-skills/skills/metadata-extraction) - フォレンジック目的のファイルメタデータの抽出と分析。
- [threat-hunting-with-sigma-rules](https://github.com/jthack/threat-hunting-with-sigma-rules-skill) - Sigma検出ルールを使用して脅威を追跡し、セキュリティイベントを分析。

## はじめに

### Claude.aiでスキルを使用する

1. チャットインターフェースでスキルアイコン（🧩）をクリック。
2. マーケットプレイスからスキルを追加するか、カスタムスキルをアップロード。
3. Claudeがタスクに基づいて関連するスキルを自動的に有効化。

### Claude Codeでスキルを使用する

1. スキルを`~/.config/claude-code/skills/`に配置：
   ```bash
   mkdir -p ~/.config/claude-code/skills/
   cp -r skill-name ~/.config/claude-code/skills/
   ```

2. スキルのメタデータを確認：
   ```bash
   head ~/.config/claude-code/skills/skill-name/SKILL.md
   ```

3. Claude Codeを起動：
   ```bash
   claude
   ```

4. スキルは自動的に読み込まれ、関連する場面で有効化されます。

### API経由でスキルを使用する

Claude Skills APIを使用してプログラムでスキルを読み込み、管理：

```python
import anthropic

client = anthropic.Anthropic(api_key="your-api-key")

response = client.messages.create(
    model="claude-3-5-sonnet-20241022",
    skills=["skill-id-here"],
    messages=[{"role": "user", "content": "Your prompt"}]
)
```

詳細は[Skills APIドキュメント](https://docs.claude.com/en/api/skills-guide)を参照してください。

## スキルの作成

### スキルの構造

各スキルは、YAMLフロントマターを含む`SKILL.md`ファイルを持つフォルダです：

```
skill-name/
├── SKILL.md          # 必須：スキルの指示とメタデータ
├── scripts/          # オプション：ヘルパースクリプト
├── templates/        # オプション：ドキュメントテンプレート
└── resources/        # オプション：参照ファイル
```

### 基本的なスキルテンプレート

```markdown
---
name: my-skill-name
description: このスキルが何をするか、いつ使用するかの明確な説明。
---

# My Skill Name

スキルの目的と機能の詳細な説明。

## このスキルを使用するタイミング

- ユースケース1
- ユースケース2
- ユースケース3

## 指示

[このスキルを実行するためのClaudeへの詳細な指示]

## 例

[スキルの実際の使用例]
```

### スキルのベストプラクティス

- 特定の反復可能なタスクに焦点を当てる
- 明確な例とエッジケースを含める
- エンドユーザーではなくClaude向けに指示を書く
- Claude.ai、Claude Code、API全体でテスト
- 前提条件と依存関係を文書化
- エラー処理のガイダンスを含める

## コントリビューション

コントリビューションを歓迎します！詳細については[コントリビューションガイドライン](CONTRIBUTING.md)をお読みください：

- 新しいスキルの提出方法
- スキルの品質基準
- プルリクエストプロセス
- 行動規範

### クイックコントリビューション手順

1. スキルが実際のユースケースに基づいていることを確認
2. 既存のスキルとの重複を確認
3. スキル構造テンプレートに従う
4. プラットフォーム全体でスキルをテスト
5. 明確なドキュメントとともにプルリクエストを提出

## リソース

### 公式ドキュメント

- [Claude Skillsの概要](https://www.anthropic.com/news/skills) - 公式発表と機能
- [Skillsユーザーガイド](https://support.claude.com/en/articles/12512180-using-skills-in-claude) - Claudeでのスキルの使用方法
- [カスタムスキルの作成](https://support.claude.com/en/articles/12512198-creating-custom-skills) - スキル開発ガイド
- [Skills APIドキュメント](https://docs.claude.com/en/api/skills-guide) - API統合ガイド
- [エージェントスキルブログ記事](https://anthropic.com/engineering/equipping-agents-for-the-real-world-with-agent-skills) - エンジニアリングの詳細

### コミュニティリソース

- [Anthropic Skillsリポジトリ](https://github.com/anthropics/skills) - 公式のサンプルスキル
- [Claudeコミュニティ](https://community.anthropic.com) - 他のユーザーとスキルについて議論
- [Skillsマーケットプレイス](https://claude.ai/marketplace) - スキルの発見と共有

### インスピレーション＆ユースケース

- [Lenny's Newsletter](https://www.lennysnewsletter.com/p/everyone-should-be-using-claude-code) - Claude Codeの50の使い方
- [Notion Skills](https://www.notion.so/notiondevs/Notion-Skills-for-Claude-28da4445d27180c7af1df7d8615723d0) - Notion統合スキル


## コミュニティに参加

- 認証設定とComposioの統合について質問がありますか？[お気軽にお電話ください](https://calendly.com/thomas-composio/composio-enterprise-setup)
- [Twitterでフォロー](https://x.com/composio)
- [Discordに参加](https://discord.com/invite/composio)

## ライセンス

このリポジトリはApache License 2.0の下でライセンスされています。

個々のスキルには異なるライセンスがある場合があります - 具体的なライセンス情報については各スキルのフォルダを確認してください。

---

**注意**: Claude SkillsはClaude.ai、Claude Code、Claude API全体で動作します。スキルを作成すれば、すべてのプラットフォームでポータブルに使用でき、Claudeを使用するすべての場所でワークフローを一貫させることができます。

- [AgentsKB](https://agentskb.com) - 調査済みの回答でAIをアップグレード。私たちが調査を行ったので、あなたのAIは最初から正しい答えを得られます。
