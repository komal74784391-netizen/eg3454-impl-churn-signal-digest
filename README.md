# Churn Signal Digest - implementation

Status: **Released** - v1.2.0

Production implementation repository for the Churn Signal Digest blueprint in the Automation
Blueprints gallery. The implementation is maintained by CS Enablement and shipped
with the gallery release train.

## Contents

- `src/main.py` - entry point and orchestration
- `src/rules.yaml` - default policy configuration
- `CHANGELOG.md` - release history
- `tests/test_smoke.py` - smoke checks used by the release pipeline

## Usage

See `src/rules.yaml` for the default configuration. Deployments pin a tagged
release rather than tracking the default branch.
