# Decision Process

This document describes how technical and non-technical decisions are made within the Jojo Privacy organization.

Jojo Privacy develops privacy-sensitive and security-critical software.  
As a result, decisions prioritize correctness, security, and long-term maintainability over speed or convenience.

---

## Scope of Decisions

This process applies to:
- Architectural changes
- Cryptographic design choices
- Privacy guarantees and assumptions
- Breaking changes
- Governance and policy updates
- Release and disclosure decisions

Minor documentation fixes and non-behavioral refactors may follow a simplified review process.

---

## Decision Principles

All decisions are guided by the following principles:

1. **Security over features**
2. **Privacy over convenience**
3. **Clarity over cleverness**
4. **Long-term trust over short-term speed**

If a proposal violates any of these, it will not be accepted.

---

## Decision Flow

### 1. Proposal
- Decisions start as a GitHub issue or design document.
- The proposal must clearly explain:
  - The problem being solved
  - Alternatives considered
  - Security and privacy implications
  - Trade-offs

### 2. Discussion
- Maintainers and contributors may discuss the proposal publicly.
- Cryptographic or privacy-critical changes require explicit discussion.
- Silence does not imply approval.

### 3. Review
- Maintainers review the proposal for:
  - Technical correctness
  - Privacy impact
  - Security risks
  - Maintainability

### 4. Decision
- A decision is made by maintainers.
- For high-impact changes, consensus is preferred.
- If consensus cannot be reached, the final decision rests with the project lead.

---

## Emergency Decisions

In the case of:
- Active security vulnerabilities
- Privacy-impacting bugs
- Responsible disclosure timelines

Maintainers may take immediate action without prior public discussion.  
A public explanation will be provided after mitigation.

---

## Reversibility

All decisions may be revisited if:
- New information becomes available
- Security assumptions change
- A flaw is discovered

Reversing a decision is acceptable. Hiding mistakes is not.

---

## Transparency

All non-sensitive decisions are documented publicly.  
Security-sensitive details may be redacted until responsible disclosure is complete.

