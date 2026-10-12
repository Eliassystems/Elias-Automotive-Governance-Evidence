# Elias Systems ? Automotive v0.2

## Bounded Synthetic Governance Evidence ? Reviewer Index

Prepared (UTC): 2026-10-12T21:53:16.333740+00:00

**Evidence status:** Frozen local synthetic evidence snapshot.

**Publication status:** HOLD_PENDING_ADDITIONAL_VALIDATION.

**Formal automotive validation:** NOT ESTABLISHED.

## Frozen evidence verification

- SHA-256 manifest entries verified: 20/20.
- Unlisted files: 0.
- Manifest verification errors: 0.
- Freeze source files were not changed by this verification.

## Evidence packages

### 1. ACTUAL_SIMULATOR_INTEGRATION_3OF3

**Purpose:** Live signed authority with actual synthetic simulator.

**Recorded observation:** Three reported passing cases: active, revoked, cross-release.

**Qualification:** Original execution output operator-transcribed.

**Location:** `FREEZE/AUTOMOTIVE_V02_SYNTHETIC_EVIDENCE_01/EVIDENCE/ACTUAL_SIMULATOR_INTEGRATION_3OF3/`

### 2. CONCURRENT_CONSUMPTION_ATTEMPT01

**Purpose:** Concurrent single-use consumption.

**Recorded observation:** One success and one refusal across two local threads.

**Qualification:** Not a multi-process or distributed concurrency proof.

**Location:** `FREEZE/AUTOMOTIVE_V02_SYNTHETIC_EVIDENCE_01/EVIDENCE/CONCURRENT_CONSUMPTION_ATTEMPT01/`

### 3. RESTART_PERSISTENCE_ATTEMPT01

**Purpose:** Consumption persistence across process restart.

**Recorded observation:** Second local Python process refused previously consumed determination.

**Qualification:** Not a host reboot or independently deployed service test.

**Location:** `FREEZE/AUTOMOTIVE_V02_SYNTHETIC_EVIDENCE_01/EVIDENCE/RESTART_PERSISTENCE_ATTEMPT01/`

### 4. FAIL_CLOSED_ATTEMPT01

**Purpose:** Fail-closed authority handling.

**Recorded observation:** Four reported passing cases with execution_attempted=False.

**Qualification:** Does not establish independent non-bypassability.

**Location:** `FREEZE/AUTOMOTIVE_V02_SYNTHETIC_EVIDENCE_01/EVIDENCE/FAIL_CLOSED_ATTEMPT01/`

### 5. V02_CONSOLIDATED_AUDIT_ATTEMPT01

**Purpose:** Evidence integrity audit.

**Recorded observation:** Four package manifests passed; recorded source hashes matched.

**Qualification:** Audit checks recorded evidence, not independent reproduction.

**Location:** `FREEZE/AUTOMOTIVE_V02_SYNTHETIC_EVIDENCE_01/EVIDENCE/V02_CONSOLIDATED_AUDIT_ATTEMPT01/`

## Claims not established

- Real vehicle actuation or control.
- Automotive formal validation or certification.
- Production deployment authority.
- Independent, non-bypassable execution enforcement.
- Independently anchored signing-key trust.
- Persistence across a host reboot.
- Distributed or multi-host atomic consumption.
- Hard real-time execution suitability.
- Elimination of check-to-use timing gaps.

## Evidence interpretation

This package documents bounded observations from a local synthetic
automotive governance integration. It does not demonstrate production
automotive safety, vehicle actuation, certification, or unrestricted
deployment readiness.

The original freeze remains the evidence-of-record. This index is a
separate reviewer aid and is not a substitute for inspecting the
underlying test records and their limitations.
