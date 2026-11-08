# labs

**Learn. Experiment. Understand. Improve.**

A personal engineering laboratory for exploring software technologies, validating ideas, and documenting practical knowledge.

このリポジトリは、ソフトウェアエンジニアとしての技術力・設計力・問題解決能力を高めるための技術検証リポジトリです。

学んだ技術を小さなコードや実験環境で検証し、その結果や設計上の判断を記録することで、実務で活用できる知識を積み上げていきます。

## Purpose

**技術の仕組みを理解し、根拠を持って設計・実装・改善できるエンジニアになる。**

このリポジトリでは、以下の能力を継続的に高めることを目指します。

- **Technical Understanding** — 技術の使い方だけでなく、内部の仕組みや設計思想を理解する
- **Problem Solving** — 課題を分析し、仮説と検証に基づいて解決する
- **Software Design** — 要件や制約に応じて、適切な設計・技術選定を行う
- **Engineering Practices** — テスト、保守性、自動化、品質改善を実践する
- **AI-assisted Development** — CodexなどのAIツールを活用し、開発プロセスの効率と品質を高める
- **Knowledge Sharing** — 学んだ知識を整理し、再現可能な形で共有する

単にコードを動かすことではなく、**なぜその実装を選択したのか、どのような結果が得られたのかを説明できること**を重視します。

## Goals — First 90 Days

**期間：2026-11-09 〜 2027-02-07**

最初の90日間は、Web開発の基礎技術とAIを活用した開発手法を中心に、実践的な技術検証を行います。

大規模なアプリケーションの完成ではなく、小さな検証を積み重ねることを優先します。

### Technical Focus

| Area                            | Learning Topics                                                                          |
| ------------------------------- | ---------------------------------------------------------------------------------------- |
| Docker                          | Dockerfile、Compose、ネットワーク、ボリューム、マルチステージビルド                      |
| SQL                             | JOIN、インデックス、実行計画、トランザクション                                           |
| Database Design                 | 正規化、ER図、制約、データモデリング                                                     |
| Go                              | エラー処理、interface、context、並行処理、テスト                                         |
| TypeScript / React / Next.js    | 型システム、Generics、型ガード、コンポーネント設計、レンダリング、データ取得、キャッシュ |
| GitHub Actions / CI/CD          | テスト自動化、ビルド、CI/CDワークフロー                                                  |
| Codex / AI-assisted Development | Skills、SKILL.md、AGENTS.md、開発ワークフローの改善                                      |
| Engineering Practices           | 問題解決、設計判断、テスト戦略、保守性、ADR                                              |

### Key Results

- [ ] 技術検証を8〜10件実施する
- [ ] 検証コード・結果・考察をGitHubに記録する
- [ ] 技術記事を3本以上公開する
- [ ] 学んだ内容を実務で1件以上活用する
- [ ] Codex Skillsを1〜2個作成し、技術検証で使用する
- [ ] Skills導入による効果と限界を評価する
- [ ] 90日間の成果を振り返り、次の学習テーマを決める

## Learning Process

**Learn → Hypothesize → Experiment → Evaluate → Document → Share**

1. **Learn** — 公式ドキュメントや技術資料から基本概念を学ぶ
2. **Hypothesize** — 検証する疑問と予想される結果を明確にする
3. **Experiment** — 小さなコードや環境を用意して検証する
4. **Evaluate** — 結果を分析し、設計や実装のトレードオフを考える
5. **Document** — 実行手順・結果・考察をGitHubに記録する
6. **Share** — 特に学びの大きかった内容を技術記事として公開する

各検証では、原則として以下を記録します。

- Objective：検証目的
- Hypothesis：仮説
- Environment：実行環境
- Procedure：検証手順
- Result：実行結果
- Analysis：考察
- Application：実務への応用可能性

## AI-assisted Development

Codex Skillsなどを活用し、繰り返し行う開発作業を再利用可能なワークフローとして定義・改善します。

最初は、技術検証を支援する `technical-experiment` Skillの作成を予定しています。

AIを利用する場合も、生成されたコードや説明を自分で理解・検証し、技術的な判断の根拠を明確にすることを重視します。

## Repository Structure

```text
labs/
├── .agents/
│   └── skills/
│       └── technical-experiment/
│           └── SKILL.md
├── docker/
├── sql/
├── database-design/
├── go/
├── typescript/
│   ├── fundamentals/
│   ├── react/
│   └── nextjs/
├── nextjs/
├── github-actions/
├── engineering-practices/
├── AGENTS.md
└── README.md
```

ディレクトリは学習の進行に応じて追加・変更します。

## Engineering Principles

1. **Understand Before Implementing** — 実装前に目的と仕組みを理解する
2. **Start Small** — 最小限の構成から検証する
3. **Think in Hypotheses** — 仮説を立て、実験によって確認する
4. **Explain Decisions** — 技術選定や設計の理由を説明する
5. **Verify, Don't Assume** — 推測やAIの回答を検証する
6. **Build for Maintainability** — 保守性と変更容易性を意識する
7. **Automate Repetitive Work** — 繰り返し作業の自動化を検討する
8. **Apply Knowledge in Practice** — 学習内容を実務上の課題に結びつける
9. **Keep Learning Sustainable** — 継続的な改善と知識の蓄積を重視する

## Milestones

| Period    | Focus                                      |
| --------- | ------------------------------------------ |
| Week 1    | 学習環境・リポジトリの整備                 |
| Week 2–3  | Docker、Docker Compose、Codex Skillsの基礎 |
| Week 4–5  | SQL、データベース設計                      |
| Week 6–7  | Go、テスト、並行処理、Skillの作成          |
| Week 8    | 中間レビュー                               |
| Week 9–10 | TypeScript、React / Next.js、Skillの改善   |
| Week 11   | GitHub Actions、CI/CD                      |
| Week 12   | 設計・問題解決、Skillsの評価               |
| Week 13   | 成果の整理、次の学習計画                   |

## Continuous Improvement

このリポジトリは、継続的な学習と技術検証の記録として更新していきます。

学習した内容を実際に試し、その結果を振り返ることで、技術的な理解と問題解決能力を少しずつ高めていきます。

**Learn by doing. Improve through reflection.**
