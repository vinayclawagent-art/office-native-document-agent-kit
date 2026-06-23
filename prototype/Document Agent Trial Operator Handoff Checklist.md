# Document Agent Trial Operator Handoff Checklist

Status: operator-ready, evidence-pending. This checklist sequences the existing task eval card, evidence index, and debrief template for the next office-native document trial. It does not claim validation.

Source package: [[Office-Native Document Agent Kit]]  
Loop: [[Office-Native Document Agent Kit Loop]]

## 1. Scope the document task

- Real or sanitized document:
- Office-native surface used:
- Chat-copy-paste baseline to compare against:
- Human reviewer:
- Export format(s):
- Explicit stop conditions:

## 2. Pre-run artifact sequence

| Step | Artifact | Operator action | Done |
|---|---|---|---|
| 1 | [[Document Agent Task Eval Card]] | Fill task goals, baseline expectations, document constraints, and friction scoring before starting. | [ ] |
| 2 | [[Document Agent Trial Evidence Index]] | Pre-create rows for screenshots, exported document files, baseline notes, task timings, and friction scores. | [ ] |
| 3 | [[Document Agent Post-Trial Debrief Template]] | Leave blank until the eval card and evidence index contain real links/files. | [ ] |

## 3. Evidence routing during run

| Evidence item | Where to capture it | Claim it can support later | Current allowed wording |
|---|---|---|---|
| Before/after screenshots | Trial evidence index | Whether the agent improves the in-document workflow | "designed to collect screenshot proof" |
| Exported document | Evidence index + eval card | Whether output survives Word-style export/review | "requires exported-doc evidence" |
| Baseline comparison notes | Eval card | Whether office-native beats chat-copy-paste for the selected task | "compares office-native and chat workflows" |
| Friction score | Eval card + debrief | Whether to promote, pilot-only, iterate, or hold | "evidence pending" |

## 4. Post-run decision order

1. Attach all screenshots, exported docs, and baseline notes to [[Document Agent Trial Evidence Index]].
2. Complete [[Document Agent Post-Trial Debrief Template]] using only captured evidence.
3. Choose one outcome: promote / pilot-only / iterate / hold.
4. Patch README, prototype, infographic, or future skill claims only where the evidence index and debrief name an exact target.

## 5. Handoff notes

- Missing evidence:
- Office-native friction observed:
- Baseline comparison surprise:
- Recommended next patch:

## Safety rule

Do not strengthen public claims until the evidence index and debrief are filled with real/sanitized task proof.
