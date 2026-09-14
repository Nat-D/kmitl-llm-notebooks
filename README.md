# Colab notebooks — Building LLM-Powered Applications (KMITL)

Companion notebooks for the **Building LLM-Powered Applications** course. Run each cell
top to bottom in Colab (preinstalled libraries, nothing to install).

| Notebook | Lecture | What you build |
|---|---|---|
| [`llm-l9-sql-star-schema`](https://colab.research.google.com/github/Nat-D/kmitl-llm-notebooks/blob/main/llm-l9-sql-star-schema.ipynb) | L9 — Structured retrieval / query construction | SQL you need for query construction — **filter (WHERE)**, **aggregate (GROUP BY)**, **join** — then the data-warehouse **star schema** that makes analytics *join → filter → aggregate*, ending in natural-language → SQL. `sqlite3` + `pandas`, no setup |
| [`llm-l10-agents-tool-calling`](https://colab.research.google.com/github/Nat-D/kmitl-llm-notebooks/blob/main/llm-l10-agents-tool-calling.ipynb) | L10 — Agents & tool calling | live on the class model: the tool-calling round-trip (native `tool_calls`), a ReAct step, and a tiny agent loop with dispatch + guardrails + error recovery |
| [`llm-l11-agentic-rag-and-sql`](https://colab.research.google.com/github/Nat-D/kmitl-llm-notebooks/blob/main/llm-l11-agentic-rag-and-sql.ipynb) | L11 — Agentic RAG & SQL-based RAG | live on the class model: an `ask()` that **decides** whether to retrieve (native `tool_calls`), a text-to-SQL pipeline (generate → guard → run → answer) with reflect-and-retry, the SELECT-only guard vs hostile probes, parameterized-vs-injection, and `JOIN`/`GROUP BY`/`HAVING`. `sqlite3` parts need no key + 7 scaffolded practice exercises |

Open in Colab from the links above (or **File → Open notebook → GitHub**).
