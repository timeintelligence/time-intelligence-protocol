# Time Intelligence Protocol v2.1

![Version](https://img.shields.io/badge/version-2.1-blue)
![License](https://img.shields.io/badge/license-CC%20BY%204.0-green)
![Status](https://img.shields.io/badge/status-locked-brightgreen)

A structured timing-analysis protocol derived from Zi Ping / Four Pillars methodology. It translates a classical Chinese timing-analysis system into an AI-executable reasoning chain with fixed steps, conditional outputs, and falsifiable checks.

The protocol does **not** predict the future. It identifies conditions under which a decision may function as expansion, escape, mismatch, or leverage — and requires those conditions to be stated as testable hypotheses.

**What this is for:** decision timing, strategic self-audit, structured reasoning, and AI-assisted analysis.  
**What this is not for:** fortune-telling, deterministic prediction, reassurance, or professional advice.

The canonical protocol file is `protocol-v2.1.md`. It defines classical Zi Ping lineage logic, verification through Step 8 hard checks and Section 5 falsification conditions, and version control: v2.1 is locked. Future protocol changes require a new versioned protocol file and changelog entry.

## Files

- [protocol-v2.1.md](protocol-v2.1.md) - authoritative protocol text. Preserved unchanged from the source document.
- [episode-01-prompt.md](episode-01-prompt.md) - execution prompt wrapper for the first analysis episode.
- [charting-guide.md](charting-guide.md) - input and run-order guide.
- [valid-output-checklist.md](valid-output-checklist.md) - pass/fail checklist for generated outputs.
- [disclaimer.md](disclaimer.md) - scope and reliance limits.
- [changelog.md](changelog.md) - version history and change control.
- [LICENSE](LICENSE) - reuse terms.

## Integrity Rule

`protocol-v2.1.md` is the canonical file.

Do not paraphrase it as a substitute for execution. Do not simplify it. Do not change rule order, tags, lineage priority, required steps, falsification conditions, or output format.

If any support document appears to conflict with the canonical `protocol-v2.1.md` file, the protocol controls.

## Standard Use

1. Read [disclaimer.md](disclaimer.md).
2. Load [protocol-v2.1.md](protocol-v2.1.md) in full.
3. Collect the required input package using [charting-guide.md](charting-guide.md).
4. Run the analysis with [episode-01-prompt.md](episode-01-prompt.md).
5. Validate the result against [valid-output-checklist.md](valid-output-checklist.md).

No output is valid unless it follows the complete mandatory chain in the protocol.

## Citation

If you reference this protocol in writing, video, or research, cite it as:

> Time Intelligence Protocol v2.1. https://github.com/timeintelligence/time-intelligence-protocol

If you test the protocol and collect pass/fail evidence, keep the evidence dated. Single-chart failures do not invalidate the protocol; systemic patterns are handled through the falsification conditions in `protocol-v2.1.md`.
