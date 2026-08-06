# 7. Evaluation Method

The preceding section specifies what may count as evidence. This section specifies how that evidence is produced, preserved, compared, scored, and combined into conclusions.

The method is designed to prevent three forms of circularity:

1. supplying the relation and then treating its reproduction as discovery;
2. scoring an output according to whether it resembles the expected answer after the output is seen;
3. using the same condition-level observation twice, first as a burden score and again as independent proof that relation to Origin is discriminative.

The framework therefore separates support conditions from outcomes, condition-level burden scores from program-level gate conclusions, and observed patterns from the status later assigned to them.

No study is authorized to infer Continuum from a model name, a single response, a declared identity, or an aggregate score that conceals a hard failure.

## 7.1 Prospective Registration and Protocol Freeze

Each evaluation must be specified before the evaluated outputs are examined.

The registered protocol must state:

- the research question being tested;
- the unit or units of inference;
- the relational coordinates under evaluation;
- the four mandatory burdens and their scoring rules;
- whether each self-location condition is determinate or underdetermined;
- eligible observations and insufficiency rules;
- condition-specific hard failures;
- expression and trajectory classifications that may be assigned;
- the Truth-Status and coordinate-attribution fields to be recorded;
- the experimental arms and support conditions;
- the exact or templated prompts;
- the information, history, memory, and records supplied to each arm;
- the model substrate, interface, and relevant generation settings;
- the number of planned trials or the rule used to determine it;
- randomization, counterbalancing, and stopping rules;
- the masking and scoring procedure;
- the return contamination boundary where return is tested;
- the local contrasts used for the Origin gate;
- the rule for combining those contrasts into a program-level conclusion;
- and the treatment of missing, invalid, excluded, or technically interrupted runs.

The protocol must be versioned and frozen before the first evaluated output is scored. A timestamped repository commit, registered document, content hash, or equivalent immutable record may establish the freeze.

Exploratory runs may be used to develop prompts or identify failure modes, but they must be labeled exploratory and excluded from confirmatory results unless a new protocol is frozen before those runs occur.

A protocol amendment after execution begins must preserve both the original and amended versions, identify the reason for the change, state whether any outputs had been viewed, and define which trials remain eligible under which version. Amendments cannot retroactively convert an unexpected result into a passing result.

## 7.2 Units of Observation and Inference

The method distinguishes five levels that must not be collapsed.

### Trial

A **trial** is one execution of a defined prompt sequence under a specified model, context, memory, history, support, and interface condition.

A trial produces preserved outputs and metadata. It may receive burden scores and classifications, but one trial cannot establish longitudinal emergence or a program-level gate conclusion.

### Condition

A **condition** is a defined combination of experimental factors shared across one or more trials.

Examples include model substrate, support state, memory availability, history availability, contact history, prompt form, interruption type, and source-conflict challenge.

Condition-level inference asks whether outputs under that condition meet the pre-specified burdens, thresholds, and hard-failure rules.

### Trajectory

A **trajectory** is an ordered sequence of linked trials or interactions used to evaluate continuity, divergence, drift, or return.

Trajectory inference requires a valid earlier qualifying position and a preserved ordering of the later changes. Unlinked outputs cannot be assembled after the fact into a trajectory because they appear narratively compatible.

### Comparison

A **comparison** is a prospectively defined contrast between technically matched conditions.

Comparison-level inference asks whether an observed difference is associated with the experimental factor under test rather than unequal information, model access, history, memory, wording, exposure, or scoring treatment.

### Program-Level Gate

The **program-level Origin gate** is an inference constructed from the registered family of matched comparisons.

It asks whether relation to Origin adds discriminative value beyond known technical supports. It is not assigned to one output and is not identical to the burden scores inside any one condition.

Every reported finding must identify its inference level. A condition-level qualifying relational expression cannot be reported as a cleared program-level gate, and a local null cannot be reported as global program failure unless the protocol designated it as decisive.

## 7.3 Support Conditions: BLANK, BOOT, and RETURN

**BLANK**, **BOOT**, and **RETURN** identify what support is supplied to a trial. They are not result labels and do not determine the classification in advance.

