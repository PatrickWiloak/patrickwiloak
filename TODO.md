# TODO

Working task list for **patrickwiloak**. Read this at the start of a work session and keep it current as work completes - check items off with a date, add follow-ups as they surface. Stale TODOs are worse than none. Security debt (if any) is tracked separately in `SECURITY-DEBT.md`.

---

## Open

### Cert counts (source of truth: LinkedIn Licenses & certifications)

As of 2026-10-18: **65 total** - AWS 15, GCP 3, Azure 2 (**20x multi-cloud**), Anthropic 19, Data/Search/Observability 14, AWS Partner 7, Other 5.

- [ ] **Retiring AWS certs - drop them from every count when they lapse.** These exams are being retired by AWS, so they cannot be renewed.
  - **AWS Certified Database - Specialty** - exam retired Apr 2024 - expires **Nov 2026** (next to lapse).
  - **AWS Certified SysOps Administrator - Associate** - exam retired 2025-09-29 (renamed CloudOps Engineer - Associate, which is also held) - expires **May 2028**.
  - **AWS Certified Machine Learning - Specialty** - exam retired 2026-03-31 - LinkedIn says expires **May 2029**. Verify on Credly: AWS's page says retired certs stay active 3 years from the date earned (Oct 2023 -> Oct 2026); May 2029 may be an extension from GenAI Developer Pro.
  - Each lapse: AWS -1, multi-cloud -1, total -1. After all three: AWS 12, multi-cloud 17, total 62.
  - Decide: SysOps and CloudOps are the same exam renamed, so "15x AWS" counts it twice while both are active. Keep or count once?
  - Places that state the counts: this repo's `README.md` (badges, About paragraph, AWS list, "All N certifications"), the GitHub profile bio ("20x multi-cloud"), `cloud-data-ai-security-zero-to-hero` (`README.md` x2, `learn/README.md`), plus portfolio and content repos (plw-portfolio, youtube-creator, strategic-writing, career). Grep for `20x`, `15x`, `65 ` before closing.

_Add items as `- [ ] task`, grouped by priority or theme. Mark done inline: `- [x] ~~task~~ ✅ done YYYY-MM-DD`._
