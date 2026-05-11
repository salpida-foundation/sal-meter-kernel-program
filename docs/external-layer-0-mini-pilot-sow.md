# External Layer-0 Mini Pilot SOW

Pre-SRA Public Helper Document for Bounded Electrochemical Feasibility Inquiry

**Repository:** salpida-foundation/sal-meter-kernel-program  
**Document status:** Public helper / pre-SRA execution support  
**Canonical status:** Non-canonical helper document  
**Program status:** kernel-first · pre-opening · research-stage · non-clinical · non-diagnostic · non-therapeutic · non-surveillance · pre-device · pre-certification  
**Intended audience:** external electrochemistry laboratories, biosensor groups, redox-interface researchers, technical reviewers, ESL / EStL candidates, SRA advisors  
**Contact:** contact@salpida.foundation  

---

## 0. Boundary Notice

This document is a public helper SOW outline for an External Layer-0 mini pilot.

It is not a canonical authority document.

It does not define CAIS.

It does not validate Sal-Meter.

It does not grant CAIS compliance.

It does not certify any laboratory, device, dataset, electrode system, workflow, cartridge, reagent condition, signal-processing method, or implementation.

It does not authorize clinical, diagnostic, therapeutic, counseling, surveillance, employment, insurance, legal, educational, eligibility, or human-ranking use.

Canonical authority remains fixed in DOI-registered records and formally designated Salpida Foundation / SICS authority surfaces.

This document exists only to help external laboratories understand the minimum scope of a bounded chemistry-first feasibility inquiry before any SRA-facing work.

---

## 1. Purpose

The purpose of this External Layer-0 mini pilot is to reduce one early technical uncertainty:

> Can an iodine redox / thiol-interface environment produce stable, repeatable, auditable electrochemical signal behavior under bounded feasibility conditions?

This is a chemistry-first feasibility support task.

It is not a human-state validation study.

It is not a consciousness measurement study.

It is not an internal SICS Phase 0 study.

It is not a Phase 1 I-channel lock.

It is not a Sal-Meter validation experiment.

It is not a CAIS conformance pathway.

External Layer-0 exists before internal kernel-phase claims.

---

## 2. Position in the Program

The current program order must be read as:

```text
External Layer-0
→ SICS Internal Phase 0
→ Phase 1
→ Phase 2a
→ Phase 2b
→ LOCK 1 / LOCK 2
→ Future SDK / broader opening
```
External Layer-0 is not SICS Internal Phase 0.

External Layer-0 is not Phase 1.

External Layer-0 is an outsourced chemistry-first feasibility support track.

Its purpose is to determine whether a narrow electrochemical interface deserves deeper internal work.

---

## 3. Core Feasibility Question

The mini pilot should address the following bounded question:

> Under controlled non-clinical laboratory conditions, can iodine redox behavior and thiol / disulfide perturbation behavior be observed with enough stability, repeatability, and metadata clarity to justify further internal kernel-stage investigation?

This question may be explored through standard electrochemical characterization methods already familiar to the external laboratory.

The study should focus on:

- iodine redox baseline behavior
- I⁻ / I₃⁻-oriented electrochemical profile observation
- gold working electrode compatibility
- thiol / disulfide perturbation response
- drift behavior
- same-day repeatability
- basic control behavior
- raw data and metadata completeness
- feasibility risks and recommended next-step boundaries

---

## 4. What This Mini Pilot Is

This mini pilot is:

- a bounded external feasibility inquiry
- a non-clinical electrochemical characterization task
- a pre-SRA helper execution package
- a technical uncertainty-reduction step
- a raw-data and metadata discipline test
- a drift / repeatability / control-awareness task
- an input to later internal review

It is designed to help answer whether further internal work is justified.

---

## 5. What This Mini Pilot Is Not

This mini pilot is not:

- Sal-Meter validation
- CAIS compliance
- CAIS conformance
- certification
- device readiness
- clinical readiness
- diagnostic validation
- therapeutic validation
- human-subject validation
- consciousness measurement
- human-state classification
- commercial product testing
- public competition participation
- public SDK work
- mark usage authorization
- publication approval
- canonical definition

No external party may describe participation in this mini pilot as CAIS-compliant, Sal-Meter-ready, Sal-Meter-validated, SICS-certified, clinically validated, diagnostically useful, therapeutically useful, or device-ready.

---

## 6. Suggested Mini Pilot Scope

The external laboratory may propose a bounded 4–6 week feasibility scope.

The exact laboratory method remains the responsibility of the external laboratory and must comply with its own safety, institutional, regulatory, and technical standards.

This public helper document does not prescribe a wet-lab recipe.

A suitable mini pilot may include the following work packages.

---

## 6.1 Work Package A — Iodine Redox Baseline Characterization

Purpose:

To observe whether an iodine redox environment can produce interpretable and repeatable electrochemical features under controlled laboratory conditions.

Possible measurement modes:

- OCP
- CV
- DPV
- SWV
- EIS, if relevant to the laboratory’s existing workflow

