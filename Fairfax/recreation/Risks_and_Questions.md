# STRATEGIC RECOMMENDATIONS, RISKS, AND CLARIFICATION QUESTIONS

## Strategic Recommendations

### 1. Address the Revenue Penalty Head-On
[cite_start]**Rationale**: Attachment 4 imposes a 10% revenue credit penalty for performance failures (e.g., page load > 2s)[cite: 787]. This is aggressive.
**Action**:
- Conduct internal load testing immediately to verify <2s compliance.
- In proposal, provide evidence of performance at scale to build confidence.
**Impact**: Mitigates risk of disqualification or future revenue loss.

### 2. Highlight "Active-Active" Architecture
[cite_start]**Rationale**: The County specifically requested "Active-Active" failover in Attachment 1[cite: 744].
**Action**: Explicitly diagram the Active-Active setup in the Technical Volume.
[cite_start]**Impact**: Directly addresses a specific technical requirement for the "Priority" of continuity[cite: 38].

### 3. Validate Due Date Year
**Rationale**: Addenda dates (Jan 2026) conflict with Due Date (Feb 2025).
**Action**: Assume 2026 but monitor Bonfire portal daily.
**Impact**: Prevents missing the actual deadline.

## Questions for Clarification

### Administrative Questions
#### Q1: Confirmation of Due Date Year
**Question**: Addendum 2 is dated January 15, 2026, but lists the Due Date as February 20, 2025. Can the County confirm the correct Due Date is February 20, **2026**?
[cite_start]**Context**: Discrepancy between Addenda dates and Due Date[cite: 64, 68].
**Impact**: Critical for submission validity.

### Technical Questions
#### Q1: SLA Penalty Calculation
**Question**: Attachment 4 Section "Penalties" references a 10% revenue credit for failure to meet metrics like "Initial page load time". Is there a cap on this penalty, and does it apply to *all* revenue or only revenue processed during the specific infraction window?
[cite_start]**Context**: The term "comparable period" is used but 10% of *all* revenue seems punitive for minor latency[cite: 787].
**Impact**: Financial risk assessment.

#### Q2: HIPAA Scope
**Question**: Addendum 1 states the County expects systems handling HIPAA info to meet requirements. Can the County specify which modules or programs will handle HIPAA data?
[cite_start]**Context**: Accurate scoping of the BAA and security architecture[cite: 36].
**Impact**: Cost and technical scope.

## Risk Assessment

| Risk | Impact | Likelihood | Mitigation Strategy | Owner |
|------|--------|------------|---------------------|-------|
| **Submission Year Confusion** | **High** | **High** | Treat deadline as Feb 20, 2026, but verify via Portal. | Proposal Mgr |
| **Non-Negotiable Legal Terms** | **High** | **High** | Legal must review Attachment J immediately. [cite_start]It is marked "Non-negotiable"[cite: 640]. | Legal |
| **SLA Revenue Penalties** | **High** | **Medium** | Ensure technical solution is over-provisioned to meet <2s load times. | Tech Lead |
| **Missing Main RFP** | **High** | **High** | Locate Main RFP document immediately to find Evaluation Weights and detailed Scope. | Proposal Mgr |
