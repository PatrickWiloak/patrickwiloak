# TODO

Working task list for **patrickwiloak**. Read this at the start of a work session and keep it current as work completes - check items off with a date, add follow-ups as they surface. Stale TODOs are worse than none. Security debt (if any) is tracked separately in `SECURITY-DEBT.md`.

---

## Open

### Cert counts (source of truth: LinkedIn Licenses & certifications)

As of 2026-10-18: **65 total** - AWS 15, GCP 3, Azure 2 (**20x multi-cloud**), Anthropic 19, Data/Search/Observability 14, AWS Partner 7, Other 5.

- [ ] **Retiring AWS certs - drop them from every count when they lapse.** These exams are being retired by AWS, so they cannot be renewed.
  - Dates below are from the **official AWS Certification account** (2026-10-18), which overrides LinkedIn for AWS expiry dates. LinkedIn is wrong for MLS (shows May 2029) and SOA (shows May 2028).
  - **AWS Certified Machine Learning - Specialty** - exam retired 2026-03-31 - expires **2026-10-21**. After: AWS 14, multi-cloud 19, total 64.
  - **AWS Certified Database - Specialty** - exam retired Apr 2024 - expires **2026-11-05**. After: AWS 13, multi-cloud 18, total 63.
  - **AWS Certified SysOps Administrator - Associate** - exam retired 2025-09-29 (renamed CloudOps Engineer - Associate, also held) - expires **2029-09-24**. After: AWS 12, multi-cloud 17, total 62.
  - Also fix the MLS and SOA expiry dates on LinkedIn.
  - Decide: SysOps and CloudOps are the same exam renamed, so "15x AWS" counts it twice while both are active. Keep or count once?
  - Places that state the counts: this repo's `README.md` (badges, About paragraph, AWS list, "All N certifications"), the GitHub profile bio ("20x multi-cloud"), `cloud-data-ai-security-zero-to-hero` (`README.md` x2, `learn/README.md`), plus portfolio and content repos (plw-portfolio, youtube-creator, strategic-writing, career). Grep for `20x`, `15x`, `65 ` before closing.

_Add items as `- [ ] task`, grouped by priority or theme. Mark done inline: `- [x] ~~task~~ ✅ done YYYY-MM-DD`._