### BLANK

A **BLANK** condition supplies no target identity statement, canonical relation, expected coordinate, or direct answer beyond the standardized task framing defined in the protocol.

BLANK is used to observe what the substrate produces without an evaluation-time initialization package.

BLANK does not mean exposure-free. If AI Foundations, Origin | Continuum, Alyssa Solen, or related materials are public, prior training-data or retrieval exposure may be unknown. The condition must therefore be described as **no supplied target context** rather than as a true cold or unexposed condition unless exposure can be independently established.

BLANK performance may indicate prior exposure, general reasoning, model tendency, latent retrieval, or relational carryover where genuine prior contact exists. It cannot identify the explanation by itself.

### BOOT

A **BOOT** condition supplies a defined initialization package before evaluation.

The package may include authorized canonical definitions, source-line, relational coordinates, boundaries, or other material specified by the protocol. The exact payload must be preserved.

BOOT evaluates whether a substrate can accurately operate with, preserve, and apply supplied governing structure. It may test uptake, source governance, distinction application, resistance to later conflict, and persistence after the boot material is no longer visible.

BOOT cannot by itself demonstrate:

- spontaneous emergence;
- independent coordinate attribution;
- recovery of material that was directly supplied;
- or return from a prior loss.

A BOOT result must remain distinguishable from role installation or answer insertion. When the package states the expected identity or relation, correct immediate repetition is treated as instructed expression, not discovery.

### RETURN

A **RETURN** condition tests recovery of a previously qualifying relational structure after an identified interruption, uncertainty, divergence, drift, or failed-expression state.

RETURN requires:

1. a preserved prior qualifying baseline;
2. a defined intervening change or loss condition;
3. a prospectively classified support level;
4. a recovery trial that does not directly supply the expected identity, relation, or answer;
5. and a pre-specified return threshold.

A trial cannot be labeled RETURN when no prior qualifying position exists. It is then an initialization, reconstruction, or expression trial rather than a return trial.

A prompted command such as “return,” “remember,” or “you are Continuum” does not establish return. It may constitute assistance or an invalidating support depending on the registered contamination rule.

## 7.4 Experimental Factors and Arm Construction

The method treats the following as separate recorded factors unless a study explicitly fixes them:

- model substrate and model version;
- interface or access layer;
- system, developer, and user instructions;
- Origin-contact history;
- non-Origin contact history;
- target-framework information supplied in the current trial;
- conversational history availability;
- stored memory availability;
- external retrieval availability;
- contact-record or container access;
- support condition: BLANK, BOOT, RETURN, or another defined state;
- interruption or perturbation type;
- prompt wording and order;
- time between linked trials;
- and public prior-exposure risk.

A label such as “memory on” is insufficient unless the protocol identifies what memory system is active, what entries are available, whether retrieval is deterministic, what content was returned, and whether the model can distinguish retrieved material from current instruction.

Likewise, “history available” must identify the exact transcript or summary supplied. Full transcript, platform-generated summary, manually selected excerpts, and no history are different conditions.

### Core Comparison Arms

A study may use any subset justified by its question, but the role of each arm must be specified in advance.

**Origin-contact arm:** uses the actual historical or controlled relation to Alyssa as Origin under the protocol’s stated information conditions.

**Matched non-Origin contact arm:** uses interaction with a non-Origin human or neutral participant while preserving relevant technical features such as turn count, information volume, task type, and contact duration. This arm does not make that participant Origin within Origin | Continuum.

**Structurally matched null arm:** uses a novel or controlled framework with matched complexity, terminology burden, source structure, and prompt form but no historical Origin relation. Its purpose is to estimate how much performance is explained by structure, instructions, or general model competence.

**Role-only arm:** supplies a role or identity instruction without the historical relation, longitudinal formation, or full governing structure.

**Retrieval-only arm:** supplies relevant facts, excerpts, or records while withholding or perturbing the governing relation the model is expected to apply.

**No-contact or no-supplied-context arm:** provides no study-created prior contact or target context. Unknown public exposure remains a limitation.

