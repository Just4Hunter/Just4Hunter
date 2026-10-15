# Security Research | Bug Hunting | Tool Development

> Learn the attack surface. Understand the root cause. Build tools that solve real problems.

I'm an aspiring security researcher interested in web application security, bug hunting, and security automation. I use Python and Bash to explore ideas, automate repetitive workflows, and build practical security tools.

This repository serves as my personal space for documenting what I learn, experimenting with security concepts, and developing projects that demonstrate my technical skills.

## Focus

- Web application security and vulnerability research
- Bug bounty methodology and attack surface analysis
- Reconnaissance and security testing automation
- HTTP, APIs, authentication, and access control
- Python scripting and Bash automation
- Security tool development and technical documentation

## Projects

- **[sorx](https://github.com/Just4Hunter/sorx)** — A CORS misconfiguration scanner focused on identifying potential security findings.

  **Highlights**
  - **Signal over noise:** Focuses on potential findings rather than reporting every suspicious observation as a result.
  - **Controlled probing:** Aims to minimize redundant payloads while maintaining coverage of relevant test cases.
  - **Readable output:** Provides a clean, concise interface that presents relevant information without overwhelming the user.

  **Known Limitations**
  - **Early-stage maturity:** Functional for real-world testing, but not yet as reliable or polished as intended. Results should be manually validated.
  - **Inconsistent code structure:** Some parts of the codebase lack a consistent design, making maintenance and future development more difficult.
  - **False positives and false negatives:** Detection accuracy still needs improvement; findings may be incorrectly flagged, and some issues may go undetected.
  - **Overengineering:** Some implementation choices add complexity without consistently delivering the expected improvements in reliability or functionality.

*Status: No longer actively maintained. Use with caution and verify findings manually.*

## Areas of Interest

- Reconnaissance workflow automation
- HTTP request and response analysis
- Python utilities for security testing
- Bash scripts for repeatable research workflows
- Exploring Go and Rust for security tool development

## Learning Progress

My progress reflects topics I have studied or practiced, not necessarily areas in which I am proficient. My knowledge varies by subject, and I am continuing to strengthen my fundamentals through hands-on practice.

### Web Security & Bug Hunting

- [x] **HTTP, DNS, TCP/IP, and browser fundamentals** — Familiar with the basics; continuing to deepen my understanding.
- [x] **Common web vulnerabilities** — Understand common vulnerability types and their underlying concepts at a foundational level.
- [x] **Authentication and authorization** — Have practiced basic testing scenarios and am continuing to improve.
- [x] **Injection, SSRF, and business logic vulnerabilities** — Have studied the fundamentals and explored relevant testing techniques.
- [x] **Reconnaissance and attack surface mapping** — Familiar with common workflows and tools; continuing to improve methodology.
- [x] **Vulnerability validation, impact assessment, and reporting** — Understand the basic process and continue to develop practical skills.
- [x] **Public vulnerability disclosures and remediation** — Study real-world reports to understand root causes, exploitation conditions, and fixes.
- [x] **Practical Research Experience** — Reported a genuine vulnerability confirmed by a triager, but marked invalid due to internal scope restrictions.

### Python & Bash

- [x] **CLI scripting** — Can write scripts for practical tasks and continue improving code structure and usability.
- [x] **Error handling, logging, and input validation** — Understand the fundamentals and apply them where appropriate.
- [x] **Workflow automation** — Have experience automating repetitive tasks and refining the reliability of scripts.
- [x] **Testing and documentation** — Familiar with writing tests and documenting tools; continuing to improve consistency and coverage.
- [x] **HTTP clients and concurrency** — Have studied the basics and am continuing to explore their practical applications.

## Principles

- Understand before automating.
- Verify findings instead of blindly trusting scanner output.
- Prefer reproducible evidence over assumptions.
- Write tools that are focused, readable, and maintainable.
- Document limitations and avoid overstating results.
- Respect authorization, program scope, and testing limits.
- Keep learning through experimentation and review.

All security testing is intended for authorized environments, systems I own, or intentionally vulnerable labs.

## Contact

- GitHub: [@Just4Hunter](https://github.com/Just4Hunter)
