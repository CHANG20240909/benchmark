# AGENTS.md

## Cursor Cloud specific instructions

This is a **data-only benchmark repository** containing Korean cancer Q&A synthetic candidate answers for LLM evaluation. There is no application code, no build system, and no runtime dependencies.

### Repository contents

| File | Description |
|---|---|
| `synthetic_candidate_answers_by_score.json` | 26 items with synthetic answers graded by score band (0, 1-2, 3-4) |
| `synthetic_candidate_answers_with_reference.json` | Same 26 items merged with original reference answers |
| `synthetic_candidate_answers_summary.md` | Korean-language summary of data generation methodology |

### Development notes

- **No services to run.** There are no servers, databases, or containers.
- **No dependencies to install.** There is no `package.json`, `requirements.txt`, or any dependency manifest.
- **No build step.** The data files are consumed as-is by external evaluation pipelines.
- **Validation:** Use `python3` (pre-installed) to validate JSON schema and content integrity. Example: `python3 -c "import json; json.load(open('synthetic_candidate_answers_by_score.json'))"`.
- **Encoding caveat:** `reference_answer_ko` fields in `synthetic_candidate_answers_with_reference.json` contain encoding-damaged Korean text from the original source. This is expected and documented in `synthetic_candidate_answers_summary.md`.
