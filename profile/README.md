# NoeticEcho

### Open systems for meaning, cognition and human–AI collaboration.

We build software in which meaning is a first-class object: a world you can
walk whose atmosphere is computed from what it means, agents (*iskins*) with
their own memory and voice, and a language (NSL) for describing both. Along
the way we open-source the tools we could not find.

> **Meaning should not disappear when software begins.**

## Open now

| Repository | What it is |
|---|---|
| [**TypedbEx**](https://github.com/NoeticEcho/TypedbEx) | An Elixir driver for TypeDB 3.x, over HTTP and gRPC, with lazy streaming on the BEAM. On Hex as [`typedb`](https://hexdocs.pm/typedb). |

## Coming next

| Project | What it will be |
|---|---|
| **control-room** | A protocol, prompts and scripts for one person running many AI coding agents in parallel through one coordinator, with a single desk for the decisions only the person can make. Works with Claude Code, Codex, e2b sandboxes or local worktrees. |
| **Agent memory on TypeDB** | A small semantic memory substrate for Elixir agents on TypedbEx: kinds of memory as types, events as relations, provenance and supersession as facts about facts. A foundation, not a framework. |
| **The development harness** | The engine that plans, gates and records the work of AI agents in our repositories: routing, gate lanes, a run ledger that runs its own checks, and regression environments derived from git history. We are deciding how to ship it: MCP server, Claude Code plugin, Hex package. |

## In development

**EchoBaby**, a walkable world of meaning. It is built in Elixir: Ash, Phoenix
and Jido, with TypeDB and Qdrant. A BabylonJS client renders it, with the
Observer seen from behind in a hooded cloak. Its first public milestone is a
site and a world that anonymous visitors can enter.

## How we work

1. **Models propose, validators decide, runtimes execute.**
2. **Meaning is kept apart from geometry, UI and rendering.**
3. **Everything generated carries its provenance.**
4. **Projections are views, never the source of truth.**
5. **The system represents what people express. It does not claim to know
   their inner state.**
6. **A specification is not proof that an implementation exists.** We say
   which is which.

## Links

- 🌐 https://noeticecho.space
- 👤 https://github.com/sudo-make-god

Technical questions go in the relevant repository's issues. Collaboration
goes through the website.
