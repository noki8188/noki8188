# Hi, I'm Zixuan Wu / 呉 梓軒

修士課程で研究を行いながら、業務システム開発・データ活用・クラウド実装を継続的に学んでいます。  
I’m a master’s student who enjoys building business systems, data-driven applications, and cloud-based solutions while continuously learning through hands-on projects.

---

## About Me / 自己紹介

日本語  
私は、まず業務や利用者の流れを理解し、その上で設計・実装・検証を丁寧に積み上げることを大切にしています。  
特定の技術だけに固執するのではなく、目的に応じてツールやアーキテクチャを学び、試し、比較しながら改善していく姿勢を重視しています。  
まだ学ぶことは多いですが、好奇心を持って新しい技術に触れ、謙虚に手を動かしながら、実務に近い形で成果物を積み上げています。

English  
I value understanding business flow and user needs first, then building systems step by step through careful design, implementation, and validation.  
Rather than relying on one technology only, I try to choose tools and architectures based on purpose, learn them quickly, compare approaches, and improve iteratively.  
I still have a lot to learn, but I enjoy staying curious, working hands-on, and building practical portfolio projects with humility and discipline.

---

## Working Style / 開発姿勢

日本語  
すべての個人開発・作品づくりにおいて、以下の流れを意識しています。

**要件定義 → 基本設計 → 詳細設計 → 開発 → テスト（UT／IT／ST） → リリース → 運用保守**

単に「動くもの」を作るだけでなく、  
- 何を解決するのか  
- どのような設計判断をしたのか  
- どのように検証したのか  
- 今後どう改善できるのか  

まで含めて整理し、GitHub 上でも読み手に伝わる形にすることを心がけています。

English  
Across all of my projects, I try to follow the full lifecycle:

**Requirements Definition → High-Level Design → Detailed Design → Development → Testing (UT / IT / ST) → Release → Operation & Maintenance**

My goal is not only to make something that works, but also to make clear:
- what problem it solves,
- what design decisions were made,
- how it was validated,
- and how it can be improved further.

---

## Technical Interests / 技術的な関心

- Full-stack web development
- Backend/API design
- Business systems and internal tools
- AI-assisted workflow automation
- Cloud architecture on AWS
- Data analysis / BI / analytics workflows
- Test automation and validation

---

## Tech Stack / 技術スタック

### Application Development
- React
- TypeScript
- Vite
- Node.js
- Express
- FastAPI
- Prisma

### Database / Data
- MySQL
- PostgreSQL
- SQL
- Python
- BI / analytics-oriented data modeling

### Cloud / Infrastructure
- Docker
- Docker Compose
- AWS
  - ECS Fargate
  - ALB
  - RDS
  - CloudWatch
  - IAM
- Terraform

### Testing / Quality
- Jest
- Vitest
- Playwright
- Swagger / API documentation
- CI workflows

---

## Featured Projects / 代表プロジェクト

### 1. [ec-inventory-management-system]
**Small-scale EC Inventory Management System**  
React, Express, Prisma, MySQL, Docker, Swagger, Playwright を用いて構築したフルスタック作品です。  
ユーザー向け購買導線と、管理者向けの商品・在庫・注文管理を一体化し、認証・権限制御・在庫整合性・API 設計・自動検証までを一通り整理しました。

- React + TypeScript frontend
- Express + Prisma backend
- JWT authentication and role-based access control
- Transaction-based ordering and stock consistency
- Swagger API docs, Docker Compose, CI, Playwright smoke test

---

### 2. [team-knowledge-copilot-v1]
**Internal Knowledge Assistant Prototype**  
FastAPI ベースの社内向けナレッジアシスタントです。  
ドキュメント取り込み、引用付き Q&A、AI 日報生成などを通じて、業務知識の検索性と共有効率を高めることを目指しました。

- FastAPI-based backend
- Document ingestion pipeline
- Citation-based Q&A
- AI-assisted daily report generation
- Knowledge workflow prototype for internal teams

---

### 3. [Internal-Ops-Ticket-Hub]
**Internal Operations Ticket Platform on AWS**  
社内運用向けのチケット管理システムで、AWS 上での構成を意識して設計したプロジェクトです。  
アプリケーションの機能だけでなく、ALB・ECS Fargate・RDS・CloudWatch・IAM Role・Terraform による構成管理まで含めて、運用を見据えた形でまとめています。

- AWS ECS Fargate
- Application Load Balancer (ALB)
- RDS PostgreSQL
- CloudWatch logs and monitoring
- IAM role design
- Terraform-based infrastructure definition

---

### 4. [MetaERP]
**Salesforce-inspired ERP Product Prototype**  
Salesforce のような「オブジェクト駆動・メタデータ駆動」の考え方を意識した ERP プロトタイプです。  
単なる CRUD ではなく、業務オブジェクト、画面構成、承認ワークフロー、運用管理の観点を意識して設計しています。

- Object-driven design
- Metadata-driven UI concept
- Approval-based procurement workflow
- Enterprise-style admin product prototype

---

### 5. [Ecommerce-Sales-Inventory-Analytics-Portfolio]
**BI / Analytics Portfolio for Ecommerce Operations**  
EC の売上分析・在庫健全性・仕入先パフォーマンス・欠品リスク分析を題材にしたデータ分析作品です。  
SQL、Python、指標設計、レポーティングの観点を整理し、データから業務改善提案につなげることを意識しています。

- Ecommerce KPI analysis
- Sales and inventory health analytics
- Supplier performance analysis
- Stockout risk perspective
- BI / reporting-oriented portfolio work

---

## What I Try to Show Through My Projects / 作品を通して示したいこと

日本語  
私は、派手な技術を並べることよりも、  
**「課題を理解し、設計し、作り、検証し、改善する」** という一連のプロセスを大切にしています。

そのため、GitHub 上の各プロジェクトでも以下を意識しています。
- README や設計資料を残す
- 実装意図と構成を説明できるようにする
- テストや検証結果を残す
- 将来の改善点も書いておく

English  
More than simply collecting technologies, I try to demonstrate the full engineering process:
**understand the problem, design a solution, build it, validate it, and improve it.**

That is why my repositories usually include:
- README and design notes
- implementation rationale
- test/validation steps
- future improvements and limitations

---

## Current Focus / 現在注力していること

- 業務システム・社内ツール開発
- API / backend design
- AI を活用した実務支援機能
- AWS を用いた運用を意識した構成
- データ分析・BI 的な視点を含むアプリケーション設計
- 自動テストとブラウザ検証

---

## Languages / 言語

- Japanese / 日本語
- English / 英語
- Chinese / 中文

技術文書・README・設計メモを、日本語と英語の両方で整理することを意識しています。  
I try to keep technical documentation and project descriptions readable in both Japanese and English.

---

## Links / リンク

- GitHub: [@noki8188](https://github.com/noki8188)

---

## Note / 補足

日本語  
まだ学習中の領域も多いですが、その分、わからないことをそのままにせず、調べ、試し、比較し、形にすることを大切にしています。  
これからも、好奇心と謙虚さを持って、実務に近い形の開発経験を積み重ねていきたいと考えています。

English  
There is still a lot for me to learn, but that is exactly why I try to investigate, experiment, compare approaches, and turn ideas into practical results.  
I hope to continue building real-world development experience with curiosity, consistency, and humility.
