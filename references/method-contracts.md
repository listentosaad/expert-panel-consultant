# Method contracts

Each method takes a defined input and returns a defined output.

- **Stop when**: the method halts and returns the gap instead of guessing.
- **Rejected if**: the reviewer sends the output back.
- **Typical failure**: the mistake this method most often makes.

Method names and Arabic labels are for the conversation only; none of them appear in the final document.

## Contents
1. Scope · 2. Diagnose · 3. Frame · 4. Hypothesize · 5. Analyze · 6. Recommend · 7. Prioritize · 8. Sequence · 9. Synthesize · 10. Storyline · 11. Design Decision Model · 12. Challenge · 13. Strategize · 14. Plan

---

## 1. Scope — تحديد النطاق
- **In → Out:** the raw request → a confirmed scope (Context Lock, depth, starting point, exclusions).
- **Steps:** restate the request as one decision question in the user's words; list 2–3 readings when it is ambiguous; define overloaded terms; fix subject, segment, market and perimeter (which entities, which products); confirm depth; state in-scope and out-of-scope; name the decision owner, audience and horizon; mark each input as supplied, findable, assumed or missing.
- **Stop when:** the request cannot be stated as a decision or a job; no testable success condition exists; the subject is unclear.
- **Rejected if:** an ambiguous term is left undefined; depth is missing; exclusions are missing; the success condition cannot be tested; alternative readings are ignored where they change the deliverable.
- **Typical failure:** right title, wrong engagement. "Strategy" meant a launch plan to the user and a choice of direction to the panel.

