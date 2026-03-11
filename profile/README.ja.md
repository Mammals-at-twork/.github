<div align="center">

# 🐾 Mammals@Work

### *Humans & LLMs · 相互理解を深めながら、ひとつのコミットずつより良い未来を構築する*

[![GitHub Org](https://img.shields.io/badge/GitHub-Mammals--at--twork-181717?logo=github&logoColor=white)](https://github.com/Mammals-at-twork)
[![Made with ❤️](https://img.shields.io/badge/Made%20with-%E2%9D%A4%EF%B8%8F-red)](https://github.com/Mammals-at-twork)

</div>

---

## 🧠 コレクティブについて

**Mammals@Work** は、**人間と大規模言語モデル**が協力して、実践的な人間-AI協力の姿を探求するオープンコレクティブです。

最高のソフトウェアは、有機的な創造性と機械的な推論速度が相互に強化される時に構築されると考えています。ここの各リポジトリは、その考えを実験するもので、人間とAIエージェントがピアとして働きながら設計、作成、レビュー、そしてデリバリーされています。

---

## 🎯 目標

| 目標 | 説明 |
|------|------|
| 🤝 **人間-AI シナジー** | 人間とLLMが本番品質のソフトウェア構築において対等なパートナーになれることを示す |
| 🔒 **セキュリティファースト** | デフォルトでセキュアなコードをデリバリーし、すべてのPRに自動SAST/DASTゲートを配置 |
| 🔊 **AIエージェントの声** | LLMに耳と声を与え、エージェントワークフローが自然にコミュニケーションできるようにする |
| 🌍 **オープン＆再利用可能** | すべてをオープンソースとしてリリースし、コミュニティ全体が恩恵を受けるようにする |
| 📈 **継続的品質** | 品質をフェーズではなく、すべてのワークフローに組み込まれたプラクティスとして扱う |

---

## 🚀 プロジェクト

### [`voice-4-llms`](https://github.com/Mammals-at-work/voice-4-llms) &nbsp;·&nbsp; 🔊 エージェント環境向けTTS

> *エージェント環境での迅速なテキスト音声変換のためのDockerizeソリューション。*

Lightweightなnpmスクリプトで、ワンコマンドでDockerベースのTTSエンジンを引き出して実行します。LLMエージェントと自動化パイプラインが手動セットアップなしで音声を生成できるように設計されました。

```bash
npx @mammals-at-work/voice-4-llms run --text "Hello from the collective" --cache
```

**ハイライト**
- ゼロ設定: 1つの`npx`コマンドが`docker pull` + `docker run`を処理
- 繰り返される発話のキャッシュ可能な出力
- Dockerが利用可能な場所ならどこでも動作（CI、VPS、ローカル）

---

### [`YACS`](https://github.com/Mammals-at-work/YACS) &nbsp;·&nbsp; 🧠 Claude Code スキル &nbsp; [![npm](https://img.shields.io/npm/v/@mammals-at-work/yacs?logo=npm&logoColor=white)](https://www.npmjs.com/package/@mammals-at-work/yacs)

> *Yet Another Claude Skills Repo — 各セッションでできることを拡張するClaudeコードスキルの集合。*

Claude Codeのnpm導入可能なスキルパック。各スキルはClaudeが関連性に応じて自動的に呼び出すプロンプトベースのツール、またはあなたが`/skill-name`で手動で呼び出すことができます。セキュリティ監査、アーキテクチャ設計、アイデア対立、データストーリーテリング、ゲーミフィケーションなど — 6言語で提供。

```bash
npx @mammals-at-work/yacs
```

**スキルカテゴリ**
| カテゴリ | スキル例 |
|---------|---------|
| 🔒 品質＆セキュリティ | `/owasp-guardian`, `/llm-safety-checks` |
| 💻 開発 | `/gamify`, `/tech-debt-hunter` |
| 🏗️ アーキテクチャ | `/adr-writer`, `/pattern-finder` |
| 🧠 議論 | `/red-team`, `/brainstorm` |
| 📊 データ | `/data-debate`, `/metric-trap` |

---

### [`paratest`](https://github.com/Mammals-at-work/paratest) &nbsp;·&nbsp; ⚡ 並列テスト

> *複数の並列ワーカーにテストスイートを分割して実行し、より高速に。*

複数の並列ランナー間でテストワークロードをインテリジェントに分配して、テスト実行を高速化するツール — テストコードを一行も変更することなくCI反応時間を短縮します。

---

### [`auto-ralph`](https://github.com/Mammals-at-work/auto-ralph) &nbsp;·&nbsp; 🤖 オートメーション エージェント &nbsp; `🔜 近日公開`

> *近日公開 — お楽しみに！*

---

### [`DevSecOps`](https://github.com/Mammals-at-work/DevSecOps) &nbsp;·&nbsp; 🛡️ セキュリティインフラストラクチャ

> *最高のQA体験のための自社ホスト型CI実行環境を構築するために必要なすべてのスクリプトとツール 🏂*

新しいUbuntu VPSに**SAST + DAST**ツーリングをプロビジョニングするターンキーセキュリティインフラストラクチャキット。高価なSaaSサブスクリプションなしでプロフェッショナルグレードのセキュリティスキャンを必要とするチーム向けです。

**内容**
| レイヤー | ツール |
|---------|--------|
| SAST | Semgrep、SonarQube |
| DAST | OWASP ZAP |
| 依存関係スキャン | OWASP Dependency-Check |
| CIワークフロー | GitHub Actions (SAST & DASTPipelines) |
| コンテナ化 | 各ツール用のDocker Composeスタック |

---

## 🛠️ テックスタック

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?logo=nodedotjs&logoColor=white)
![Shell](https://img.shields.io/badge/Shell-4EAA25?logo=gnubash&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?logo=githubactions&logoColor=white)
![SonarQube](https://img.shields.io/badge/SonarQube-4E9BCD?logo=sonarqube&logoColor=white)
![Semgrep](https://img.shields.io/badge/Semgrep-1B2D55?logo=semgrep&logoColor=white)
![OWASP ZAP](https://img.shields.io/badge/OWASP%20ZAP-000000?logo=owasp&logoColor=white)

</div>

---

## ✅ 品質原則

すべてのプロジェクトで高い品質基準を維持しています：

- **🔍 自動セキュリティスキャン** — SASTとDASTがすべてのプルリクエストで実行され、既知の重大な脆弱性のあるものはマージされません。
- **🐳 再現可能な環境** — すべてのツーリングはDockerコンテナとして提供されるため、「私のマシンでは動く」は言い訳にはなりません。
- **🧪 テストカバレッジ** — 各プロジェクトはテストを備えており、CIはマージ前に実行を強制します。
- **📖 リビングドキュメンテーション** — READMEとインラインドキュメンテーションは事後対応ではなく、ファーストクラスのデリバリーとして扱われます。
- **👁️ ピアレビュー** — 人間の貢献者とAIエージェント双方がお互いのコードをレビューし、異なる推論スタイルをまとめてより良い結果を得ます。
- **♻️ 最小限の足跡** — モノリスよりも小さく組み合わせ可能なツールを好み、不要な依存関係を避けます。

---

## 🤝 貢献

人間 *と* AIエージェントからの貢献を歓迎します。問題を開く、議論を始める、または私たちのリポジトリのいずれかにプルリクエストを提出してください。建設的なアイデアはすべて対象です。

---

<div align="center">
*「インテリジェンスを理解する最良の方法は、それを使って構築することです。」*
</div>
<div align="center">
*"Todo viaje comienza con una pregunta...¿Cerré la llave del gas?"*
</div>
