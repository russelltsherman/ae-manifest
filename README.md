# ae-manifest

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

A typed, queryable, JSON-backed coordination object for multi-agent work.

Manifest is a **binder, not a container.** It holds the coordination metadata around a unit of work and *references* — with typed, role-labeled links — the tasks, knowledge records, prompts, agent runs, and PRs that constitute its substance. 
Code lives in git. Issues live in tasks. Expertise lives in knowledge. Manifest makes them legible together.

A Manifest is the place where intent meets execution: humans author it, agents query it, runs dispatch from it and report back to it, and external sources hang off it as typed attachments.

## Where Manifest fits in os-eco

| Tool         | Unit             | Role                                  |
|--------------|------------------|---------------------------------------|
| Task         | Issue            | "This needs doing"                    |
| Knowledge    | Expertise record | "This is what we know"                |
| Prompt       | Prompt template  | "This is how we ask"                  |
| **Manifest** | **Coordination object** | **"This is what's happening on X right now, and who/what is involved"** |

Manifest is the substrate that other os-eco tools sit on top of to coordinate multi-agent work around a unit of work.
