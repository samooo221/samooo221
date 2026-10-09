# Samuel Pavlovič

IT student at VUT FIT Brno. I build software by directing AI coding agents: I set the scope, review every step and tune their autonomy so the work stays sharp.

## What I build

- **Study tools for agents.** Claude Code skills that run exam drills, grade them hostilely and turn mistakes into flashcards only after I explain them myself.
- **Agent workflow tools.** A verification gate, a ladder of worker levels, and approvals that an agent cannot give itself.
- **Measured experiments.** I replay my own agent sessions and keep the result, including the ones that say "no gain".
- **Small tools and a game prototype.** A display font with a command that writes text to images. A game with 408 small rule specs (private).

## Featured work

| Repo | What it is |
|---|---|
| [sisyphus](https://github.com/samooo221/sisyphus) | A Claude Code plugin of 19 prose skills for exam drills and flashcards in Obsidian vaults. No app code. Sample course and drill transcript inside. |
| [bound-font](https://github.com/samooo221/bound-font) | Bound Inline Round: a display font with a groove carved through every stroke, plus `bound-write`, a command that writes text to PNG or SVG. |

Coming soon (not public yet):

- A Claude Code compaction add-on, extended from an MIT-licensed plugin, with my replay measurements.
- `forgeflow-workshop`: notes from directing a local open-weight model.
- `robot-print-shop`: safety rules enforced in code around agents that drive a 3D printer.

## How I work with AI agents

I write the specs, set the rules, read the reports and decide what ships. The agents write the code. I did not write it by hand.

Most of my repos are private, so I show the method and the numbers. Counts come from git history, logs and project notes (25 Jun to 9 Oct 2026). I did not re-run every test suite. Each idea has a limit.

- **Verification gate.** A full test run writes a green record tied to one commit and one clean tree. Landing is refused without it. Limit: the hook is not a sandbox.
- **Worker ladder.** Six written levels, from lead to second-opinion model, with a move-up rule after two failed tries. Limit: I cannot show the ladder caused the shift to cheaper workers.
- **Approvals an agent cannot give itself.** A decision closes only on my own typed reply. A worker report is data, never approval. Plain code does the matching, with no model. 23 real decisions, 138 automated tests.
- **Measure, then cut.** I replayed my own sessions through an open-source (MIT) compaction plugin. A small decision model chose no better than a free rule (24.2% vs 24.1% of characters removed), so I removed it. Limit: replays, not a controlled trial.

### What I do not claim

- I did not write the code by hand. I directed AI agents to build it.
- Counts show volume, not quality. I wrote down the gaps.
- Model reviewers are not human reviewers.

## Links

[LinkedIn](https://www.linkedin.com/in/samuel-pavlovi%C4%8D-3906b141b/) | [GitHub](https://github.com/samooo221)
