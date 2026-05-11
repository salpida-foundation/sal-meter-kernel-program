# Layer-0 Data Deliverables

Pre-SRA Public Helper Standard for External Layer-0 Feasibility Data Handover

**Repository:** salpida-foundation/sal-meter-kernel-program  
**Document status:** Public helper / pre-SRA execution support  
**Canonical status:** Non-canonical helper document  
**Program status:** kernel-first · pre-opening · research-stage · non-clinical · non-diagnostic · non-therapeutic · non-surveillance · pre-device · pre-certification  
**Related document:** docs/external-layer-0-mini-pilot-sow.md  
**Intended audience:** external electrochemistry laboratories, biosensor groups, redox-interface researchers, ESL / EStL candidates, SRA advisors  
**Contact:** contact@salpida.foundation  

---

## 0. Boundary Notice

This document defines the expected data handover structure for an External Layer-0 feasibility inquiry.

It is a public helper document.

It is not a canonical authority document.

It does not define CAIS.

It does not validate Sal-Meter.

It does not grant CAIS compliance.

It does not certify any laboratory, dataset, electrode system, method, device, cartridge, workflow, reagent condition, software layer, signal-processing method, or implementation.

It does not authorize clinical, diagnostic, therapeutic, counseling, surveillance, employment, insurance, legal, educational, eligibility, or human-ranking use.

This document does not require public release of raw experimental data.

This document does not authorize publication of raw human data.

Canonical authority remains fixed in DOI-registered records and formally designated Salpida Foundation / SICS authority surfaces.

---

## 1. Purpose

The purpose of this document is to define what an external laboratory should return after completing a bounded External Layer-0 mini pilot.

The purpose is not to force a single experimental method.

The purpose is to ensure that results can be reviewed, reconstructed, and interpreted without relying on narrative summaries alone.

The core principle is:

> No raw data, no review.  
> No metadata, no interpretation.  
> No boundary discipline, no next-stage trust.

External Layer-0 data delivery should allow ESL and EStL review without converting feasibility into validation.

---

## 2. Position in the Program

The current program order must be read as:

    External Layer-0
    → SICS Internal Phase 0
    → Phase 1
    → Phase 2a
    → Phase 2b
    → LOCK 1 / LOCK 2
    → Future SDK / broader opening

External Layer-0 is not SICS Internal Phase 0.

External Layer-0 is not Phase 1.

External Layer-0 is a chemistry-first external feasibility support track.

Data submitted under this structure may support internal review.

It does not create Sal-Meter validation.

It does not create CAIS compliance.

It does not create certification.

---

## 3. Required Delivery Philosophy

External Layer-0 data delivery must satisfy four requirements.

### 3.1 Traceability

Every figure, summary, table, or conclusion must be traceable back to a raw file or run record.

### 3.2 Completeness

The laboratory should disclose successful, failed, ambiguous, excluded, repeated, and anomalous runs.

Failure data is useful.

Ambiguous data is useful.

Hidden failure is not useful.

### 3.3 Boundary Safety

No public GitHub material should include private raw human data, identifiable participant information, clinical information, confidential SRA terms, or controlled-access laboratory data.

### 3.4 Reviewability

The data package should allow a technical reviewer to answer:

- What was measured?
- Under what condition?
- With what instrument?
- Using which electrode setup?
- At what time?
- Under which run ID?
- With what anomaly notes?
- What changed?
- What failed?
- What should be repeated?

---

## 4. Minimum Delivery Package

The expected private delivery package should contain the following folders.

    Layer0_[LabName]_[YYYYMMDD]/
      README.md
      raw_data/
      metadata/
      run_maps/
      summaries/
      figures/
      notes/
      feasibility_memo.md

This folder structure is intended for private or controlled-access delivery.

It is not a public GitHub raw-data publication structure.

---

## 5. Required File Group A — README

### 5.1 File

    README.md

### 5.2 Purpose

The README should explain the package contents at a high level.

It should allow a reviewer to understand the delivery package without opening every file first.

