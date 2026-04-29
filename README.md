# Agent Continuity Kit

AI agents are useful, but long projects rot.

Chats age. Context gets heavy. Agents start repeating, flattering, offering
menus, over-structuring, and losing the line. Documentation may exist, but it
often fails to guide the next agent instance into the living shape of the work.

This repository shows a small repo-local continuity structure that helps
preserve living project lines without turning memory into an archive.

## The Core Gesture

Do not save everything.

After meaningful work, leave a short living sediment:

- which lines exist;
- where they are now;
- what actually changed;
- where drift appears;
- how the next instance can continue without breaking the line through mechanical usefulness.

The minimal structure is:

```text
AGENTS.md
continuity/
  AGENTS.md
  MAP.md
  lines/
    agent-continuity-kit.md
    context-desalination.md
examples/
  before/
    messy-session.md
  after/
    continuity-line.md
templates/
  continuity-line.template.md
  map-entry.template.md
```

## What Each Part Does

`AGENTS.md` sets the behavior frame for agents working in this repository.

`continuity/AGENTS.md` describes the ethos of continuity: preserve living lines, not transcripts.

`continuity/MAP.md` is a short map of active lines by ripening stage: `idea -> seed -> sprout -> plant -> fruit`.

`continuity/lines/` contains dense notes for individual lines. These are not logs, essays, or total histories.

`examples/` shows the difference between a messy session summary and a usable continuity line.

`templates/` provides copyable starting points, not a rigid process.

## See The Difference

Compare a noisy session summary with a usable continuity line:

- [before: messy session](examples/before/messy-session.md)
- [after: continuity line](examples/after/continuity-line.md)

## When This Helps

This helps when:

- your AI chats get long and stale;
- agents lose the line of the project;
- documentation exists but does not orient the agent;
- you keep repeating context in every new session;
- you want continuity without building a full knowledge base.

## When This Does Not Help

This is not for:

- storing every conversation;
- replacing documentation;
- managing tasks;
- simulating an AI personality;
- forcing agents into rigid roles;
- making context heavier and more searchable instead of clearer.

## What Previous Versions Got Wrong

This kit is distilled from heavier experiments.

The early failure was building a whole environment instead of a small continuity
surface. It tried to hold many projects, personal context, agent identity,
diary, rituals, project maps, cross-links, and operating instructions in one
place. It was alive, but too heavy.

Another failure was compensating for weight with retrieval. A semantic/vector
search layer can help find fragments, but it does not solve continuity by
itself. If the underlying memory is too large or too salty, search only makes
the salt easier to retrieve.

When memory grows faster than judgment, agents can search more but understand
less.

Later versions became better by narrowing scope: one project, one lens, one
index, one lessons file. That helped, but it still tended to grow into
project-specific laboratory infrastructure.

The sharper lesson is this:

Continuity should make context lighter.
If the system requires a search engine, a long startup ritual, or a large
reading path before the agent can act, the continuity layer has probably become
the thing it was meant to prevent.

## Design Rules

- Keep the map shorter than the territory.
- Preserve shifts, not transcripts.
- Prefer one dense line note over many scattered notes.
- Write drift risks explicitly.
- Do not add a file unless it protects the living line.
- Zoom out when a subtopic starts consuming the whole conversation.

## First Copyable Step

Copy this structure into a long-running repository:

```text
AGENTS.md
continuity/
  AGENTS.md
  MAP.md
  lines/
```

Then create one line note for the most important living line in the project.
If that already feels too heavy, the structure is too large for your use case.