Expected observations:

- baseline shape
- signal stability
- peak or feature position
- current or potential response
- noise profile
- same-day repeatability
- time-dependent drift
- obvious electrode or matrix instability

Expected output:

- raw electrochemical files
- run metadata
- baseline stability summary
- repeatability summary
- drift summary
- laboratory interpretation of feasibility limits

---

## 6.2 Work Package B — Thiol / Disulfide Perturbation Response

Purpose:

To observe whether thiol / disulfide-related perturbation can produce directionally interpretable signal change in the iodine redox environment.

This work package should remain exploratory.

It should not be framed as biomarker detection.

It should not be framed as diagnosis.

It should not be framed as human-state classification.

Expected observations:

- direction of signal change
- perturbation-response pattern
- repeatability across repeated runs
- drift versus perturbation distinction
- interference or instability warning signs

Expected output:

- raw electrochemical files
- perturbation log
- run metadata
- directionality summary
- repeatability summary
- instability notes
- feasibility interpretation

---

## 6.3 Work Package C — Control and Drift Review

Purpose:

To determine whether observed signal change can be distinguished from drift, electrode instability, matrix artifact, or handling artifact.

Expected review categories:

- blank or buffer control behavior
- repeated-run variation
- same-day drift behavior
- electrode condition notes
- cleaning / handling notes, if applicable
- instrument setting summary
- anomaly notes
- failed-run notes

Failed or ambiguous runs should not be hidden.

Failure data is useful.

A feasibility pilot that maps what fails is still valuable.

---

## 6.4 Work Package D — Optional Matrix Compatibility Check

Purpose:

To evaluate whether the signal environment shows obvious collapse or major instability in a more complex non-diagnostic biological or biological-like matrix.

This work package is optional.

If biological materials are used, the laboratory must ensure that all handling, consent, biosafety, privacy, and institutional requirements are satisfied before work begins.

No identifiable human data should be generated for public GitHub use.

No raw human data should be published in this repository.

Expected output, if performed:

- matrix type summary
- public-safe description of handling boundary
- raw electrochemical files retained in controlled-access or private delivery route
- public-safe feasibility summary only
- instability and contamination notes
- no clinical interpretation

---

## 7. Minimum Deliverables

The mini pilot should deliver the following materials.

### 7.1 Raw Data Package

Include raw electrochemical output files where available.

Examples may include:

    raw_data/
      run_001_ocp.csv
      run_002_cv.csv
      run_003_dpv.csv
      run_004_swv.csv

The exact file format may follow the laboratory’s instrument export format.

Raw files should not be replaced by screenshots alone.

Screenshots may be provided only as supplementary figures.

---

### 7.2 Metadata Table

Include a metadata table sufficient to interpret each run.

Minimum suggested fields:

    run_id
    date
    operator_or_lab_code
    instrument_model
    working_electrode_type
    reference_electrode_type
    counter_electrode_type
    solution_or_condition_label
    matrix_label
    measurement_mode
    start_time
    end_time
    replicate_number
    temperature_note
    pH_note
    preparation_note
    electrode_condition_note
    anomaly_flag
    anomaly_note
    public_release_status

Do not include personally identifiable information.

Do not include private participant information.

Do not include clinical information.

---

### 7.3 Run Map

Include a run map connecting each raw file to its condition.

Example:

    run_map.csv

Suggested fields:

    run_id
    file_name
    condition_group
    measurement_mode
    replicate_number
    control_or_test
    included_in_summary
    exclusion_reason_if_any

---

### 7.4 Drift and Repeatability Summary

Include a short drift / repeatability report.

It should state:

- whether baseline features were interpretable
- whether same-day repeats preserved direction
- whether drift dominated the observed signal
- whether failed runs occurred
- what instability risks were observed
- what should be changed before any next-stage study

---

### 7.5 Feasibility Interpretation Memo

Include a short public-safe memo with one of the following conclusions:

    Pass for next internal review
    Revise before next internal review
    Hold due to instability
    No-Go under current conditions

The memo should not claim validation.

The memo should not claim Sal-Meter readiness.

The memo should not claim CAIS compliance.

It should state only whether the external feasibility result is strong enough to justify further review.

---

## 8. Acceptance Logic

This mini pilot is not scored as a final validation.

It is reviewed as feasibility evidence.

Suggested review logic:

### Pass for next internal review

A pass may be considered if:

- iodine redox behavior is interpretable
- repeat runs are reasonably consistent
- perturbation direction is observable
- drift does not dominate the main observation
- raw data are complete
- metadata are sufficient
- controls and failed runs are disclosed

### Revise before next internal review

A revise outcome may be considered if:

- signal behavior is partially interpretable
- drift or noise remains significant
- metadata are incomplete but recoverable
- repeatability requires better controls
- run conditions require clearer separation

### Hold due to instability

A hold outcome may be considered if:

- drift dominates the signal
- electrode instability prevents interpretation
- repeatability is weak
- controls are not sufficient
- raw data or metadata are not adequate

### No-Go under current conditions