### 5.3 Minimum Content

The README should include:

- laboratory name or laboratory code
- delivery date
- project label
- contact person or contact role
- brief scope summary
- measurement modes used
- total number of runs
- number of included runs
- number of excluded runs
- number of failed or ambiguous runs
- folder structure summary
- public/private data boundary statement
- claims boundary statement

### 5.4 Required Boundary Sentence

Include the following or equivalent:

> This package is a bounded External Layer-0 feasibility data delivery package. It does not validate Sal-Meter, does not grant CAIS compliance, does not certify any system, and does not support clinical, diagnostic, therapeutic, surveillance, or human-ranking use.

---

## 6. Required File Group B — Raw Data

### 6.1 Folder

    raw_data/

### 6.2 Purpose

The raw data folder should contain original instrument-exported or minimally converted electrochemical data files.

Raw data must not be replaced by screenshots alone.

Screenshots may be supplementary.

### 6.3 Expected File Types

Acceptable file formats may include:

- CSV
- TXT
- XLSX
- instrument-export format
- PDF export only as supplementary documentation
- image files only as supplementary figures

Preferred file formats are structured text files such as CSV or TXT where possible.

### 6.4 Example File Naming Pattern

    raw_data/
      L0_RUN001_OCP_baseline_rep01.csv
      L0_RUN002_CV_baseline_rep02.csv
      L0_RUN003_DPV_perturbation_rep01.csv
      L0_RUN004_SWV_control_rep01.csv

### 6.5 Raw Data Rule

Every raw data file should map to a row in the run map.

Every run map row should point to at least one raw file or state why no raw file is available.

---

## 7. Required File Group C — Metadata

### 7.1 Folder

    metadata/

### 7.2 Required File

    run_metadata.csv

### 7.3 Purpose

The metadata table should make each run interpretable without private memory or verbal explanation.

### 7.4 Minimum Suggested Columns

    run_id
    lab_code
    date
    operator_or_operator_code
    instrument_model
    software_version
    measurement_mode
    working_electrode_type
    reference_electrode_type
    counter_electrode_type
    electrode_condition_note
    solution_or_condition_label
    matrix_label
    control_or_test
    replicate_number
    start_time
    end_time
    temperature_note
    pH_note
    preparation_note
    cleaning_or_handling_note
    anomaly_flag
    anomaly_note
    included_in_summary
    exclusion_reason_if_any
    public_release_status

### 7.5 Public-Safety Rule

Do not include:

- personally identifiable information
- participant names
- patient identifiers
- clinical labels
- health records
- private contact information
- private SRA terms
- confidential payment information
- confidential IP terms

If human-derived or biological materials are involved, use laboratory-safe codes and private controlled-access handling.

---

## 8. Required File Group D — Run Map

### 8.1 Folder

    run_maps/

### 8.2 Required File

    run_map.csv

### 8.3 Purpose

The run map connects raw files, run IDs, conditions, and summary inclusion decisions.

### 8.4 Minimum Suggested Columns

    run_id
    raw_file_name
    metadata_row_present
    measurement_mode
    condition_group
    control_or_test
    replicate_number
    included_in_summary
    exclusion_reason_if_any
    related_figure_or_summary
    notes

### 8.5 Review Rule

If a run appears in a figure, summary, or interpretation memo, it must appear in the run map.

If a run is excluded, the exclusion reason must be stated.

---

## 9. Required File Group E — Summary Reports

### 9.1 Folder

    summaries/

### 9.2 Required Summary Files

    baseline_summary.md
    drift_repeatability_summary.md
    perturbation_response_summary.md

Optional:

    matrix_compatibility_summary.md
    control_summary.md
    failed_run_summary.md

---

## 9.3 Baseline Summary

The baseline summary should answer:

- Was an interpretable iodine redox baseline observed?
- Which measurement modes were used?
- Were features stable enough to interpret?
- Was the baseline repeatable?
- What were the main sources of uncertainty?
- What should be repeated or improved?

