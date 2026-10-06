# Creative Research

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

Investigate references, context, and creative possibilities across media.

Creative Research helps agents turn an open question into sourced findings, creative options, and an informed next step. It supports writing, visual art, design, film, animation, music, performance, games, and material practice.

## Capabilities

- Frame an inquiry around the decision a project needs to make.
- Select suitable methods for contextual, archival, audience, practitioner, or material research.
- Analyze references and identify principles that can be adapted to new work.
- Synthesize sources, observations, and interview material while preserving their context.
- Design experiments and prototypes that resolve an uncertainty or open a new possibility.
- Translate findings into creative decisions and a usable production handoff.

The guidance distinguishes documented evidence, interpretation, hypotheses, and speculation. Methods are selected for the inquiry, with room for artistic exploration and discoveries through making.

## Installation

Install with the [Skills CLI](https://github.com/vercel-labs/skills) using Node.js and npm:

```bash
npx skills add nonomnonom/creative-research
```

The CLI supports Claude Code, Codex, Cursor, OpenCode, and other agents listed in its documentation. Use `--agent` to select target agents and `--global` for a personal installation across projects.

For manual installation, clone or download the repository:

```bash
git clone https://github.com/nonomnonom/creative-research.git
```

Place the complete `creative-research` folder in the skills directory documented by your agent. Keep `SKILL.md` and `references/` together so the supporting guides remain accessible.

## Compatibility

The package uses the open [Agent Skills format](https://agentskills.io/specification). Its core instructions are Markdown with YAML metadata and have no model-provider dependency. `agents/openai.yaml` supplies optional interface metadata for hosts that use it.

Discovery, installation paths, and invocation syntax depend on the host. For an agent without native skill support, provide `SKILL.md` as instructions and make the referenced files accessible through its context or file tools.

## Usage

Ask your agent to use the creative-research skill with the question, project context, and available material. Specify whether you need findings, a research plan, or an experiment. If your host offers a skill picker or explicit invocation command, use its supported mechanism.

```text
Use the creative-research skill to investigate how objects prompt family memories
for an exhibition. Analyze these interview transcripts, show the basis
for your findings, and propose an interaction to explore next.
```

```text
Use the creative-research skill to plan an inquiry into rhythm and waiting
for a short animation. Recommend reference studies and timing experiments
before production begins.
```

Prompts and output can use the language of the project. In hosts that support automatic skill selection, the package can also be selected from its description.

## Reference library

| Guide | Focus |
| --- | --- |
| [Methods](references/methods.md) | Choosing research approaches and preparing an inquiry |
| [Evidence and context](references/evidence-and-context.md) | Source evaluation, provenance, cultural context, and participant material |
| [Synthesis and experiments](references/synthesis-and-experiments.md) | Developing findings, testing possibilities, and making decisions |
| [Media and handoff](references/media-and-handoff.md) | Adapting an inquiry to its medium and carrying findings into production |
| [Examples and review](references/examples-and-review.md) | Representative cases and checks for research delivery |

[SKILL.md](SKILL.md) contains the working instructions and routes to the references relevant to each task. The package works independently and can complement specialized writing or design skills.

## License

Original repository content is available under the [MIT License](LICENSE). Referenced publications, recordings, and other third-party materials retain their own rights and terms. Sources are linked from the relevant guides.
