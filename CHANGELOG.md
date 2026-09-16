# Changelog

All notable changes to this project are recorded here.
Format follows Keep a Changelog; versioning follows Semantic Versioning.

## [0.1.0] — unreleased

### Added
- `docs/lifecycle.md`: the lifecycle architecture, standards mapping and an
  account of how the three layers meet.
- Governance lifecycle with the admissibility gate sited between decision
  support and execution, and feedback paths from assurance and audit to
  governance, controls and risk management.
- Framework-of-frameworks mapping: each lifecycle stage anchored to the
  external standards it draws on.
- Issue-scoring engine: five scored dimensions, derived priority tier,
  next action.
- JSON Schema for the input and output contracts.
- Worked example suite: five fictional scenarios spanning five failure modes
  and four outcome tiers, including an authorised-absence control case.
- Dependency-free conformance checker that re-derives every tier from the
  published rules.
- Obligation register: a jurisdiction-specific layer decomposing each obligation into gate criteria, controls, evidence types and assurance activities, with its own schema and coverage checker.
- Register support for standing, conditional and anticipatory obligations, including dependencies and coverage findings.
- One illustrative worked register entry for post-quantum cryptographic migration, demonstrating how the architecture represents an emerging obligation whose governance consequences arise before the obligation fully crystallises.
- Added Preface: French-language context on the repository’s international scope and evaluation criteria.
- Refined and repositoned Preface.

### Changed
- Register support extended to distinguish enacted, transitional and contingent obligations.
- Standards mapping refined to record legal status and distinguish voluntary from legally recognised standards.

  ### Notes
- The rubric anchors are published as provisional and may change before v1.0.
  The tier rules and schema contracts are stable.
