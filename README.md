# Engineering Leadership Prompt Library

A structured set of AI prompts for engineering leaders navigating new roles, setting strategy, and driving organizational focus. Built on a synthesis of Theory of Constraints, the WRAP decision framework, and Camp's negotiation principles.

Created by [Rich Wasserman](https://www.randomwalkthroughtech.com/) — writing about engineering leadership from 20+ years at Amazon, IMDb, Convoy, Meta, and Stitch Fix.

## Who This Is For

Engineering managers, directors, and VPs who need to:
- Articulate a clear vision for their org
- Find the constraint that's actually blocking progress
- Set OKRs based on controllable inputs, not hoped-for outputs
- Ruthlessly prioritize to 1-3 real bets
- Draft tenets that enable team autonomy
- Make visible where engineering time actually goes

## The Dependency Graph

These prompts follow a specific order. Each stage's output feeds the next. The whole sequence is a cycle — when you fix a constraint, a new one emerges, and you come back to Stage 2.

```
1. Vision Excavator    → What does success look like?
2. Constraint Finder   → What's actually blocking that vision?
3. OKR Drafter         → What controllable inputs move the constraint?
4. Prioritization      → Which 1-3 bets matter most?
5. Tenet Sharpener     → What decision principles enable autonomy?
6. Work Histogram      → Where is time actually going?
       ↓
   [Constraint shifts → back to Stage 2]
```

## How to Use

1. Copy the full text of `01-vision-excavator.md` and paste it as your first message in a new [Claude](https://claude.ai) or [ChatGPT](https://chat.openai.com) conversation.
2. The AI will ask you questions. Answer honestly with your real situation — raw notes, half-formed thoughts, messy observations. Don't try to be polished.
3. Work through the conversation until you have output you're satisfied with. Save it.
4. Move to the next prompt. Paste your output from the previous stage when asked.

**Which AI to use:**
- **ChatGPT Enterprise**: When you need to reference or upload confidential work files (org charts, reviews, team data).
- **Claude**: For general framework thinking, drafting, and iteration.
- Both work equally well with these prompts.

**Tips:**
- If the AI starts giving advice instead of asking questions, tell it: "Stop advising. Ask me a question instead."
- The best outputs come from 4-5+ rounds of back-and-forth, not the first draft.
- Every output includes a tripwire — a specific signal that tells you to revisit the decision. Set these seriously.

## The Frameworks

These prompts synthesize four bodies of work:

- **Theory of Constraints (Goldratt)**: Every system has one constraint limiting throughput. Find it. Exploit it. Subordinate everything else. Improving a non-bottleneck is an illusion of progress.
- **WRAP (Heath brothers, *Decisive*)**: Widen options, Reality-test assumptions, Attain distance before deciding, Prepare to be wrong. Tripwires over autopilot.
- **Start with No (Jim Camp)**: Frame problems in others' pain. Ask, don't tell. "You cannot tell anyone anything — you can only help people see for themselves."
- **Amazon Operating Mechanisms**: Controllable inputs over output metrics, tenets for autonomous decision-making, mechanisms over good intentions, disagree and commit.

## Related Writing

These prompts are companions to articles at [A Random Walk Through Tech](https://www.randomwalkthroughtech.com/):

- [Everything You Wanted to Know About Goals](https://www.randomwalkthroughtech.com/p/everything-you-wanted-to-know-about) — Vision, Objectives, and Key Results
- [The 80/20 of Getting Stuff Done](https://www.randomwalkthroughtech.com/p/the-8020-of-getting-stuff-done) — Finding and exploiting constraints
- [Tenets](https://www.randomwalkthroughtech.com/p/tenets) — Decision principles for autonomous teams
- [Priorities for Prioritizing Prioritization](https://www.randomwalkthroughtech.com/p/priorities-for-prioritizing-prioritization) — The gold standard prioritization test
- [A Work Visibility Tracking Framework](https://www.randomwalkthroughtech.com/p/a-work-visibility-tracking-framework) — The six-bucket work histogram
- [All Agile Is Not Created Equal](https://www.randomwalkthroughtech.com/p/all-agile-is-not-created-equal) — Why Kanban beats Scrum for flow
- [Meditations on Tech Debt](https://www.randomwalkthroughtech.com/p/mediations-on-tech-debt) — Framing debt as throughput, not moral failing
- [The Agreeable Compromise Trap](https://www.randomwalkthroughtech.com/p/the-agreeable-compromise-trap) — Why splitting the difference makes everyone worse off

## Contributing

This is a curated prompt library. I'm not accepting pull requests at this time, but feedback and suggestions are welcome via [Issues](../../issues). If you use these prompts and have observations about what works or doesn't, I'd love to hear about it.

## License

This work is licensed under [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/). You are free to share and adapt with attribution for non-commercial purposes.
