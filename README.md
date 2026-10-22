# ATP020 — Harbor

An Astrona **training path**: a course track that groups training series
(`ATSxxx`) as its domains. Each stage in `path.yaml` is one domain and points
at the repository that teaches it. There is no official Harbor certification
exam, so the domains and weights are Astrona's own and `examPreparation` is
off. Everything is written for Harbor 2.15 (2.15.4 in the labs) and the
Harbor CLI v0.0.27.

| Stage | Domain | Weight | Content | Status |
| --- | --- | --- | --- | --- |
| STG001 | Architecture, Installation & Harbor CLI Basics | 10 % | [ATS100](https://github.com/astrona-io/ATS100) | Draft, being written |
| STG002 | Project Management, RBAC & Multi-Tenancy | 20 % | [ATS101](https://github.com/astrona-io/ATS101) | Draft, being written |
| STG003 | Content Trust, Vulnerability Scanning & SBOMs | 25 % | [ATS102](https://github.com/astrona-io/ATS102) | Draft, being written |
| STG004 | Replication, P2P Preheating & Remote Registries | 15 % | [ATS103](https://github.com/astrona-io/ATS103) | Draft, being written |
| STG005 | Harbor CLI Automation, REST API & Webhooks | 15 % | [ATS104](https://github.com/astrona-io/ATS104) | Draft, being written |
| STG006 | Enterprise Operations, High Availability & Helm | 15 % | [ATS105](https://github.com/astrona-io/ATS105) | Draft, being written |

The site picks it up through [astrona-content](https://github.com/astrona-io/astrona-content):
a file in `courses/` that points at this repository, and the content sync
builds the course — one section per stage, with the readings, playgrounds and
labs each stage repository lists in its `astrona.yaml`. That course file does
not exist yet; add it when the first stage is ready to show.
