# REQUIREMENTS ANALYSIS MATRIX

## Mandatory Requirements

### 1. Security Policy Compliance
- [cite_start]**Description**: Offerors must include a complete "Fairfax County Project Proposal Matrix for Meeting Information Technology Security Policy Requirements"[cite: 636].
- [cite_start]**Location**: Attachment 1, Section 1.4.2[cite: 636].
- [cite_start]**Evidence Required**: Completed Attachment H[cite: 636].
- **Compliance Approach**: Review Fairfax County IT Security Policy and map solution capabilities to Matrix H.

### 2. IT Consultant Agreement
- [cite_start]**Description**: Offerors must include the completed Attachment J: Fairfax County IT Services Provider Consultant/Contractor Agreement[cite: 639].
- [cite_start]**Location**: Attachment 1, Section 1.4.4[cite: 639].
- [cite_start]**Evidence Required**: Completed Attachment J[cite: 639].
- **Compliance Approach**: Legal review and signature. [cite_start]**Non-negotiable**[cite: 640].

### 3. Business Authorization
- [cite_start]**Description**: Contractor must be authorized to transact business in the Commonwealth of Virginia (Title 13.1 or Title 50)[cite: 440].
- [cite_start]**Location**: Appendix A, Section 61[cite: 440].
- [cite_start]**Evidence Required**: Valid registration/certification[cite: 441].
- **Compliance Approach**: Verify status with Virginia SCC.

### 4. BPOL License
- [cite_start]**Description**: Firms doing business in Fairfax County must obtain a BPOL License[cite: 432].
- [cite_start]**Location**: Appendix A, Section 60[cite: 432].
- [cite_start]**Evidence Required**: BPOL Tax number on Cover Sheet[cite: 434].
- **Compliance Approach**: Register with Department of Tax Administration if applicable.

---

## Technical Requirements

### Architecture Requirements

#### 1. Mobile & Web Architecture
- [cite_start]**Requirement**: Solution must use modern web-based application architecture and be operational out of the box on any mobile device OS[cite: 593].
- [cite_start]**Acceptance Criteria**: Functional on iOS/Android without custom dev[cite: 593].
- [cite_start]**Location**: Attachment 1, Section 1.1.1[cite: 593].

#### 2. Active-Active Failover
- [cite_start]**Requirement**: Solution must be able to seamlessly fail-over and be active-active[cite: 744].
- [cite_start]**Location**: Attachment 1, Section 12.9.2[cite: 744].
- **Priority**: Critical.

### Integration Requirements

#### 1. SAP (FOCUS) Integration
- [cite_start]**Target System**: SAP-based ERP (Fairfax County Unified System - FOCUS)[cite: 593].
- [cite_start]**Integration Type**: Interface[cite: 593].
- [cite_start]**Location**: Attachment 1, Section 1.1.1[cite: 593].

#### 2. GIS Integration
- [cite_start]**Target System**: County GIS[cite: 593].
- [cite_start]**Integration Type**: Interface[cite: 593].
- [cite_start]**Location**: Attachment 1, Section 1.1.1[cite: 593].

#### 3. Public Website Integration
- [cite_start]**Target System**: County Public Website[cite: 593].
- [cite_start]**Integration Type**: Interface[cite: 593].
- [cite_start]**Location**: Attachment 1, Section 1.1.1[cite: 593].

### Security and Compliance Requirements

#### 1. Data Ownership
- **Requirement**: All County data remains sole property of County. [cite_start]Source code reverts to County in bankruptcy[cite: 686, 693].
- [cite_start]**Location**: Attachment 1, Section 12.5.1[cite: 686].

#### 2. Section 508 / ADA
- [cite_start]**Standard**: Section 508 guidelines for accessibility[cite: 22].
- [cite_start]**Requirement**: Compliant with ADA and Section 508[cite: 638].
- [cite_start]**Location**: Attachment 1, Section 1.4.3[cite: 638]; Addendum 1, Ans. [cite_start]2[cite: 22].

#### 3. HIPAA Compliance
- [cite_start]**Standard**: HIPAA (Business Associate Agreement may be required)[cite: 36].
- [cite_start]**Scope**: All systems handling HIPAA protected info[cite: 36].
- **Location**: Addendum 1, Ans. [cite_start]4[cite: 36].

---

## Performance Requirements (SLAs)

### 1. Service Availability (Uptime)
- [cite_start]**Metric**: Uptime Percentage - Standard Traffic Period[cite: 759].
- [cite_start]**Required Performance**: 99.9%[cite: 759].
- [cite_start]**Penalty for Non-Compliance**: 10% of average revenue for the failure period (past 24h avg)[cite: 787].
- [cite_start]**Location**: Attachment 4, Service Availability[cite: 759].

### 2. Public Interface Response Times
- [cite_start]**Initial page load**: Max 2 seconds[cite: 768].
- [cite_start]**Login time**: Max 20 seconds[cite: 768].
- [cite_start]**Static page load**: Max 2 seconds[cite: 768].
- [cite_start]**Search result return**: Max 5 seconds[cite: 768].
- [cite_start]**Transaction completion**: Max 60 seconds[cite: 768].
- [cite_start]**Penalty**: 10% of all revenue collected for prior comparable period[cite: 787].

### 3. Staff Interface Response Times
- [cite_start]**Login time**: Max 10 seconds[cite: 772].
- [cite_start]**POS (Standard)**: Max 30 seconds[cite: 772].
- [cite_start]**Class Registration**: Max 120 seconds[cite: 772].
- [cite_start]**Check-in Validation**: Max 2 seconds[cite: 772].
- [cite_start]**Location**: Attachment 4, Staff Interface[cite: 772].

---

## Staffing Requirements

### 1. Implementation/Support Staff
- [cite_start]**Role**: Personnel for implementation and management[cite: 639].
- [cite_start]**Requirement**: Must sign Consultant/Contractor Agreement (Attachment J)[cite: 639].
- [cite_start]**Remote Access**: Must use 2FA tokens; personal machines subject to County standards (anti-virus, patch mgmt)[cite: 658, 675].
- [cite_start]**Location**: Attachment 1, Section 1.4.8[cite: 647].

---

## Administrative Requirements

### 1. Insurance / Indemnification
- [cite_start]**Requirement**: Indemnify County against claims, including data breach and IP infringement[cite: 403, 408].
- [cite_start]**Location**: Appendix A, Section 58[cite: 402].
