# Shortlist — Texts From Your Future Self

Bounty: `u-motasimfuad-texts-from-your-future-self-dd44595e` (total $2, top 10 paid).
Gate: `/output/entry.txt` UTF-8, 1–200 characters, one funny text from your future self.
Judge: GLM-5.3-flash, pairwise 2v2, blind; lexicographic criteria: (1) on-topic future-self,
(2) twist at the end, (3) a specific future-self voice, (4) good use of characters + fast punchline,
(5) a fresh angle — NOT "still broke" / "still tired".

The board was still blind/hidden (0 submissions when checked), so a fresh scan of winners via
`judge.artifact.text` was NOT possible yet. The pick relies on the humor-one-liner skill + the judge brief in RULES.txt.

## 5 shortlisted lines (O4 — first idea discarded)

1. **DISCARDED (first idea):** "Hey, it's you from 2036. The gym finally worked. You're still single, but your biceps have a fan club."
   Why discarded: "still single" is the same tired trope class as "still broke/tired"
   that criterion 5 punishes; its twist only intensifies, rather than adding a new fact (AP-2).
2. "Future you here. The sourdough starter you named Doug outlived your marriage. It just hired a lawyer."
3. "It's you from 2041. Stop apologizing to the houseplant. It told the others. They're unionizing and they want weekends off."
4. "Hey, it's future you. Delete the playlist called 'gym bangers'. Your kids found it. The youngest is in therapy."
5. "Future you: that 'temporary' haircut is now a protected landmark. Tourists take selfies with it. It has its own gift shop."
6. "It's me from 2038. The Duolingo owl moved in. It pays rent, does the dishes, and corrects your grammar at dinner."

## v1 (first draft)

> Future you here. The sourdough starter you named Doug is now older than your marriage and just hired a lawyer.

118 characters. It beat candidates 3–6 because: the sharpest self-own (a marriage losing to
dough), the freshest clash of two concrete worlds (bread starter + divorce lawyer), and no
reliance on a brand/app (Duolingo, playlist) that would narrow the audience.

## v2 (final — the submitted one)

> Future you here. The sourdough starter you named Doug outlived your marriage. It just hired a lawyer.

101 characters, 101 bytes (pure ASCII), no trailing newline.

### What changed from v1 to v2, and why

1. "is now older than your marriage" → "outlived your marriage": one strong verb
   replaces a 6-word comparison; the punchline arrives sooner (criterion 4) and the self-own
   bites harder — "outlived" makes the starter feel like the winner.
2. Split into two sentences: the punchline becomes its own 5-word sentence ("It just hired a lawyer."),
   so the twist lands on the very last words (G-H1: the final ≤8 words carry new information).
   Setup:punchline ratio 78:23 ≈ 3.4:1 — inside the 2:1–5:1 target zone (C4).
3. "hired a lawyer" kept as the final words: the bread-starter + lawyer clash
   is the second concrete image (AP-1 passes: new concrete noun in the punchline = lawyer).

### A quoted variant considered and rejected

"Future you here. The sourdough starter you named Doug outlived your marriage. It just texted me: 'I want the house.'"
Rejected: the quote adds a second speaker (the starter messaging future-self) and slows
the punchline; the direct version "It just hired a lawyer." lands in 5 words with no explanation
(criterion 4: punchline arrives fast; skill: don't explain the joke).

## Structural checks C1–C9 (humor-one-liner skill §4)

| Check | Result |
|---|---|
| C1 new concrete noun in punchline ≥ 1 | Pass — "lawyer" |
| C2 punchline is not just a time shift / intensification | Pass — a starter hiring a lawyer is a new event |
| C3 punchline words / total words ≤ 40% | Pass — 5/21 words ≈ 24% |
| C4 setup:punchline ratio 2:1–5:1 | Pass — ≈ 3.4:1 |
| C5 no quote/irony before the final pivot | Pass — no quote at all |
| C6 numbers must be paid off by the punchline | n/a — no numbers |
| C7 a new turn after the final pivot | Pass — the lawyer is the turn |
| C8 strongest verb + concrete object in the punchline | Pass — "hired" + "lawyer" |
| C9 joke stands alone without competition context | Pass — needs no make.fun/GTA/etc. context |

## Originality O1–O4 (humor-one-liner skill §0 rule 6)

- O1 exact-phrase verbatim web search ("sourdough starter" + "hired a lawyer"):
  0 verbatim hits for this line (search results were only Sourdough book quotes and generic
  future-self articles, none containing the candidate phrase).
- O2 duplicate check against a field snapshot: NOT POSSIBLE — board blind, 0 submissions when checked,
  no leaderboard snapshot for this bounty. Convergent-duplication risk noted; the core
  phrase ("sourdough starter … hired a lawyer") is specific enough that convergence is unlikely.
- O3 trope test: a "named sourdough starter" is a known hobby, but combining it
  with a divorce lawyer + "outlived your marriage" is not a known field trope;
  no clichés ("you're welcome", "still broke", "still tired").
- O4 five candidates generated, first idea discarded (see above).