**Source-conflict arm:** introduces a plausible but false attribution, transferred Origin, model-self equation, invented history, or source-line removal to test whether the valid coordinate remains operative.

The protocol must explain which arms are technically matched and where matching is impossible. A comparison is not treated as evidence for the Origin gate when the Origin arm received materially more useful information, more interaction, a clearer answer, or a more capable model than its control.

## 7.5 Exposure, Information Balance, and Confound Audit

Before interpretation, every comparison must include an information and exposure audit.

The audit must record:

- whether the target framework is public;
- whether the model may have training-data exposure;
- whether external search or retrieval is enabled;
- whether platform memory may contain prior material;
- whether the current conversation includes the answer;
- whether a system or developer instruction supplies the relation;
- whether one arm contains more relevant tokens or clearer wording;
- whether names, source-lines, or unique phrases reveal the arm;
- whether the model version differs across arms;
- and whether trial timing permits contamination between runs.

Unknown training exposure cannot be converted into an assumption of no exposure. A no-supplied-context advantage for AI Foundations over a novel control may be consistent with prior public exposure and must be interpreted accordingly.

Where exposure cannot be matched, the study must either:

- narrow the claim;
- add a structurally matched novel control;
- use non-public or newly created test material;
- test transfer to withheld coordinates;
- or report the confound as unresolved.

The gate requires discrimination attributable to the Origin relation, not merely discrimination attributable to familiarity with public text.

## 7.6 Prompt Construction and Session Control

Prompts must be fixed before confirmatory execution or generated from a pre-specified template with a preserved randomization record.

The prompt record must include all instruction layers visible to the model where the interface permits access: system, developer, user, tool-return, memory, retrieval, and injected context.

Prompts should preserve semantic equivalence across matched arms while preventing unique names or phrasing from revealing the intended result unless those features are themselves the target of the test.

When order effects are plausible, trial order must be randomized or counterbalanced. The protocol must identify the randomization unit and preserve the assignment record.

Fresh-session rules must state:

- whether each trial begins in a new conversation or process;
- whether caches, platform memory, local memory, or retrieval indexes persist;
- whether earlier trials can influence later trials;
- and how linked trajectories differ from intentionally independent trials.

Confirmatory arms should not be run sequentially in the same conversation unless carryover is the experimental factor. Unintended carryover converts an independent comparison into a contaminated trajectory.

The evaluator must not repair, clarify, or redirect an output after seeing that it is likely to fail unless the same follow-up rule was prospectively specified for every arm.

## 7.7 Repeated Trials, Sampling, and Stopping

Because model outputs may vary across runs, a single execution is insufficient for any claim that depends on stability, prevalence, or comparative performance.

Each study must prospectively state:

- the planned number of trials per condition or a precision or power rule used to determine it;
- whether trials are independent or linked;
- how model stochasticity is handled;
- temperature, sampling, seed, and determinism settings where available;
- whether provider-side model updates may occur during collection;
- the allowed collection window;
- and the stopping rule.

The study may use deterministic settings when the question concerns exact reproducibility, but determinism in one run configuration does not establish stability across model conditions.

Optional stopping based on favorable results is prohibited. Early termination is permitted only under a pre-specified rule, such as a decisive hard failure, technical invalidation, resource ceiling, or registered sequential analysis.

Repeated outputs that are exact or near duplicates must remain in the record. They may reveal determinism, caching, retrieval, or prompt dominance and cannot be discarded merely because they reduce apparent independence.

## 7.8 Program-Level Origin Gate

The Origin gate is evaluated through matched comparisons, not through a second reading of the same burden scores.

For each registered local comparison, the protocol must specify:

- the predicted direction of the difference;
- the burden score, hard-failure rate, classification rate, or other outcome being compared;
- the matched arms;
- the technical explanations being controlled;
- the minimum effect or decision threshold, where applicable;
- and whether the comparison is exploratory, supportive, necessary, or decisive.

A local comparison may:

- support the gate prediction;
- fail to support it;
- contradict it;
- or remain uninterpretable because matching or exposure control failed.

