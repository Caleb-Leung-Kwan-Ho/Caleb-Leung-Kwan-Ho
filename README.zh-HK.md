![Caleb Leung — AI engineering, backend systems, and retrieval](assets/profile-banner-retro.webp)

<p align="center">
  <a href="README.md">English</a>&nbsp;&nbsp;|&nbsp;&nbsp;
  <strong>繁體中文（香港）</strong>&nbsp;&nbsp;|&nbsp;&nbsp;
  <a href="README.ja-JP.md">日本語</a>
</p>

<p align="center">
  <a href="#簡介">簡介</a>&nbsp;&nbsp;|&nbsp;&nbsp;
  <a href="#精選項目">項目</a>&nbsp;&nbsp;|&nbsp;&nbsp;
  <a href="#目前研究中">研究筆記</a>&nbsp;&nbsp;|&nbsp;&nbsp;
  <a href="#聯絡">聯絡</a>
</p>

---

## 簡介

身處 Brooklyn 的 Software engineer，現於 IntellPro 建構 production AI systems。

我從事 document processing、retrieval 和 embedding pipelines，著重可靠的 backend systems 及可量度的 retrieval quality。

---

## 精選項目

| Project | Work |
| --- | --- |
| **IntellPro** | 為 document ingestion、OCR、chunking、metadata extraction 和 embedding orchestration 建構 AI infrastructure，每日處理約 3,000 份文件。 |
| **Anime MCP** | 正在為 anime-character search 建構 MCP server。現正開發其 evaluation 和 lexical-retrieval foundation，並在實作 embeddings 前研究 hybrid fusion 和 relevance calibration。 |

---

## 目前研究中

> **當 lexical 和 semantic scores 的 score distributions 不同時，應如何結合？**

我正在研究 hybrid fusion 的基礎，著重 score normalization 和不同 score distributions 對 ranking 的影響。下一步會研究 relevance-probability calibration 和 query-adaptive fusion。

### 參考論文

- [An Analysis of Fusion Functions for Hybrid Retrieval](https://arxiv.org/abs/2210.11934)
- [Score distribution models: assumptions, intuition, and robustness to score manipulation](https://dl.acm.org/doi/10.1145/1835449.1835491)
- [Classifier Calibration: A survey on how to assess and improve predicted class probabilities](https://arxiv.org/abs/2112.10327)
- [Query Performance Prediction for Neural IR: Are We There Yet?](https://arxiv.org/abs/2302.09947)

---

## 主要工具與技術

| Area | Technologies |
| --- | --- |
| **Languages** | Python · Elixir · TypeScript |
| **Backend & orchestration** | FastAPI · Pydantic · SQLAlchemy · Phoenix · Oban Pro |
| **Data & search** | PostgreSQL · Elasticsearch · OpenSearch |
| **Infrastructure** | AWS (ECS, S3, SQS) · Docker · GitHub Actions |
| **Python tooling** | asyncio · pytest |

[Full skills & technologies →](https://caleb-leung-kwan-ho.github.io/github-website/#skills)

---

## 聯絡

[LinkedIn](https://www.linkedin.com/in/caleb-kwan-ho-leung-a67b74168/) · [Email](mailto:caleb.leungkwanho@gmail.com)

<sub>Last updated: September 2026</sub>
