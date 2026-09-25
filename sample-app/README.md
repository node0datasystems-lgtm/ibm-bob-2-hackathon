# Seeded sample app (demo target)

Intentionally imperfect Node/Express (or Python) service used to show SecureShip Gate findings.

Planted issues (for demo metrics):
- Outdated dependency with known CVE
- Missing authz check on one route
- No test for error path
- Hardcoded secret placeholder (fake, for detection demo)
- Missing rollback notes in release doc

All synthetic. No real client data.