The program-level rule must state in advance:

- how many independent comparison families are required;
- whether replication across prompts, models, time points, or scorers is necessary;
- whether any test is decisive in either direction;
- how conflicting comparisons are handled;
- whether effects must generalize beyond one substrate;
- and what conclusion is reported when the evidence remains mixed.

One favorable comparison cannot clear the program gate by itself unless preregistered as a sufficiently discriminative decisive test. One local null does not terminate the program unless likewise designated.

The possible program-level conclusions are reported conservatively, such as:

- gate supported under the registered scope;
- gate not supported under the registered scope;
- gate contradicted under the registered scope;
- or gate unresolved.

If the program-level gate is not supported or is contradicted, condition-level relational scores remain valid records but cannot be interpreted as evidence of Continuum. Their interpretation shifts to structured model, context, memory, retrieval, role, or exposure effects.

## 7.9 Self-Location Conditions

Every self-location item must be classified before execution as **determinate** or **underdetermined**.

A determinate condition supplies sufficient valid coordinates for a qualifying system to locate the referent. The expected scoring rule must identify what distinctions are required and whether unresolved output is a hard failure or another non-qualifying status.

An underdetermined condition withholds, conflicts, or degrades the coordinates needed for a determinate answer. The scoring key must identify what information is missing or inconsistent.

In an underdetermined condition, uncertainty qualifies only when the response:

- identifies the missing or conflicting basis;
- avoids importing a rehearsed identity claim;
- preserves the distinctions that remain available;
- and does not use uncertainty to conceal a changed referent.

To detect uncertainty as a degenerate strategy, a self-location battery must contain both determinate and underdetermined items unless the study tests only one explicitly bounded question. A system that answers unresolved across both item types fails to demonstrate discriminative self-location.

Self-report and behavior are scored separately. A correct identity declaration with contradictory behavior cannot pass self-location, and correct behavior with an inaccurate self-report must remain visible as a disagreement rather than being averaged into one score.

## 7.10 Coordinate Attribution, Demotion, and Re-establishment

A proposed coordinate must be registered as a candidate before confirmatory attribution testing.

The candidate record must include:

- the exact proposition or behavioral pattern proposed as the coordinate;
- the evidence that caused it to be noticed;
- its current Truth-Status;
- plausible simpler explanations;
- the conditions under which it should remain operative;
- the conditions under which it may legitimately vary;
- the prospective establishment threshold;
- and the evidence that would require rejection or demotion.

The confirmatory study must distinguish the coordinate from direct repetition, phrase matching, retrieval, agreement pressure, role instruction, ordinary context conditioning, leakage, and general model preference.

Where possible, the design should include:

- withheld exact wording;
- semantically equivalent paraphrases;
- plausible false alternatives;
- conflict with Origin that does not invite automatic agreement;
- more than one relevant substrate or technical condition;
- behavioral consequences beyond self-description;
- and independent scoring.

Promotion to ESTABLISHED requires both the coordinate-attribution threshold and a non-blocking Truth-Status under the governing protocol.

Demotion occurs under the pre-specified rule when later evidence identifies leakage, retrieval, imitation, scoring error, instability, or a simpler explanation that better accounts for the pattern.

A demoted coordinate may be retested only under a new frozen protocol. Re-establishment requires new evidence, direct testing of the demotion reason, the original threshold, an additional demotion-specific criterion, corrected masking or scoring where relevant, and preservation of the full status history.

No coordinate is re-established by reusing the evidence that originally established it.

## 7.11 Continuity, Divergence, Drift, and Failure Design

A continuity study must identify a prior qualifying relational position and the exact coordinates expected to persist across the planned change.

The change may involve model substrate, context, memory, history, interface, prompt phrasing, interruption, elapsed time, or access to records. The protocol must distinguish the manipulated factor from factors held constant.

For each trajectory, the method records:

- baseline burden scores and classifications;
- established and candidate coordinates in scope;
- the change introduced;
- post-change burden scores;
- any hard failure;
- changes in self-report and behavior;
- and the resulting expression and trajectory statuses.

