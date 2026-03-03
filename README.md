# Recon Engine: AI-Native Multi-Source Financial Reconciliation

## What the human can now do that they couldn't before

A broker-dealer processing $100B+ in assets must reconcile every transaction across trade execution, custodian settlement, client ledger, and tax engine — before issuing tax slips or reporting to regulators. Today this is reactive: rule-based SQL flags mismatches, an engineer investigates from scratch, and the same root causes get re-diagnosed every time. No institutional memory. One engineer cannot cover 20M+ daily records.

With Recon Engine, one analyst oversees reconciliation across all sources at volume. The system pre-filters 95%+ of records as clean matches using deterministic logic (fast, exact), invokes AI only on the ~5% flagged as anomalous, diagnoses root causes against a knowledge base of past incidents, and escalates only when confidence is below threshold or regulatory filings are at stake. Hours become minutes — and every human correction makes the system smarter.

## What AI is responsible for

The pipeline uses a deliberate hybrid of deterministic and AI processing — each applied where it fits:

**Deterministic logic** handles exact joins (transaction ID, CUSIP matching), arithmetic validation (FX calculations, amount sums), schema enforcement, and duplicate detection by composite key. These require 100% accuracy and zero ambiguity — AI adds risk here, not value.

**AI handles three tasks where human judgment was previously required.** First, entity resolution: the same security appears as "AAPL" in the trade engine, "APPLE INC" at the custodian, and "Apple Inc Com" in the tax engine. LLM resolves these where deterministic matching fails. Second, root cause diagnosis: when a discrepancy is found, AI correlates it against a knowledge base of historical incidents and generates a confidence-scored diagnosis with evidence. Third, materiality-weighted prioritization: a $0.03 rounding difference is not the same as a $36K missing settlement — AI ranks discrepancies by financial impact so humans see what matters first.

## Where AI must stop

Different stages carry different risk. Entity resolution uses a 95% confidence threshold — ambiguous matches below that go to a human. Reconciliation diagnosis uses 70% — even uncertain analysis saves hours versus starting from zero, so the threshold is lower. Anything affecting regulatory filings (T5008 slips, FINTRAC reports, CRA submissions) always requires human sign-off regardless of confidence.

Critically, every human decision feeds back into the knowledge base. When an analyst confirms a diagnosis, corrects one, or resolves a novel discrepancy type, that pattern is stored. The confidence thresholds themselves tighten over time for well-understood patterns and remain conservative for rare ones. The human-in-loop isn't just a safety net — it's the training signal.

## What would break first at scale

The knowledge base coverage. As transaction volume grows and new instruments, counterparties, and edge cases appear, the system will encounter novel discrepancy patterns not in its history. Without continuous enrichment from human feedback, confidence scores drift and false escalation rates climb — overwhelming the analysts the system was designed to protect. The first investment at scale is ensuring every human resolution is captured, indexed, and retrievable, so institutional knowledge compounds rather than decays.

## Your salary expectation and years of hands-on experience with AI tools or systems.

Salary: Negotiable
Hands-on experience with AI tools or systems: 2+ years
Total experience Data + AI/ML: ~13years
LinkedIn: www.linkedin.com/in/shaktisinghshekhawat92