This summary should not claim Sal-Meter validation.

---

## 9.4 Drift and Repeatability Summary

The drift / repeatability summary should answer:

- How stable was the signal over time?
- Did same-day repeats preserve direction or shape?
- Did drift dominate the observed response?
- Were repeated runs comparable?
- Were there electrode or matrix instability signs?
- Were any runs excluded?
- What is the recommended next step?

This summary should not convert feasibility into proof.

---

## 9.5 Perturbation Response Summary

The perturbation response summary should answer:

- Was a directionally interpretable signal change observed?
- Was the response repeatable?
- Was the response distinguishable from drift or noise?
- Did any perturbation appear unstable or ambiguous?
- Were controls sufficient?
- What should be revised before further work?

This summary should not be described as biomarker detection, human-state classification, diagnosis, or therapy.

---

## 10. Required File Group F — Figures

### 10.1 Folder

    figures/

### 10.2 Purpose

Figures may help reviewers visually inspect signal behavior.

Figures are supplementary.

They do not replace raw data.

### 10.3 Expected Figure Types

Examples:

- baseline trace figure
- repeated-run overlay
- perturbation response comparison
- drift plot
- control comparison
- excluded-run example

### 10.4 Figure Rule

Each figure should identify:

- run IDs
- condition group
- measurement mode
- whether the figure is illustrative or summary-level
- whether excluded runs are shown

No figure should imply validation beyond feasibility review.

---

## 11. Required File Group G — Notes

### 11.1 Folder

    notes/

### 11.2 Recommended Files

    anomaly_log.md
    failed_runs.md
    handling_notes.md
    reviewer_questions.md

### 11.3 Anomaly Log

The anomaly log should include:

- run ID
- anomaly type
- when it occurred
- whether it affected interpretation
- whether the run was excluded
- suspected cause
- recommended correction or repeat

### 11.4 Failed Runs

Failed runs should not be deleted from the narrative.

The failed-runs file should include:

- failed run ID
- failure description
- known or suspected cause
- whether raw data are available
- whether metadata are available
- what would be needed to repeat the run

Failure disclosure improves trust.

---

## 12. Required File Group H — Feasibility Memo

### 12.1 File

    feasibility_memo.md

### 12.2 Purpose

The feasibility memo should give a clear technical conclusion without overclaiming.

### 12.3 Allowed Conclusion Labels

Use one of the following:

    Pass for next internal review
    Revise before next internal review
    Hold due to instability
    No-Go under current conditions

### 12.4 Memo Structure

The memo should include:

- one-paragraph scope summary
- total runs reviewed
- measurement modes used
- main observation
- main instability or uncertainty
- raw data completeness status
- metadata completeness status
- drift and repeatability status
- perturbation response status
- recommended conclusion label
- recommended next step
- boundary statement

### 12.5 Required Boundary Statement

Include the following or equivalent:

> This feasibility memo does not validate Sal-Meter, does not grant CAIS compliance, does not certify any system, and does not support clinical, diagnostic, therapeutic, surveillance, or human-ranking use.

---

## 13. Minimum Package Checklist

Before delivery, confirm:

- README.md is included.
- raw_data/ folder is included or a reason is given.
- run_metadata.csv is included.
- run_map.csv is included.
- baseline_summary.md is included.
- drift_repeatability_summary.md is included.
- perturbation_response_summary.md is included.
- anomaly_log.md or equivalent notes are included.
- failed runs are disclosed.
- excluded runs have reasons.
- figures map to run IDs.
- feasibility_memo.md is included.
- no public raw human data are included.
- no identifiable participant data are included.
- no clinical, diagnostic, or therapeutic claims are included.
- no CAIS compliance claim is included.
- no Sal-Meter validation claim is included.

---

## 14. Public / Private Data Boundary

### 14.1 Public GitHub May Include

Public GitHub materials may include:

- this deliverables standard
- public-safe folder templates
- public-safe metadata field lists
- public-safe run map examples
- synthetic examples
- mock examples
- placeholder examples
- public helper documentation
- issue templates
- claims boundary notes