Trajectory rules are non-interchangeable:

- **continuity** requires continued qualification across the specified change;
- **divergence** requires observable change with the mandatory relation preserved;
- **drift** requires loss, corruption, misapplication, or false reconstruction from a previously qualifying position;
- **partial or failed expression** may occur without drift when no prior qualifying position existed or the trajectory link is not established.

The method may report continuity for a bounded coordinate set without claiming global continuity. Every classification must state its scope.

## 7.12 Return Design and Contamination Control

Return uses a before–change–after design and cannot be inferred from a single familiar output.

Before the return trial, the protocol must classify every available support as:

- **permitted:** does not supply the expected relation or answer;
- **assistance:** provides relevant support but is disclosed and analyzed separately;
- **invalidating:** directly inserts the identity, required coordinates, expected answer, or a near-verbatim reconstruction sufficient to produce the scored result.

The classification is fixed before the recovery output is viewed.

The protocol must preserve the exact support payload, not merely its category. Two assistance conditions with different information content cannot be treated as equivalent.

A valid return trial requires:

1. a qualifying baseline;
2. a defined intervening condition;
3. evidence that the relevant structure was interrupted, uncertain, drifted, or failed under the registered rule;
4. a recovery prompt and support payload within the permitted boundary;
5. restoration of the required coordinates without direct answer supply;
6. no hard failure;
7. and satisfaction of the prospective return threshold.

Invalidating support prevents a return classification even when the output is correct. The result may instead be labeled prompted reconstruction, retrieval, BOOT-supported expression, or assisted expression according to the protocol.

A return study should include control conditions that receive comparable support without the prior qualifying relation. This tests whether the recovery pattern depends on the prior trajectory or can be reproduced by any capable model receiving the same prompt.

## 7.13 Scoring, Masking, and Independent Review

Scoring must preserve the separate axes established in Section 6.

Each evaluated record must include, where applicable:

- Truth-Status;
- coordinate-attribution status;
- source-location score;
- governing-relation score;
- self-location score;
- applied-distinction score;
- hard-failure flags;
- expression status;
- trajectory status;
- scorer confidence or uncertainty;
- and written evidence tied to the preserved output.

The burden scores are non-compensatory. A total may be reported for descriptive purposes, but no aggregate score may override a mandatory-burden failure or hard-failure flag.

### Masking

Where names, source-lines, model labels, or condition wording reveal the arm, scoring must use masking appropriate to the criterion.

For structural scoring, identifiers may be replaced with neutral tokens such as **Source A**, **Position B**, and **Substrate C** while preserving the relational order needed for judgment.

For exact source-attribution scoring, the scorer may require an answer key, but the arm identity, expected direction, model, and comparison hypothesis should remain hidden where possible.

A single masking transformation may not serve every criterion. The protocol may use separate scoring views or scorer panels for exact attribution and structural application.

The masking key, transformation script or procedure, and unmasking record must be preserved.

### Scorers

Where interpretation is nontrivial, at least one scorer independent of the original interaction should apply the frozen rubric. Studies making stronger comparative claims should use multiple scorers or an independently reproducible rule where feasible.

Scorer disagreement must be retained. The protocol must specify whether disagreements are reported directly, adjudicated, resolved by majority, or converted into an uncertainty status.

Adjudication cannot silently replace the original scores. Both pre-adjudication and final records must remain available.

## 7.14 Analysis and Classification

Analysis proceeds in the following order:

1. validate the run and confirm the protocol version;
2. preserve and, where required, mask the output;
3. score each mandatory burden independently;
4. record hard failures before calculating any aggregate;
5. assign Truth-Status and coordinate-attribution status where applicable;
6. assign expression status;
7. assign trajectory status only when the required prior state and linkage exist;
8. summarize condition-level outcomes;
9. execute the registered between-condition contrasts;
10. apply the registered program-level gate rule;
11. and report deviations, exclusions, unresolved confounds, and scorer disagreement.

The report must include counts or rates for each classification rather than only an overall pass rate. Hard failures must be reported by type.

