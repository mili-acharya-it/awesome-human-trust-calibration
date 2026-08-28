
# Tools and Libraries

The following tools were selected for their usefulness in building, evaluating, or verifying human-agent research systems.

## 1. LlamaIndex

**Purpose:** Framework for building agentic applications around documents, retrieval, indexing, and RAG workflows.

**Why relevant:** Autonomous research agents need to ingest papers, retrieve evidence, maintain source context, and connect generated claims to documents.

**Official project:** https://github.com/run-llama/llama_index

**License:** MIT.

## 2. LangGraph

**Purpose:** Low-level orchestration framework for building stateful, long-running agents and multi-agent workflows.

**Why relevant:** Research agents often require explicit workflow state, checkpoints, human-in-the-loop intervention, and controlled transitions between research stages.

**Official project:** https://github.com/langchain-ai/langgraph

**License:** See the repository license.

## 3. DSPy

**Purpose:** Framework for programming and optimizing language-model pipelines rather than relying only on manually written prompts.

**Why relevant:** Useful for building repeatable research-agent pipelines and optimizing multi-stage LLM programs.

**Official project:** https://github.com/stanfordnlp/dspy

**License:** MIT.

## 4. Microsoft Agent Framework

**Purpose:** Open framework for building, orchestrating, and deploying single-agent and multi-agent workflows in Python and .NET.

**Why relevant:** Provides workflow orchestration, human-in-the-loop patterns, observability, and multi-agent collaboration capabilities relevant to autonomous research.

**Official project:** https://github.com/microsoft/agent-framework

**License:** MIT.

## 5. Semantic Scholar Academic Graph API

**Purpose:** Scholarly search and metadata API for papers, authors, citations, and venues.

**Why relevant:** Useful for discovering candidate papers and checking bibliographic information during citation verification.

**Official resource:** https://www.semanticscholar.org/product/api

**Important:** Semantic Scholar is a discovery/verification aid; the final verification should still compare the record with a publisher, DOI, or other authoritative source where appropriate.

## 6. OpenAlex

**Purpose:** Open catalog and API covering scholarly works, authors, sources, institutions, and topics.

**Why relevant:** Useful for cross-checking paper metadata, publication years, venues, authors, and scholarly relationships.

**Official resource:** https://developers.openalex.org/

## 7. Crossref REST API

**Purpose:** Search and retrieve deposited scholarly metadata, including DOI records.

**Why relevant:** Particularly useful for verifying whether a DOI corresponds to the title, authors, venue, and year claimed by an AI-generated reference.

**Official resource:** https://www.crossref.org/documentation/retrieve-metadata/rest-api/

## Tool Selection Note

The tools are not all interchangeable. Agent frameworks support implementation; scholarly APIs support discovery and verification. For citation auditing, authoritative metadata sources should be treated as evidence rather than relying on an AI chatbot's assertion that a reference exists.
