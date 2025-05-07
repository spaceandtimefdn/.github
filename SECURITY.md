<!-- BEGIN SECURITY.MD -->

## Security

We take security seriously and have established the following process to ensure vulnerabilities are handled promptly and responsibly.

If you believe you have found a security vulnerability in any repository that meets [NIST's definition of a security vulnerability](https://csrc.nist.gov/glossary/term/vulnerability), please report it to us as described below.

---

## Table of Contents

1. [Scope & Supported Versions](#scope--supported-versions)  
2. [Reporting a Vulnerability](#reporting-a-vulnerability)  
3. [Our Response Process](#our-response-process)  
4. [Coordinated Disclosure & Public Acknowledgement](#coordinated-disclosure--public-acknowledgement)  
5. [Vulnerability Disclosure Program](#vulnerability-disclosure-program-vdp)  
7. [Feedback](#feedback)  

---

## Scope & Supported Versions

We strive to maintain security fixes for all actively supported versions of our software. If you are unsure whether your version is covered, please report the issue; our team will confirm applicability.

---

## Reporting a Vulnerability

**Do not** open GitHub issues, pull requests, or discussions for security reports.

When reporting, include as many details as possible:

- **Issue type** (e.g. SQL injection, XSS, insecure deserialization)  
- **Repository & Version** (tag/branch/commit SHA or direct URL)  
- **File paths** where the vulnerability occurs  
- **Reproduction steps** or test case  
- **Proof-of-concept** or exploit code, if available  
- **Suggested severity/impact** and any mitigating factors  

---

## Our Response Process

Once a report is received:

1. **Triage & Acknowledgment**  
   - Assign a primary handler.  

2. **Investigation & Fix**  
   - Confirm the issue and scope (affected versions).  
   - Audit related code paths for similar patterns.  
   - Develop and test patches for all supported versions.

3. **Release & Notification**  
   - Publish security-only releases as soon as fixes are ready.  
   - Send you a private follow-up with the patch details and advisories.

4. **Closure**  
   - Once patches are live, we’ll confirm resolution and (with your permission) acknowledge you in our public advisory.

---

## Coordinated Disclosure & Public Acknowledgement

- We will not disclose any details until a fix is available, or a mutually agreed embargo expires.  
- If you wish to be credited publicly, please let us know; otherwise, we will maintain anonymity.  
- After disclosure, we’ll post an advisory and update this policy.

---

## Vulnerability Disclosure Program (VDP)

**All vulnerability reports must go through our official VDP on HackerOne.**

- **Submission Channel**  
  - HackerOne: [hackerone.com/spaceandtime](https://hackerone.com/spaceandtime)

- **Private & Invite-Only**  
  - Our VDP is closed and available by invitation only.  
  - To request an invitation, please email us at **security@spaceandtime.io**.

- **Guidelines**  
  - Adhere to the submission and disclosure requirements on HackerOne.  
  - Include all details outlined in [Reporting a Vulnerability](#reporting-a-vulnerability).

- **Acknowledgment & Response**  
  - Our Security Team will investigate, triage, and provide status updates via the platform.

- **Safe Harbor**  
  - Researchers acting in good faith will not face legal or disciplinary action.

---

## Feedback

If you have suggestions to improve this process, please submit a pull request against this `SECURITY.md`. We welcome your input!

---

*Last updated: May 2025*  

<!-- END SECURITY.MD BLOCK -->
