![Caleb Leung — AI engineering, backend systems, and retrieval](assets/profile-banner-retro.webp)

<p align="center">
  <a href="README.md">English</a>&nbsp;&nbsp;|&nbsp;&nbsp;
  <a href="README.zh-HK.md">繁體中文（香港）</a>&nbsp;&nbsp;|&nbsp;&nbsp;
  <strong>日本語</strong>
</p>

<p align="center">
  <a href="#概要">概要</a>&nbsp;&nbsp;|&nbsp;&nbsp;
  <a href="#主なプロジェクト">プロジェクト</a>&nbsp;&nbsp;|&nbsp;&nbsp;
  <a href="#現在調査中のテーマ">研究ノート</a>&nbsp;&nbsp;|&nbsp;&nbsp;
  <a href="#連絡先">連絡先</a>
</p>

---

## 概要

Brooklyn を拠点とする Software engineer。IntellPro で production AI systems を構築しています。

document processing、retrieval、embedding pipelines に取り組み、信頼性の高い backend systems と測定可能な retrieval quality を重視しています。

---

## 主なプロジェクト

| Project | Work |
| --- | --- |
| **IntellPro** | document ingestion、OCR、chunking、metadata extraction、embedding orchestration のための AI infrastructure を構築し、1日あたり約 3,000 documents を処理しています。 |
| **Anime MCP** | anime-character search 向けの MCP server を構築中です。現在は evaluation と lexical-retrieval foundation を開発し、embeddings を実装する前に hybrid fusion と relevance calibration を研究しています。 |

---

## 現在調査中のテーマ

> **lexical scores と semantic scores の score distributions が異なる場合、どのように組み合わせるべきか？**

hybrid fusion の基礎を学び、score normalization と異なる score distributions が ranking に与える影響を調べています。次に relevance-probability calibration と query-adaptive fusion を検討する予定です。

### 参考論文

- [An Analysis of Fusion Functions for Hybrid Retrieval](https://arxiv.org/abs/2210.11934)
- [Score distribution models: assumptions, intuition, and robustness to score manipulation](https://dl.acm.org/doi/10.1145/1835449.1835491)
- [Classifier Calibration: A survey on how to assess and improve predicted class probabilities](https://arxiv.org/abs/2112.10327)
- [Query Performance Prediction for Neural IR: Are We There Yet?](https://arxiv.org/abs/2302.09947)

---

## 主なツールと技術

| Area | Technologies |
| --- | --- |
| **Languages** | Python · Elixir · TypeScript |
| **Backend & orchestration** | FastAPI · Pydantic · SQLAlchemy · Phoenix · Oban Pro |
| **Data & search** | PostgreSQL · Elasticsearch · OpenSearch |
| **Infrastructure** | AWS (ECS, S3, SQS) · Docker · GitHub Actions |
| **Python tooling** | asyncio · pytest |

[Full skills & technologies →](https://caleb-leung-kwan-ho.github.io/github-website/#skills)

---

## 連絡先

[LinkedIn](https://www.linkedin.com/in/caleb-kwan-ho-leung-a67b74168/) · [Email](mailto:caleb.leungkwanho@gmail.com)

<sub>Last updated: September 2026</sub>