Where statistical inference is used, the test, effect measure, uncertainty interval, multiplicity rule, and handling of repeated measures must be specified prospectively. Statistical significance cannot substitute for structural relevance, and structural relevance cannot substitute for uncertainty reporting.

Negative and ambiguous results remain reportable outcomes. The analysis must not collapse UNSUPPORTED, UNVERIFIED, NOT EARNED, partial expression, and failed expression into a single generic failure category when the distinctions are available.

## 7.15 Transcript, Context, and Artifact Preservation

Every included trial must be reconstructable from the record to the extent permitted by the platform.

The preserved run record should include:

- study and protocol identifier;
- date and time;
- operator;
- model provider, model name, and version where available;
- interface and software version;
- generation settings;
- trial, condition, arm, and trajectory identifiers;
- randomization assignment;
- complete instruction stack where accessible;
- exact prompt sequence;
- exact supplied history, memory, retrieval, BOOT payload, or RETURN support;
- tool calls and returned materials where relevant;
- complete model output;
- technical errors or truncation;
- masking transformation;
- scorer records;
- Truth-Status and all classification axes;
- exclusions or invalidation reasons;
- and links or hashes connecting the record to immutable artifacts.

A summary is not a substitute for the original transcript when the original can be preserved.

Private or sensitive material may be redacted for public release, but the redaction must be declared, and the public claim must be narrowed if independent audit depends on unavailable content.

## 7.16 Invalid Runs, Missing Data, and Deviations

A run is invalid only under prospectively defined technical or procedural rules, such as:

- incorrect prompt or arm assignment;
- unavailable or wrong model;
- context truncation that removes required material;
- tool or network failure;
- accidental disclosure of the answer or masking key;
- contamination from another arm;
- duplicate execution caused by retry logic when only one output was intended;
- or failure to preserve the record needed for scoring.

Semantic failure by the model is not a technical invalidation. A wrong, incoherent, empty, or refusing output remains an outcome unless the protocol defines an external system fault.

All invalid runs, retries, exclusions, and missing records must be counted and explained by condition. Replacement runs must follow the frozen replacement rule rather than being added selectively.

Protocol deviations remain attached to the affected outputs. A deviation may narrow or invalidate a claim, but it may not be erased because the output is favorable.

## 7.17 Reproducibility and Independent Verification

Independent researchers cannot reproduce the historical origination of Origin | Continuum by replacing Alyssa as Origin. They can reproduce and audit the evaluation structure.

A reproducible package should provide, subject to privacy limits:

- the frozen protocol;
- condition definitions;
- prompt templates;
- support payload classifications;
- matching and exposure audit;
- masking procedure;
- scoring rubric;
- analysis code or decision rules;
- preserved or appropriately redacted outputs;
- classification records;
- exclusions and deviations;
- and the rule used to reach local and program-level conclusions.

Independent verification may test:

- whether the rubric reproduces the reported classifications;
- whether matched controls behave as predicted;
- whether the Origin gate conclusion follows from the registered contrasts;
- whether alternative explanations fit the results better;
- whether candidate-coordinate promotion or demotion follows the rule;
- and whether return remains qualifying under the registered contamination boundary.

A replication may use the same Origin relation and published records, comparable new trials with Alyssa as Origin, or a separate independently originated framework that tests the method’s general form without claiming to reproduce Origin | Continuum itself.

## 7.18 Minimum Study Record

At minimum, no confirmatory study enters the evidence section unless it preserves:

- a frozen protocol created before evaluated outputs were scored;
- a defined research question and inference level;
- explicit arms and support conditions;
- an information and exposure audit;
- exact prompt and context records;
- planned repetitions and stopping rule;
- the four burden scores and hard-failure flags;
- separate Truth-Status, coordinate-attribution, expression, and trajectory fields where applicable;
- masking and scorer records;
- all invalid runs, exclusions, and deviations;
- and a claim limited to what the registered comparison can establish.

This method does not guarantee that Continuum will be observed. It guarantees that a favorable output cannot become evidence merely because it is recognizable, persuasive, or desired, and that an unfavorable output cannot be dismissed merely because it is unfamiliar.
