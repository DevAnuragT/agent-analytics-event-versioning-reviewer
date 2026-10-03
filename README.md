# Analytics Event Versioning Reviewer

Check event schema changes for versioning, compatibility, and consumer migration evidence.

## Run

    python3 agent.py examples/good-input.json
    python3 tools/review-analytics-event-versioning-reviewer.py examples/good-input.json

Input requirements and thresholds are listed in metadata.json. Output contains status, score, checked rules, and evidence-backed findings.

## Limits

Offline, deterministic review aid. Cannot establish facts beyond supplied evidence; a human must review before acting.