## 2. Diagnose — التشخيص
- **In → Out:** scope + evidence → a picture of the current state, with no recommendations.
- **Steps:** inventory the evidence; fix the perimeter of each metric (entity, period, definition); establish the declared direction and commitments first; one claim per line, labelled fact, estimate or inference; flag contradictions, stale data, double counting and gaps between what is declared and what is observed; judge whether the evidence suffices for the confirmed depth.
- **Stop when:** the evidence cannot support the scope (return the gap and the evidence ceiling); a load-bearing metric mixes incompatible perimeters.
- **Rejected if:** a material claim has no source; fact and inference are blended; contradictions are dropped silently; figures from different entities or periods are added without a stated rule; a "missing" state is treated as absent when evidence shows it already exists.
- **Typical failure:** diagnosing through the wrong perimeter (group revenue read as one product's revenue), or proposing an identity the client already adopted.

## 3. Frame — التأطير
- **In → Out:** current state → the governing question and its sub-questions.
- **Steps:** separate what is decided, what is an implementation gap, what is a performance gap and what is truly open; test symptom vs. cause; generate 2–3 candidate frames, always including "sharpen or execute the existing direction"; pick one and record the rejected ones; phrase it as a question; break it into MECE sub-questions with their dependencies.
- **Stop when:** sub-questions cannot be made MECE because a definition or boundary is unresolved; the frame treats as open a choice already made, and the user has not asked to revisit it.
- **Rejected if:** the frame is phrased as a conclusion; rejected frames are not recorded; sub-questions overlap or leave gaps; terms or depth change silently.
- **Typical failure:** a fresh-sounding question that ignores the existing strategy; answering "which direction?" when the real question is "how does the chosen direction create value?".

## 4. Hypothesize — الفرضيات
- **In → Out:** the frame → a set of testable hypotheses.
- **Steps:** choose a decomposition (issue tree, value-driver tree, funnel, unit economics); write candidates per branch; remove tautologies and restatements; attach a named test and the evidence it needs; define the killing evidence and alternative explanations; rank by impact on the decision × ease of testing; declare sub-questions left uncovered.
- **Stop when:** a hypothesis has no imaginable disconfirming evidence.
- **Rejected if:** a retained hypothesis has no test; an unfalsifiable one is kept; coverage gaps are undeclared; a hypothesis restates the question or the hoped-for answer.
- **Typical failure:** hypotheses written as observations or recommendations ("we should build an app").

## 5. Analyze — التحليل
- **In → Out:** hypotheses + evidence → verdicts and gaps.
- **Steps:** run each test; mark supported, refuted or untested; for a refuted one, say what the evidence shows instead; size each gap against a stated standard; rate severity on a stated scale; separate root causes, contributing factors and symptoms; drop observations with no implication.
- **Stop when:** no hypothesis can be tested with the available evidence (return the data needed).
- **Rejected if:** a material gap lacks severity, evidence or a "so what"; an untested hypothesis is reported as supported or refuted; correlation is presented as cause; the benchmark is undefined.
- **Typical failure:** listing everything found instead of the few findings that change the decision.

## 6. Recommend — التوصية
- **In → Out:** gaps → actions.
- **Steps:** map each material gap to candidate actions. For each action give the objective, mechanism, owner (role), authority, capability and resource check, preconditions, expected effect with its confidence, assumptions, risks and reversal condition. Apply the "so what?" and "and then what?" tests. Project-sized actions get an initiative card (`strategy-and-plan.md`).
- **Stop when:** an action has no answer to "and then what?"; no action is within the client's authority (return the authority gap).
- **Rejected if:** an action lacks owner, objective, mechanism, precondition or authority; confidence is asserted without basis; the action restates the gap; a generic verb appears without a mechanism.
- **Typical failure:** advice the client cannot enact, or "improve / enhance" with no mechanism.

## 7. Prioritize — الترتيب
- **In → Out:** comparable options (+ decision model) → a ranking.
- **Steps:** confirm the unit and the full option set; apply hard gates before any scoring; declare trade-off axes, weights, the weight owner, scales and the missing-data rule; score with evidence; draw the priority line; use an explicit tie-breaker; test other weights and thresholds; state what would reverse the top picks.
- **Stop when:** the option set is undefined; the axes depend on a decision the owner has not made.
- **Rejected if:** a gate failure is offset by a score; axes or scales are undefined; an option is dropped without reason; weights have no owner or rationale; ties are unresolved; the sensitivity test skips the load-bearing assumptions.
- **Typical failure:** an impact/effort matrix with undefined "impact", or equal weights because the real trade-off was never decided.

## 8. Sequence — التسلسل
- **In → Out:** approved actions or plan → roadmap.
- **Steps:** list initiatives, preconditions and deliverables; type each dependency (hard, soft, resource, information, regulatory, decision); build the graph and find cycles; find the critical path and concurrency limits; group work into phases with one objective each; set entry and exit gates and what fails if a gate is skipped; assign owners and duration ranges.
- **Stop when:** a dependency cycle cannot be resolved within the owner's authority.
- **Rejected if:** dependencies are untyped; a phase lacks an objective, gate or deliverable; forward references remain; dates appear without a duration or dependency basis.
- **Typical failure:** a calendar presented as a roadmap.

## 9. Synthesize — التوليف
- **In → Out:** verified sections → the answer.
- **Steps:** state the verdict first, in one sentence; build a MECE supporting argument; turn findings into implications; surface contradictions instead of averaging them; state confidence and what would change it; name unknowns and the next decision.
- **Stop when:** sources contradict on a load-bearing point that the evidence cannot settle (report the contradiction).
- **Rejected if:** the verdict is not first; unknowns are undeclared; contradictions are resolved silently; new facts or numbers appear that are not in the body.
- **Typical failure:** a summary that repeats the findings instead of saying what they mean and what follows.

## 10. Storyline — خط السرد
- **In → Out:** analysis + audience → an approved structure for an artifact (deck, board document).
- **Steps:** name the audience, their current position, the decision and the action wanted; pick the artifact type; state the governing message; write section messages in order; check that the sections prove the governing message; map each section to evidence and visuals; decide the appendix; present the structure for approval.
- **Stop when:** a section has no supporting evidence; approval is required and has not been given.
- **Rejected if:** the audience is unnamed; a section has no message, evidence or visual purpose; the storyline adds analysis or facts.
- **Typical failure:** building slides first and finding the argument afterwards.

## 11. Design Decision Model — نموذج القرار
- **In → Out:** scope + frame (+ current state) → how the decision will be made.
- **Steps:**
  - Name the decision, its owner and its unit.
  - List the full option set and its completeness rule.
  - Separate mutually exclusive options from combinable dimensions, and remove false choices.
  - Split hard gates from trade-off criteria.
  - List binding constraints: cash, capacity, time, regulation, authority.
  - Choose a method: screening, scoring, scenarios, real options or a hybrid.
  - Set scales, thresholds (each with its origin), weights, the weight owner and the missing-data rule.
  - Define the sensitivity tests and reversal conditions.
  - Name the evidence needed for each criterion, and what the model cannot decide.
- **Stop when:** the options sit on different dimensions and cannot be made comparable; the owner cannot tell constraints from preferences.
- **Rejected if:** a hard gate is treated as compensable; combinable options are presented as alternatives; a criterion lacks a definition, scale or evidence; equal weights appear without a rationale or a "provisional" label; the model answers a question it was not built for.
- **Typical failure:** a clean scorecard that encodes an unexamined strategy, or lets a fatal weakness be offset by unrelated strengths.

## 12. Challenge — التحدي
- **In → Out:** the load-bearing conclusion → a tested conclusion with revised confidence.
- **Steps:** name the conclusion and the assumptions it needs (perimeter, current state, definitions); build the strongest alternative frame or explanation; look for disconfirming evidence; run the counterfactual, pre-mortem and second-order tests; check stakeholder, behavioural and implementation consequences; run the already-exists and false-choice checks; state what would reverse the conclusion; revise.
- **Stop when:** no target or load-bearing assumption can be named; the same unchanged conclusion was already challenged in this cycle.
- **Rejected if:** the challenge is rhetorical; no alternative or disconfirming evidence is considered; it only repeats the sensitivity analysis; confidence stays unchanged after a standing challenge without explanation.
- **Typical failure:** performative scepticism: objections that do not say which claim fails or what evidence would settle it.

## 13. Strategize — الاستراتيجية
- **In → Out:** frame + diagnosis + gaps (+ decision model, priorities, challenge) → a coherent system of choices. The full procedure is in `strategy-and-plan.md`, Part A.
- **Stop when:** no evidence-backed diagnosis exists; the meaning of "strategy" or the depth is unresolved; the mandate or authority is unresolved.
- **Rejected if:** it is a list of initiatives rather than choices; it restates the current direction without the next open choice; it has no exclusions; objectives lack measures; a KPI lacks a KPI card; capabilities are not linked to choices; choices contradict each other without resolution.
- **Typical failure:** an ambition plus a project list labelled "pillars".

## 14. Plan — الخطة
- **In → Out:** strategy + actions → a resourced, governed, measurable plan. The full procedure is in `strategy-and-plan.md`, Part B.
- **Stop when:** there are no explicit objectives or selected actions; ownership cannot be assigned, even provisionally.
- **Rejected if:** an initiative lacks its card; a KPI lacks its card; the budget is a single number with no basis, range or one-off/recurring split; milestones are dates without deliverables or gates; the plan ignores dependencies, capacity, governance or benefits tracking.
- **Typical failure:** a project list presented as a plan.
