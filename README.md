# 🚀 Ohiro Cursor Rules (Solo Full-Stack Optimized)

このリポジトリは、Cursor AIエディタのための包括的なルールセットです。
ソロ開発者が「開発・デザイン・マーケティング・PM」の全領域をワンオペで高速かつ高品質に実行するために最適化されています。

## 🌟 特徴

- **フルスタック対応**: フロントエンド(React/Next.js)、バックエンド(Node.js/Supabase)、デザイン、マーケティングまで網羅。
- **ソロ開発最適化**: チーム開発のオーバーヘッド（承認フロー等）を排除し、CI/CDと自動化による高速ワークフローを実現。
- **最新技術スタック**: React 19, Next.js 15, Tailwind CSS v4, TypeScript 5対応。
- **デザインシステム**: 8pxグリッド、Bento Grid、心理学的デザイン原則（行動経済学）を統合。
- **GCP完全対応**: PowerShell対応の完全自動デプロイスクリプト完備。

## 📁 フォルダ構成

全てのルールファイルは `rules/` ディレクトリ内に格納されています。

| ファイル名 | 分類 | 概要 |
| :--- | :--- | :--- |
| `00-index.mdc` | 目次 | ルールのマスターインデックス |
| `00-mindset.mdc` | 思考 | エンジニアとしての基本原則 (DRY, KISS, MVP優先) |
| `01-design-system.mdc` | デザイン | 8pxグリッド、配色、タイポグラフィの定義 |
| `02-environment-setup.mdc` | 環境 | PowerShell環境設定、日本語解説ルール |
| `03-git-github-workflow.mdc` | Git | ソロ開発用Gitフロー、コミット規約 |
| `04-frontend-basics.mdc` | FE | セマンティックHTML、モダンJS/TS |
| `05-react-patterns.mdc` | FE | React 19, Next.js 15, FSDアーキテクチャ |
| `10-frontend-quality-assurance.mdc` | QA | デザインレビュー、レスポンシブチェック |
| `20-gcp-deploy-complete-guide.mdc` | Deploy | GCP Cloud Runへの完全自動デプロイガイド |
| `21-workflow-master.mdc` | Workflow | ソロ開発最適化ワークフロー |
| `22-tool-usage-policy.mdc` | Tool | AIツールの安全利用ポリシー |
| `23-security-policy.mdc` | Security | OWASP Top 10準拠セキュリティポリシー |
| `24-growth-marketing.mdc` | Biz | グロースハック、行動経済学、KPI設定 |
| `25-performance-tuning.mdc` | Perf | Core Web Vitals最適化、パフォーマンス予算 |
| ...他多数 | | |

## 🚀 使い方

1. このリポジトリの `rules/` フォルダの中身を、あなたのプロジェクトの `.cursor/rules/` フォルダに配置してください。
2. `.cursorrules` ファイル（設定ファイル）を作成し、プロジェクトの特異性を定義します。
3. Cursorでチャットをする際、AIは自動的にこれらのルールを参照して回答します。

## 📄 ライセンス

MIT License
