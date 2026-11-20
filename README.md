# Brain Skills — six practical specialists

Open, portable skills for AI agents, based on the six Brain specialist profiles. Each skill is a standalone SKILL.md following the [Agent Skills format](https://agentskills.io/specification). They can be installed individually or used together.

## The six skills

| Skill | Use it for |
|---|---|
| brain-strategy | Product direction, audience, offer, business goals and conversion paths |
| brain-design | UX/UI, accessibility, visual consistency and interaction design |
| brain-engineering | Architecture, implementation, integrations, performance and secure development |
| brain-visibility | Technical/local SEO, content structure, GEO/AEO and measurement |
| brain-compliance | Jurisdiction-aware compliance issue spotting and evidence gathering |
| brain-audit | Release review, evidence, risk prioritization and verification status |

## Install

### Claude Code

In Claude Code (terminal, desktop, or IDE), paste these commands one at a time. The first adds this GitHub marketplace; the second opens the install flow for the plugin containing all six skills.

~~~text
/plugin marketplace add LouDbsss/brain-skills
/plugin install brain-skills@brain-skills
~~~

After installation, run a skill with one of these names: /brain-skills:brain-strategy, /brain-skills:brain-design, /brain-skills:brain-engineering, /brain-skills:brain-visibility, /brain-skills:brain-compliance, or /brain-skills:brain-audit.

This installation route is for Claude Code. In Claude's regular web chat, a GitHub link alone does not install a skill; use Claude's Skills settings to add it to your account.

### Other compatible agents

Download a skill folder from the skills directory or copy it to the skills directory supported by your agent. A skill provides instructions; it does not grant access to tools, files, accounts, networks, or private data.

## Use together

Start with Strategy when the goal is unclear; involve Design for user-facing experience, Engineering for implementation, Visibility for discoverability, Compliance for applicable obligations, and Audit before release. Use only the specialists relevant to the task. They are independent skills, not autonomous agents, and do not call one another automatically.

## Scope and evidence

These skills contain reusable methods, not the private Obsidian vault, client records, credentials, Brain SaaS source code, or proprietary knowledge documents. They do not claim that checks were run. Agents should distinguish verified evidence from assumptions and unknowns. Compliance guidance is issue spotting, not legal advice or certification; SEO/GEO outcomes are never guaranteed.

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md). Please include sources for factual additions and never contribute private vault content, client data, credentials, or unlicensed material.

## License

This package is licensed under MIT. See [LICENSE](LICENSE).

---

# Brain Skills — six spécialistes pratiques

Skills ouverts et portables pour agents IA, dérivés des six profils Brain. Chaque compétence est un fichier SKILL.md autonome au format [Agent Skills](https://agentskills.io/specification).

## Installation dans Claude Code

Dans Claude Code (terminal, application ou IDE), colle ces commandes une par une. La première ajoute cette marketplace GitHub ; la seconde ouvre l’installation du plugin avec les six skills.

~~~text
/plugin marketplace add LouDbsss/brain-skills
/plugin install brain-skills@brain-skills
~~~

Dans la conversation Claude classique, un lien GitHub seul n’installe pas de skill. Il faut passer par les réglages Skills de Claude.

Les six skills sont aussi utilisables dans les autres agents compatibles avec le format Agent Skills. Le dépôt ne contient ni le coffre Obsidian privé, ni les données client, ni les identifiants, ni le code SaaS Brain.
