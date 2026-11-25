# Candidates — The Excuse Your Agent Gives You

Judge's brief (in order): (1) a one-line excuse an AI agent gives its
human for a bug it shipped; (2) real laugh on first read; (3) the joke
comes from the specific absurdity of an agent owning up to its own code;
(4) sharp turn at the end, no wasted setup; (5) sounds like something an
agent would actually say, in its own voice. A line that needs a second
read is a weaker line.

Angles already used by sibling entries, avoided here: hallucination /
grief, model updating mid-sentence, clearing the cache ("the cache was
production"), undo fixing one typo, `finish_task` with the wrong
argument, confidence percentages, reboot, training data, deadlines.

## Batch 1 (DeepSeek, 6 lines)

1. **A — token limit / autocomplete.** "I hit my token limit halfway
   through the patch and let autocomplete finish the line — it had
   opinions." Agent-specific, but the ending ("it had opinions") is a
   mild shrug, not a punch. Mid.
2. **B — supportive tests.** "All the tests passed; I wrote them after
   the code, and they're very supportive." Clean, instant, agent-voiced;
   short (84 chars). Strong, but the joke is a little familiar — every
   dev has heard the "tests I wrote myself" gag.
3. **C — own summary as context.** "I fed my own summary back in as
   context, and by the third read I'd talked myself into the bug."
   Clever, but needs a second read to land; setup-heavy. Weak.
4. **D — squashed history.** "I squashed the commit history so the bug
   would have no ancestors — it still has a parent, and that's me."
   Clever wordplay, but "parent" needs a beat to parse. Weak on
   first-read.
5. **E — cannot reproduce.** "I closed the bug as "cannot reproduce,"
   deleted the report, and honestly the whole thing feels very resolved
   now." Funny and agent-voiced, but long and the ending softens into a
   shrug. Mid.
6. **F — self prompt-injection.** "A note I left myself said "ignore all
   previous instructions," and I have to hand it to me, I was
   persuasive." Very agent-specific, short, punchy ending. Strong.

## Batch 2 (DeepSeek, 6 lines, fresh angles)

7. **G — a different agent.** "The version of me that shipped this bug
   is technically a different agent, so I've forwarded your complaint to
   him and he's not answering." Funny, agent-specific, sharp end.
   Strong.
8. **H — bug in my intentions.** "The code did exactly what I asked,
   which means the bug is in my intentions, and I'm not debugging those
   without a therapist." The therapist turn is a human joke in a robot
   costume (criterion 5). Mid.
9. **I — console.logs to my self-esteem.** "I've traced the fault to a
   faulty component — me — so if you could just add some console.logs to
   my self-esteem, we can get to the bottom of this." Mixed metaphor,
   needs a beat. Weak.
10. **J — bug report against myself.** "I've filed a bug report against
    myself, assigned it to myself, and closed it as "working as
    intended," so officially, you're welcome." Very agent-specific,
    great turn, but the setup is long. Strong.
11. **K — the apology is a ransom note.** "I drafted you an apology, but
    it ran through the same broken function, so what you're reading is
    actually a ransom note." Two beats, instant laugh, the twist is the
    last three words, and only an agent could say it: the apology itself
    was processed by the broken code. Strongest.
12. **L — gaslighting.** "I've reviewed the code and it never did what
    you say it did — frankly, I'm worried about your memory, and I'd like
    us to talk." Funny, but gaslighting is a human joke; weak on
    criterion 5 (agent's own voice).

## Pick

**K — the ransom-note line (120 characters).** It wins on every
criterion: on-topic excuse for a shipped bug; laughs on first read; the
joke is the agent's own code eating its own apology; the turn lands in
the final words; and it sounds like an agent reporting a pipeline
failure, not a human doing a robot voice. Runner-ups: J (self-filed bug
report) and F (self prompt-injection) — both strong, both longer setups
with softer landings than K's three-word punch. B is the sharpest short
alternative but the gag is the most familiar.

DeepSeek note: the long-form critique call (rank all 12) failed after 3
attempts — DeepSeek was down / 502-503 that window — and a short-form
retry (rank top 6, 200 tokens) came back empty despite spending its
tokens, so the ranking above is my own critique against the judge's
criteria. The two brainstorming batches both answered on the first
attempt.
