# Awesome Azure AI / Dynamics 365 / Security

Microsoft Azure AI、Dynamics 365、Power Platform、Identity、Security に関する、日本語を中心とした学習・実務リソース集です。

> A Japanese-first curated list of learning and practical resources for Microsoft Azure AI, Dynamics 365, Power Platform, Identity, and Security.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> ⭐ badges show live GitHub star counts (via shields.io); release badges show the date of the latest GitHub release (YYYY/MM/DD, as of the last refresh); last-commit badges show live commit activity (via shields.io).
>
> ⭐ バッジは GitHub のスター数をリアルタイム表示します(shields.io)。release バッジは GitHub の最新リリース日(YYYY/MM/DD、最終更新時点)を示します。last commit バッジは最新コミット日をリアルタイム表示します(shields.io)。

## 目次 / Table of Contents

- [Azure AI / OpenAI / Machine Learning](#azure-ai--openai--machine-learning)
- [Dynamics 365 / Power Platform](#dynamics-365--power-platform)
- [Security / Identity / Governance](#security--identity--governance)
- [SDK / Samples / Tools](#sdk--samples--tools)
- [Architecture / Cloud Adoption](#architecture--cloud-adoption)
- [学習リソース / Learning Resources](#学習リソース--learning-resources)
- [日本語コミュニティ / Japanese Communities](#日本語コミュニティ--japanese-communities)
- [実務チェックリスト / Production Checklist](#実務チェックリスト--production-checklist)
- [Contributing](#contributing)
- [shvyac's awesome lists](#shvyacs-awesome-lists)

## Azure AI / OpenAI / Machine Learning

Azure 上で AI、生成 AI、機械学習を活用するための公式情報です。

> Official resources for AI, generative AI, and machine learning on Azure.

### 公式ドキュメント / Official Documentation

- [Microsoft Foundry](https://learn.microsoft.com/ja-jp/azure/foundry/) — AI アプリ・エージェントの開発・評価・運用（旧 Azure AI Foundry / Azure AI サービス / Azure OpenAI のドキュメントを統合）
- [Azure Machine Learning](https://learn.microsoft.com/ja-jp/azure/machine-learning/) — 機械学習モデルの開発と運用
- [Foundry Local](https://learn.microsoft.com/ja-jp/azure/foundry-local/) — Windows・macOS・Linux の端末上でモデルを実行するオンデバイス AI ランタイム（OpenAI 互換 API、2026 年 4 月 GA）
- [Azure AI Search](https://learn.microsoft.com/ja-jp/azure/search/) — 検索拡張生成（RAG）で利用できる検索サービス
- [Responsible AI](https://learn.microsoft.com/ja-jp/azure/ai-foundry/responsible-use-of-ai-overview) — Microsoft Foundry における責任ある AI

### GitHub / Samples

- [Azure-Samples](https://github.com/Azure-Samples) — Azure の公式サンプル集
- [azure-ai-docs](https://github.com/MicrosoftDocs/azure-ai-docs) ![GitHub stars](https://img.shields.io/github/stars/MicrosoftDocs/azure-ai-docs?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/MicrosoftDocs/azure-ai-docs?style=flat) — Azure AI ドキュメント
- [azureml-examples](https://github.com/Azure/azureml-examples) ![GitHub stars](https://img.shields.io/github/stars/Azure/azureml-examples?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/Azure/azureml-examples?style=flat) — Azure Machine Learning サンプル
- [foundry-samples](https://github.com/microsoft-foundry/foundry-samples) ![GitHub stars](https://img.shields.io/github/stars/microsoft-foundry/foundry-samples?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/microsoft-foundry/foundry-samples?style=flat) — Microsoft Foundry サンプル
- [Azure-Samples/openai](https://github.com/Azure-Samples/openai) ![GitHub stars](https://img.shields.io/github/stars/Azure-Samples/openai?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/Azure-Samples/openai?style=flat) — Azure OpenAI サンプル
- [Foundry Local](https://github.com/microsoft/foundry-local) ![GitHub stars](https://img.shields.io/github/stars/microsoft/foundry-local?style=flat&label=%E2%AD%90) ![Release date](https://img.shields.io/badge/release-2026%2F11%2F03-blue?style=flat) ![Last commit](https://img.shields.io/github/last-commit/microsoft/foundry-local?style=flat) — Foundry Local の SDK（Python／JavaScript／C#／Rust、MIT ライセンス）とサンプル
- [Microsoft Agent Framework](https://github.com/microsoft/agent-framework) ![New](https://img.shields.io/badge/-NEW-red?style=flat) ![GitHub stars](https://img.shields.io/github/stars/microsoft/agent-framework?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/microsoft/agent-framework?style=flat) — Semantic Kernel と AutoGen の後継となる .NET / Python 向けオープンソースのエージェント開発フレームワーク（2026 年 4 月に 1.0 GA、マルチエージェントのワークフローや MCP に対応）

## Dynamics 365 / Power Platform

業務アプリケーション、Dataverse、ローコード開発、業務自動化に関するリソースです。

> Resources for business applications, Dataverse, low-code development, and automation.

### 公式ドキュメント / Official Documentation

- [Dynamics 365](https://learn.microsoft.com/ja-jp/dynamics365/) — Dynamics 365 製品ドキュメント
- [Power Platform](https://learn.microsoft.com/ja-jp/power-platform/) — Power Platform の概要
- [Dataverse](https://learn.microsoft.com/ja-jp/power-apps/maker/data-platform/) — データモデル、テーブル、環境の管理
- [Power Apps](https://learn.microsoft.com/ja-jp/power-apps/) — アプリ開発と管理
- [Power Automate](https://learn.microsoft.com/ja-jp/power-automate/) — ワークフローと業務自動化
- [Power BI](https://learn.microsoft.com/ja-jp/power-bi/) — データ分析と可視化
- [Copilot Studio](https://learn.microsoft.com/ja-jp/microsoft-copilot-studio/) — AI エージェントの構築
- [Dataverse MCP サーバー](https://learn.microsoft.com/ja-jp/power-apps/maker/data-platform/data-platform-mcp) ![New](https://img.shields.io/badge/-NEW-red?style=flat) — Copilot Studio、GitHub Copilot、Claude などの MCP クライアントから Dataverse のテーブルやデータを操作する

### GitHub / Samples

- [dynamics-365-customer-engagement](https://github.com/MicrosoftDocs/dynamics-365-customer-engagement) ![GitHub stars](https://img.shields.io/github/stars/MicrosoftDocs/dynamics-365-customer-engagement?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/MicrosoftDocs/dynamics-365-customer-engagement?style=flat) — Dynamics 365 Customer Engagement ドキュメント
- [power-platform](https://github.com/MicrosoftDocs/power-platform) ![GitHub stars](https://img.shields.io/github/stars/MicrosoftDocs/power-platform?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/MicrosoftDocs/power-platform?style=flat) — Power Platform ドキュメント
- [PowerPlatformConnectors](https://github.com/microsoft/PowerPlatformConnectors) ![GitHub stars](https://img.shields.io/github/stars/microsoft/PowerPlatformConnectors?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/microsoft/PowerPlatformConnectors?style=flat) — コネクタ定義とサンプル
- [powerapps-docs](https://github.com/MicrosoftDocs/powerapps-docs) ![GitHub stars](https://img.shields.io/github/stars/MicrosoftDocs/powerapps-docs?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/MicrosoftDocs/powerapps-docs?style=flat) — Power Apps ドキュメント
- [powerautomate-docs](https://github.com/MicrosoftDocs/power-automate-docs) ![GitHub stars](https://img.shields.io/github/stars/MicrosoftDocs/power-automate-docs?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/MicrosoftDocs/power-automate-docs?style=flat) — Power Automate ドキュメント

## Security / Identity / Governance

AI と業務データを安全に扱うための、認証、認可、脅威対策、ガバナンスのリソースです。

> Resources for authentication, authorization, threat protection, and governance.

### 公式ドキュメント / Official Documentation

- [Azure Security](https://learn.microsoft.com/ja-jp/azure/security/) — Azure セキュリティの基礎
- [Microsoft Entra](https://learn.microsoft.com/ja-jp/entra/) — ID、アクセス管理、認証
- [Zero Trust](https://learn.microsoft.com/ja-jp/security/zero-trust/) — Zero Trust の設計原則
- [Microsoft Defender for Cloud](https://learn.microsoft.com/ja-jp/azure/defender-for-cloud/) — クラウドセキュリティ態勢管理
- [Microsoft Sentinel](https://learn.microsoft.com/ja-jp/azure/sentinel/) — SIEM とセキュリティ分析
- [Azure Policy](https://learn.microsoft.com/ja-jp/azure/governance/policy/) — 組織のポリシーとコンプライアンス
- [Microsoft Purview](https://learn.microsoft.com/ja-jp/purview/) — データガバナンスとコンプライアンス
- [Azure Key Vault](https://learn.microsoft.com/ja-jp/azure/key-vault/) — シークレット、キー、証明書の管理
- [Microsoft Cloud Security Benchmark](https://learn.microsoft.com/ja-jp/security/benchmark/azure/introduction) — Azure セキュリティ基準

### GitHub / Tools

- [entra-docs](https://github.com/MicrosoftDocs/entra-docs) ![GitHub stars](https://img.shields.io/github/stars/MicrosoftDocs/entra-docs?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/MicrosoftDocs/entra-docs?style=flat) — Microsoft Entra ドキュメント
- [Threat Modeling Tool](https://learn.microsoft.com/ja-jp/azure/security/develop/threat-modeling-tool) — 脅威モデリングツール
- [azure-policy](https://github.com/Azure/azure-policy) ![GitHub stars](https://img.shields.io/github/stars/Azure/azure-policy?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/Azure/azure-policy?style=flat) — Azure Policy のサンプル
- [Microsoft-Defender-for-Cloud](https://github.com/Azure/Microsoft-Defender-for-Cloud) ![GitHub stars](https://img.shields.io/github/stars/Azure/Microsoft-Defender-for-Cloud?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/Azure/Microsoft-Defender-for-Cloud?style=flat) — Defender for Cloud のポリシー・ワークブック・自動化サンプル

## SDK / Samples / Tools

- [Azure SDK for .NET](https://github.com/Azure/azure-sdk-for-net) ![GitHub stars](https://img.shields.io/github/stars/Azure/azure-sdk-for-net?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/Azure/azure-sdk-for-net?style=flat) — .NET SDK
- [Azure SDK for Python](https://github.com/Azure/azure-sdk-for-python) ![GitHub stars](https://img.shields.io/github/stars/Azure/azure-sdk-for-python?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/Azure/azure-sdk-for-python?style=flat) — Python SDK
- [Azure SDK for JavaScript](https://github.com/Azure/azure-sdk-for-js) ![GitHub stars](https://img.shields.io/github/stars/Azure/azure-sdk-for-js?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/Azure/azure-sdk-for-js?style=flat) — JavaScript / TypeScript SDK
- [Azure SDK for Java](https://github.com/Azure/azure-sdk-for-java) ![GitHub stars](https://img.shields.io/github/stars/Azure/azure-sdk-for-java?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/Azure/azure-sdk-for-java?style=flat) — Java SDK
- [Azure SDK for Go](https://github.com/Azure/azure-sdk-for-go) ![GitHub stars](https://img.shields.io/github/stars/Azure/azure-sdk-for-go?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/Azure/azure-sdk-for-go?style=flat) — Go SDK
- [Azure Quickstart Templates](https://github.com/Azure/azure-quickstart-templates) ![GitHub stars](https://img.shields.io/github/stars/Azure/azure-quickstart-templates?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/Azure/azure-quickstart-templates?style=flat) — ARM テンプレート
- [Azure Verified Modules](https://github.com/Azure/Azure-Verified-Modules) ![GitHub stars](https://img.shields.io/github/stars/Azure/Azure-Verified-Modules?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/Azure/Azure-Verified-Modules?style=flat) — Bicep / Terraform の公式 IaC モジュール
- [Bicep](https://github.com/Azure/bicep) ![GitHub stars](https://img.shields.io/github/stars/Azure/bicep?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/Azure/bicep?style=flat) — Azure リソースをコードで管理する IaC ツール
- [Azure CLI](https://github.com/Azure/azure-cli) ![GitHub stars](https://img.shields.io/github/stars/Azure/azure-cli?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/Azure/azure-cli?style=flat) — Azure コマンドラインツール
- [Azure Functions Templates](https://github.com/Azure/azure-functions-templates) ![GitHub stars](https://img.shields.io/github/stars/Azure/azure-functions-templates?style=flat&label=%E2%AD%90) ![Last commit](https://img.shields.io/github/last-commit/Azure/azure-functions-templates?style=flat) — サーバーレス関数テンプレート

## Architecture / Cloud Adoption

設計、移行、運用、コスト、信頼性を含むクラウド活用のリファレンスです。

> References for architecture, migration, operations, cost, and reliability.

- [Azure Architecture Center](https://learn.microsoft.com/ja-jp/azure/architecture/) — リファレンスアーキテクチャと設計ガイド
- [Azure Well-Architected Framework](https://learn.microsoft.com/ja-jp/azure/well-architected/) — 信頼性・セキュリティ・コスト最適化
- [Cloud Adoption Framework](https://learn.microsoft.com/ja-jp/azure/cloud-adoption-framework/) — クラウド導入・統制の方法論
- [Azure Design Patterns](https://learn.microsoft.com/ja-jp/azure/architecture/patterns/) — クラウド設計パターン
- [Landing Zone 実装オプション](https://learn.microsoft.com/ja-jp/azure/cloud-adoption-framework/ready/landing-zone/implementation-options) — Bicep / Terraform / AVM による大規模 Azure 基盤の実装
- [Azure Landing Zones](https://learn.microsoft.com/ja-jp/azure/cloud-adoption-framework/ready/landing-zone/) — セキュアな Azure 基盤

## 学習リソース / Learning Resources

### Microsoft Learn

- [Microsoft Learn 日本語](https://learn.microsoft.com/ja-jp/) — Microsoft 製品の公式学習サイト
- [Azure 学習パス](https://learn.microsoft.com/ja-jp/training/azure/) — Azure の体系的な学習
- [Azure AI 学習](https://learn.microsoft.com/ja-jp/training/browse/?products=azure&terms=ai) — Azure AI の学習コンテンツ
- [Dynamics 365 学習](https://learn.microsoft.com/ja-jp/training/browse/?products=dynamics) — Dynamics 365 の学習コンテンツ
- [Security 学習](https://learn.microsoft.com/ja-jp/training/browse/?terms=security) — セキュリティ関連の学習
- [Azure 認定資格](https://learn.microsoft.com/ja-jp/credentials/browse/?products=azure) — Azure 認定資格一覧

### 日本語の学習観点 / Recommended Learning Path

1. Azure の基本、ネットワーク、ストレージ、コンピューティングを学ぶ
2. Microsoft Entra ID と最小権限のアクセス制御を理解する
3. Azure AI / Azure OpenAI と RAG の基本を学ぶ
4. Dataverse、Dynamics 365、Power Platform を理解する
5. Defender、Sentinel、Policy、Purview で保護と監視を設計する
6. Well-Architected Framework と Cloud Adoption Framework で本番設計を確認する

## 日本語コミュニティ / Japanese Communities

- [JAZUG（Japan Azure User Group）](https://jazug.connpass.com/) — 日本の Azure ユーザーグループ
- [Microsoft Tech Community](https://techcommunity.microsoft.com/) — Microsoft 製品の技術記事とディスカッション
- [Microsoft Security Blog](https://www.microsoft.com/security/blog/) — Microsoft セキュリティの最新情報
- [Microsoft Reactor](https://developer.microsoft.com/ja-jp/reactor/) — 技術イベントと学習コンテンツ
- [Dynamics 365 Community](https://community.dynamics.com/) — Dynamics 365 のコミュニティ

## 実務チェックリスト / Production Checklist

本番環境へ展開する前に、次の観点を確認してください。

> Use this checklist before deploying an AI or business application to production.

- [ ] Microsoft Entra ID を利用し、共有アカウントを避けている
- [ ] ユーザー、アプリ、サービスの権限を最小権限にしている
- [ ] シークレットやキーをコード、ログ、設定ファイルに直接保存していない
- [ ] Key Vault などでシークレットを管理している
- [ ] ネットワークアクセス、Private Endpoint、Firewall を検討している
- [ ] Dataverse と AI データのアクセス範囲を定義している
- [ ] 個人情報・機密情報の分類、保持、マスキングを設計している
- [ ] プロンプトインジェクション、データ漏えい、出力検証を検討している
- [ ] Azure Policy、Defender、監査ログ、アラートを設定している
- [ ] コスト上限、レート制限、可用性、障害時の手順を定義している
- [ ] IaC と CI/CD にセキュリティ検査を組み込んでいる
- [ ] ドキュメント、データフロー、脅威モデルを更新している

## Contributing

掲載したいリソースがあれば、次の条件を満たす Pull Request を歓迎します。

> Pull requests are welcome when proposed resources meet the following criteria.

- Microsoft Azure、Dynamics 365、Power Platform、Identity、Security と直接関連している
- 公式または信頼できる一次情報である
- 説明が簡潔で、リンクが有効である
- 同じ内容の重複掲載ではない
- 日本語または英語で利用できる

Issue や Pull Request では、追加理由と対象カテゴリを記載してください。

## License

このリストの構成・編集物は [CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/) とします（[LICENSE](LICENSE)）。リンク先の各リソースには、それぞれのライセンス・利用条件が適用されます。

## shvyac's awesome lists

All curated lists maintained by [shvyac](https://github.com/shvyac):

- [awesome-ai-dev-tools](https://github.com/shvyac/awesome-ai-dev-tools) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-ai-dev-tools?style=flat&label=%E2%AD%90)
- [awesome-AI-Powered-Executive-Dashboards](https://github.com/shvyac/awesome-AI-Powered-Executive-Dashboards) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-AI-Powered-Executive-Dashboards?style=flat&label=%E2%AD%90)
- [awesome-ai-tool-for-mechanical-engineering](https://github.com/shvyac/awesome-ai-tool-for-mechanical-engineering) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-ai-tool-for-mechanical-engineering?style=flat&label=%E2%AD%90)
- [awesome-audio-softwares](https://github.com/shvyac/awesome-audio-softwares) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-audio-softwares?style=flat&label=%E2%AD%90)
- [awesome-automotive-cae](https://github.com/shvyac/awesome-automotive-cae) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-automotive-cae?style=flat&label=%E2%AD%90)
- [awesome-automotive-todo-mcp](https://github.com/shvyac/awesome-automotive-todo-mcp) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-automotive-todo-mcp?style=flat&label=%E2%AD%90)
- [awesome-azure-ai-dynamics365-security](https://github.com/shvyac/awesome-azure-ai-dynamics365-security) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-azure-ai-dynamics365-security?style=flat&label=%E2%AD%90)
- [awesome-ballroom-dance](https://github.com/shvyac/awesome-ballroom-dance) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-ballroom-dance?style=flat&label=%E2%AD%90)
- [awesome-cad-cae](https://github.com/shvyac/awesome-cad-cae) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-cad-cae?style=flat&label=%E2%AD%90)
- [awesome-cms-ai](https://github.com/shvyac/awesome-cms-ai) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-cms-ai?style=flat&label=%E2%AD%90)
- [awesome-dashboards-visualization](https://github.com/shvyac/awesome-dashboards-visualization) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-dashboards-visualization?style=flat&label=%E2%AD%90)
- [awesome-ghost-artists](https://github.com/shvyac/awesome-ghost-artists) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-ghost-artists?style=flat&label=%E2%AD%90)
- [awesome-hamradio](https://github.com/shvyac/awesome-hamradio) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-hamradio?style=flat&label=%E2%AD%90)
- [awesome-hpc](https://github.com/shvyac/awesome-hpc) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-hpc?style=flat&label=%E2%AD%90)
- [awesome-iso27001-isms-tools](https://github.com/shvyac/awesome-iso27001-isms-tools) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-iso27001-isms-tools?style=flat&label=%E2%AD%90)
- [awesome-local-llm](https://github.com/shvyac/awesome-local-llm) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-local-llm?style=flat&label=%E2%AD%90)
- [awesome-m5stack-arduino](https://github.com/shvyac/awesome-m5stack-arduino) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-m5stack-arduino?style=flat&label=%E2%AD%90)
- [awesome-map-gis](https://github.com/shvyac/awesome-map-gis) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-map-gis?style=flat&label=%E2%AD%90)
- [awesome-mcp-ai](https://github.com/shvyac/awesome-mcp-ai) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-mcp-ai?style=flat&label=%E2%AD%90)
- [awesome-meshless-cae](https://github.com/shvyac/awesome-meshless-cae) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-meshless-cae?style=flat&label=%E2%AD%90)
- [awesome-online-services](https://github.com/shvyac/awesome-online-services) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-online-services?style=flat&label=%E2%AD%90)
- [awesome-open-source-solvers](https://github.com/shvyac/awesome-open-source-solvers) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-open-source-solvers?style=flat&label=%E2%AD%90)
- [awesome-osint-ai](https://github.com/shvyac/awesome-osint-ai) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-osint-ai?style=flat&label=%E2%AD%90)
- [awesome-physical-ai-kaizen](https://github.com/shvyac/awesome-physical-ai-kaizen) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-physical-ai-kaizen?style=flat&label=%E2%AD%90)
- [awesome-quantum](https://github.com/shvyac/awesome-quantum) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-quantum?style=flat&label=%E2%AD%90)
- [awesome-redmine-ai](https://github.com/shvyac/awesome-redmine-ai) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-redmine-ai?style=flat&label=%E2%AD%90)
- [awesome-requirements-system-ai](https://github.com/shvyac/awesome-requirements-system-ai) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-requirements-system-ai?style=flat&label=%E2%AD%90)
- [awesome-trading-stock](https://github.com/shvyac/awesome-trading-stock) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-trading-stock?style=flat&label=%E2%AD%90)
- [awesome-web-app-design](https://github.com/shvyac/awesome-web-app-design) ![GitHub stars](https://img.shields.io/github/stars/shvyac/awesome-web-app-design?style=flat&label=%E2%AD%90)