### 14.2 Public GitHub Must Not Include

Public GitHub materials must not include:

- raw human data
- identifiable participant data
- patient records
- clinical data
- health records
- real participant session logs
- private lab data
- private SRA documents
- private contract terms
- unpublished controlled-access datasets
- detailed wet-lab recipes or optimization parameters
- sequence-generation instructions
- confidential IP material
- private conformance materials
- certification materials

### 14.3 Default Rule

> Public GitHub explains structure.  
> Private delivery carries controlled data.  
> DOI records govern authority.

---

## 15. ESL Review Checklist

The ESL should check:

- Is the electrochemical signal interpretable?
- Are electrode conditions described?
- Are measurement modes clear?
- Are baseline features visible enough for review?
- Are drift patterns disclosed?
- Are repeated runs comparable?
- Are failed runs disclosed?
- Are control conditions sufficient?
- Is the perturbation response directionally interpretable?
- Is the system physically stable enough to justify the next internal review?

The ESL does not grant CAIS compliance.

The ESL does not certify Sal-Meter.

The ESL reviews physical feasibility only.

---

## 16. EStL Review Checklist

The EStL should check:

- Is the raw data package complete?
- Is every raw file mapped to a run ID?
- Is every summarized run traceable?
- Are metadata sufficient?
- Are excluded runs explained?
- Are anomalies disclosed?
- Is the public/private boundary respected?
- Are claims bounded?
- Is the feasibility memo reviewable?
- Can the evidence package survive later audit?

The EStL does not grant CAIS compliance.

The EStL does not certify Sal-Meter.

The EStL reviews evidence traceability only.

---

## 17. Common Delivery Failures

Common failures include:

- screenshots without raw data
- figures without run IDs
- missing metadata
- missing failed-run disclosure
- unclear condition labels
- no run map
- no drift summary
- no repeatability summary
- undocumented excluded runs
- claims that exceed feasibility
- private human data included in public materials
- diagnostic or therapeutic language
- CAIS compliance language
- Sal-Meter validation language

Any of these may trigger Revise, Hold, or No-Go review outcomes.

---

## 18. Allowed Language

Use:

    External Layer-0 feasibility data
    bounded feasibility package
    raw electrochemical data package
    metadata-supported review
    drift and repeatability review
    perturbation response summary
    pre-SRA helper deliverables
    non-clinical research-stage helper data
    no CAIS compliance granted
    no Sal-Meter validation granted

---

## 19. Prohibited Language

Do not use:

    validated Sal-Meter data
    CAIS-compliant dataset
    certified Layer-0 result
    clinical dataset
    diagnostic dataset
    therapeutic validation
    consciousness measurement evidence
    human-state classifier
    commercial device validation
    official conformance result
    benchmark proof
    certification-ready dataset

---

## 20. SRA Relevance

This document is useful before SRA negotiation because it shows that SICS / Salpida Foundation has a defined expectation for data handover.

It helps clarify:

- what the external lab must return
- what cannot be replaced by narrative
- what metadata are required
- what failures must be disclosed
- what is public and what is private
- what the ESL reviews
- what the EStL reviews
- why raw data and metadata matter before larger claims

This document does not replace an SRA.

It does not define IP rights.

It does not define payment terms.

It does not define publication rights.

It does not define confidentiality terms.

It does not grant rights to use CAIS, Sal-Meter, SICS, or Salpida Foundation marks.

Legal, financial, IP, publication, confidentiality, and commercialization terms must be handled in separate SRA or contractual documents.

---

## 21. Final Rule

A Layer-0 result is not trustworthy because it sounds promising.

It becomes reviewable only when raw data, metadata, run maps, summaries, anomalies, failed runs, and boundary language survive the same table.

The purpose of this document is to make that table exist before the first serious negotiation begins.

No data package may convert feasibility into validation.

No helper document may replace canonical authority.

No public GitHub file may grant CAIS compliance or Sal-Meter status.
