# Identity & Access Baseline

## What I did
- Verified AWS CLI identity context using STS
- Confirmed IAM user in use instead of root
- Enforced MFA on root and IAM user
- Rotated and removed stale access keys
- Applied strong password policy

## Why it matters
Identity is the primary breach vector. MFA and key hygiene reduce account takeover risk and enforce least privilege practices.

## Proof
- 00-caller-identity.json
- IAM dashboard MFA screenshots
