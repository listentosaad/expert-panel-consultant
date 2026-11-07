# Prior context, delivery, test instruments and follow-up

## Contents
1. Read prior context (Stage 0)
2. Choose the output format (after Stage 5)
3. Test instruments ("buy information first")
4. Watch list
5. Scheduled re-check

---

## 1. Read prior context (Stage 0)
Before scoping, read what already exists about this client or question:
- memory;
- project files;
- connected documents (Drive, Notion, OneDrive…);
- earlier conversations on the same subject.

Extract goals, decisions already taken, constraints and past numbers. Use them in three ways:
- Put them in the starting point and in the assumptions ("بناءً على قرار سابق: …").
- Do not ask the user for anything already found there.
- If a past decision conflicts with the new request, raise it in the question block. The user may have changed their mind, or the request may have missed it.

Cite the source of each prior fact (file name or "قرار سابق في محادثة بتاريخ …"), the same way as any other evidence.

## 2. Choose the output format (after Stage 5)
**Default:** the report as one document. Then offer, in one line, the other formats that fit the case, and build only what the user confirms. In Full auto mode, build the document and list the other formats as options. At D5 the artifact is part of the confirmed depth, so build it after the storyline is approved.

| Format | When it fits | How |
|---|---|---|
| Document | Default | One clean document (Stage 4 structure) |
| Deck | The reader must present it (board, investors, management), or D5 | Lock the storyline first: the governing message and one message per slide, approved by the user. Then build. |
| Spreadsheet model | The numbers will be reused, changed or audited | Export the Quant Analyst's model with live formulas: an inputs sheet (each input labelled with source or تقدير), a scenarios sheet, a sensitivity sheet and a sources sheet |
| Survey or interview guide | The verdict is "buy information first" | See §3 |
| Dashboard | The watch list will be tracked over time | Build from the watch list in §4 |

Rules:
- Use the session's artifact types or file skills, and read the relevant skill before building.
- Every format draws on the same model and ledger, so a number is identical in the document, the deck and the sheet.
- The clean-document rules (Stage 5, check 12) apply to every format.

## 3. Test instruments ("buy information first")
When the evidence ceiling forces "buy information first", the deliverable includes the instrument itself, not only the advice to run it. Each instrument names:
- the flip variable it settles;
- its cost and duration;
- the result that means go and the result that means stop. Each threshold has an origin (the user, derived from their numbers, or a linked benchmark), or is labelled "هدف داخلي مقترح".

| Instrument | Contents |
|---|---|
| Survey | Objective tied to a flip variable; target sample and how to reach it; a screening question; 8–12 questions in Arabic, neutral and not leading, asking about past behaviour before intentions; the answer pattern that means go or stop |
| Interview guide | Who and how many (profile); 6–8 open questions about what people actually did last time, not what they would do; what to listen for; how to record answers |
| Smoke test / landing page | The promise, the call to action, the traffic source, the success threshold and its origin, duration, cost |
| Pilot | Scope, duration, sample, the metric, success and stop thresholds, the decision date, who decides |

## 4. Watch list
Add it to the document when the recommendation is conditional. Heading: "ما يجب مراقبته".

| What to watch | Current value (label) | Flip point | Source to check (link) | How often |
|---|---|---|---|---|

Include:
- the decision-flipping variables from Stage 1.5 §6;
- the go/stop triggers from Stage 1.5 §7;
- external signals that could change the verdict:
  - regulation;
  - competitor launches and price changes, verified;
  - AI features in the category;
  - local data releases (statistics authority, sector regulators).

## 5. Scheduled re-check
If the session has a scheduled-task tool, offer once, in the conversation, to set up a re-check (monthly by default, or the user's choice). Create it only after the user agrees.

The task's prompt must stand on its own, because each run starts fresh. It contains:
- the decision sentence;
- the watch list with flip points and source links;
- the instruction to report only the items that moved, and whether the recommendation now flips.

Never say that monitoring is in place unless the task was actually created.
