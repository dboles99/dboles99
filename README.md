# Daniel Boles

Applied AI developer. LLM systems, agents, evaluation, language technology.

简体中文：应用型 AI 开发者，专注于大模型系统、智能体、评测与语言技术。

繁體中文：應用型 AI 開發者，專注於大型語言模型系統、代理、評測與語言技術。

## Selected work

| Project | What it is | Result |
| --- | --- | --- |
| [agent-gateway](https://github.com/dboles99/agent-gateway) | Admission control, budgets, watchdogs, and checkpoints for unattended coding agents | 241 tests passed, 1 skipped |
| [tm-rag-copilot](https://github.com/dboles99/tm-rag-copilot) | Retrieval-augmented translation over a synthetic translation memory, with deterministic QA | 40 of 41 segments passed QA with a local Qwen model, against 33 of 41 for retrieval alone |
| [docx-mcp](https://github.com/dboles99/docx-mcp) | Read-only MCP server that lets an agent read Word documents with tracked changes accepted | 67 tests passed; six tools, none of which can write |
| [rosetta-bench](https://github.com/dboles99/rosetta-bench) | Harness for comparing verbose and compact prompt formats across language-model tools | 38 tests passed; no model results published yet |
| [llm-watermark-lab](https://github.com/dboles99/llm-watermark-lab) | Research lab for measuring statistical watermarks in language-model text | A watermark kept a mean 88% of its clean score through print-scan-OCR in 4 of 4 scorable cells; not a calibrated claim |
| [pseudocode-ai-workflows](https://github.com/dboles99/pseudocode-ai-workflows) | Pseudocode specifications compiled to Python and PowerShell with contracts and a human approval gate | Eight defects found by execution and logged |
| [papers](https://github.com/dboles99/papers) | Four papers on pseudocode as a guardrail and on language-model text watermarks | A citation audit found 9 of 14 identifiers wrong in an earlier review |
| [bachelorpluslite](https://github.com/dboles99/bachelorpluslite) | A Rust text editor with Notepad's features and a local note layer that never touches the network | 1,104 test functions in the source; 94 recorded decisions |
| [bachelorpadplus_rust](https://github.com/dboles99/bachelorpadplus_rust) | The larger Rust text-processing application for Windows and Linux | 2,026 test functions in the source; 68 recorded decisions |
| [amplified-futures-vcv](https://github.com/dboles99/amplified-futures-vcv) | C++ DSP modules for VCV Rack 2 | Not measured |

## Method

The work proceeds through small experiments rather than large claims, because a change small enough to measure is also small enough to undo. Each one faces tests or an evaluation; what works stays, and what fails goes into the record with its numbers, since a negative result on paper saves more time than a success nobody measured. These repositories ask for that reading, limits included.
