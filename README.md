# Brain Skills — six practical specialists

Open, portable skills for AI agents, based on the six Brain specialist profiles. Each skill is a standalone `SKILL.md` following the [Agent Skills format](https://agentskills.io/specification). They can be installed individually or used together.

## The six skills

| Skill | Use it for |
|---|---|
| `brain-strategy` | Product direction, audience, offer, business goals and conversion paths |
| `brain-design` | UX/UI, accessibility, visual consistency and interaction design |
| `brain-engineering` | Architecture, implementation, integrations, performance and secure development |
| `brain-visibility` | Technical/local SEO, content structure, GEO/AEO and measurement |
| `brain-compliance` | Jurisdiction-aware compliance issue spotting and evidence gathering |
| `brain-audit` | Release review, evidence, risk prioritization and verification status |

## Install

Copy any skill folder into the skills directory supported by your agent. For example, Codex and Claude Code can discover repository skills under `.agents/skills/` and `.claude/skills/` respectively. Check your agent's current documentation for its supported install path.

To try all six in this repository, copy `skills/*` to your agent's project skills directory. A skill provides instructions; it does not grant access to tools, files, accounts, networks, or private data.

## Publish as a separate public repository

This folder is deliberately self-contained inside a larger private project. To publish only the skills, create an empty public repository on your Git host, then copy the **contents of `brain-skills/`** into a clean local clone of that new repository, review the files, and push that repository. Do not make the parent SaaS project public just to publish this package. Choose a repository name such as `brain-skills` and add its final URL here after publication.

## Use together

Start with Strategy when the goal is unclear; involve Design for user-facing experience, Engineering for implementation, Visibility for discoverability, Compliance for applicable obligations, and Audit before release. Use only the specialists relevant to the task. They are independent skills, not autonomous agents, and do not call one another automatically.

## Scope and evidence

These skills contain reusable methods, not the private Obsidian vault, client records, credentials, Brain SaaS source code, or proprietary knowledge documents. They do not claim that checks were run. Agents should distinguish verified evidence from assumptions and unknowns. Compliance guidance is issue spotting, not legal advice or certification; SEO/GEO outcomes are never guaranteed.

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md). Please include sources for factual additions and never contribute private vault content, client data, credentials, or unlicensed material.

## License

The files in this `brain-skills` package are licensed under MIT. See [LICENSE](LICENSE).

---

# Brain Skills — six spécialistes pratiques

Skills ouverts et portables pour agents IA, dérivés des six profils spécialisés Brain. Chaque compétence est autonome et suit le format [Agent Skills](https://agentskills.io/specification). Elles s'installent séparément et peuvent être combinées.

Le paquet ne contient ni le coffre Obsidian privé, ni données client, identifiants, code SaaS Brain ou documents de connaissances propriétaires. Les skills donnent des consignes, pas des permissions ou des outils. Ils distinguent les preuves des hypothèses et ne prétendent pas avoir exécuté de vérifications.
