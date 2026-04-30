<div align="center">

# ChopLogic

**Personal blog, content backend, and tools for symbolic logic — from formulas to proofs.**

[Repositories](https://github.com/orgs/ChopLogic/repositories) · [Projects](https://github.com/orgs/ChopLogic/projects)

</div>

---

ChopLogic is a suite of projects for a **personal blog portal** and a **web application for constructing logical proofs** and working with **symbolic logic** (propositional logic, proof systems, and related tooling). This organization hosts the apps, shared libraries, and infrastructure that power that experience.

## Repositories

| Repository | Role |
|------------|------|
| [**chop-logic-portal**](https://github.com/ChopLogic/chop-logic-portal) | Front-facing site — Astro-based portal (blog, MDX, RSS, sitemap); consumes the CMS via GraphQL and shared UI packages. |
| [**chop-logic-cms**](https://github.com/ChopLogic/chop-logic-cms) | Content backend — Strapi CMS for the Chop Logic Portal (GraphQL, users & permissions, cloud plugin). |
| [**chop-logic-core**](https://github.com/ChopLogic/chop-logic-core) | Logic engine — TypeScript library for evaluating formulas and building proofs (published to npm). |
| [**chop-logic-components**](https://github.com/ChopLogic/chop-logic-components) | UI kit — reusable React components and hooks for Chop Logic apps (published to npm; Storybook docs). |

## Packages on npm

Shared libraries used across apps and available to the wider ecosystem:

| Package | Version | Description |
|---------|---------|-------------|
| [`chop-logic-core`](https://www.npmjs.com/package/chop-logic-core) | [![npm](https://img.shields.io/npm/v/chop-logic-core?label=)](https://www.npmjs.com/package/chop-logic-core) | Core types and algorithms for logical formulas and proofs. [Docs](https://choplogic.github.io/chop-logic-core) |
| [`chop-logic-components`](https://www.npmjs.com/package/chop-logic-components) | [![npm](https://img.shields.io/npm/v/chop-logic-components?label=)](https://www.npmjs.com/package/chop-logic-components) | React components and hooks for the Chop Logic UI layer. [Docs](https://choplogic.github.io/chop-logic-components) |

## Stack

- **Portal:** Astro, React, GraphQL (`graphql-request`), Zod  
- **CMS:** Strapi 5, GraphQL, SQLite (`better-sqlite3`)  
- **Libraries:** TypeScript, Vitest / Jest, Biome, published ESM/CJS where applicable  

## Contributing

Issues and pull requests are welcome in each repository. Use the linked **Issues** tab on the repo you care about; published packages also list bug trackers on their npm pages.

---

<div align="center">

<sub>MIT-licensed projects · Dmitrii Suroviagin</sub>

</div>