A no-go outcome may be considered if:

- no interpretable signal behavior is observed
- perturbation response is not distinguishable from noise
- results cannot be reconstructed from raw data
- public/private boundary is violated
- laboratory output implies unauthorized clinical, diagnostic, therapeutic, device, certification, or compliance claims

---

## 9. Public / Private Data Boundary

Public GitHub materials may include:

- this SOW
- public-safe summary tables
- synthetic examples
- mock file trees
- public boundary notes
- non-sensitive metadata templates
- non-identifiable feasibility summaries
- issue templates
- README route descriptions

Public GitHub materials must not include:

- raw human data
- identifiable participant data
- clinical records
- health records
- private session logs
- consent forms containing personal information
- Sal-Meter raw core input unless separately governed
- confidential laboratory data
- private SRA documents
- private contractual terms
- unpublished controlled-access datasets
- detailed wet-lab recipes or optimization parameters
- sequence-generation instructions
- private conformance materials
- certification materials

The default rule:

> Public GitHub explains structure.  
> Private delivery carries controlled data.  
> DOI records govern authority.

---

## 10. Required Boundary Language for External Communication

External communication should use:

    External Layer-0 feasibility inquiry
    bounded electrochemical feasibility support
    iodine redox / thiol-interface feasibility
    research-stage
    non-clinical
    non-diagnostic
    non-therapeutic
    pre-device
    pre-certification
    no CAIS compliance granted
    no Sal-Meter validation granted

External communication must not use:

    validated Sal-Meter
    CAIS-compliant device
    certified Sal-Meter
    clinical diagnostic test
    therapeutic platform
    consciousness measurement device
    human-state classifier
    commercial device readiness
    official conformance result
    public competition entry

---

## 11. Suggested Folder Structure for Private Delivery

A private controlled-access delivery package may use the following structure:

    Layer0_[LabName]_[YYYYMMDD]/
      README.md
      raw_data/
      metadata/
        run_metadata.csv
        run_map.csv
      summaries/
        baseline_summary.md
        drift_repeatability_summary.md
        perturbation_response_summary.md
      figures/
      notes/
        anomaly_log.md
        failed_runs.md
      feasibility_memo.md

This folder structure is illustrative.

It is not a public GitHub data publication structure.

---

## 12. ESL Review Role

The ESL should review:

- physical measurement stability
- electrochemical plausibility
- electrode behavior
- drift behavior
- repeatability
- perturbation-response direction
- instrument and condition notes
- whether the system is stable enough to justify a next-stage internal review

The ESL owns the question:

> Is the physical measurement system stable enough to trust the next step?

---

## 13. EStL Review Role

The EStL should review:

- raw data completeness
- metadata completeness
- run map clarity
- failed-run disclosure
- audit trail
- public/private data separation
- claims boundary
- reproducibility package logic
- whether the evidence can survive review

The EStL owns the question:

> Is the evidence structure traceable enough to survive review?

---

## 14. Suggested 4–6 Week Mini Pilot Timeline

### Week 0 — Scope confirmation

- confirm laboratory fit
- confirm public/private boundary
- confirm expected measurement modes
- confirm deliverable structure
- confirm no clinical, diagnostic, therapeutic, certification, or compliance claims

### Week 1 — Baseline setup

- initial iodine redox baseline observation
- instrument export check
- metadata table setup
- run ID convention setup

### Week 2 — Repeatability and drift

- same-day repeated runs
- drift observation
- control review
- failed-run logging

### Week 3 — Perturbation review

- thiol / disulfide perturbation response review
- directionality assessment
- instability check
- replicate summary

### Week 4 — Optional matrix or robustness review

- optional matrix compatibility check
- robustness notes
- anomaly summary
- next-step risk assessment

### Week 5–6 — Delivery and review

- raw data delivery
- metadata delivery
- summary delivery
- feasibility memo delivery
- ESL / EStL review
- Pass / Revise / Hold / No-Go decision

---

## 15. SRA Relevance

This mini pilot SOW is useful before SRA negotiation because it fixes the minimum external feasibility burden.

It helps clarify:

- what an external lab is being asked to do
- what data must be returned
- what is public and what is private
- what claims are prohibited
- what the ESL should evaluate
- what the EStL should evaluate
- what counts as sufficient pre-SRA technical seriousness

It does not replace an SRA.

It does not define IP terms.

It does not define payment terms.

It does not define publication rights.

It does not grant rights to use CAIS, Sal-Meter, SICS, or Salpida Foundation marks.

Any legal, financial, IP, publication, confidentiality, or commercialization terms must be handled in separate SRA or contractual documents.

---

## 16. Final Rule

External Layer-0 is a gate of humility.

It asks whether the interface survives contact with matter before larger claims are allowed to speak.

If the signal is unstable, the project learns.

If the signal is ambiguous, the project narrows.

If the signal is repeatable, the project earns the next internal step.

No claim may run ahead of the evidence.

No helper document may replace canonical authority.

No public GitHub file may convert feasibility into validation.
