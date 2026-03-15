# Migration Granularity Notes

- Repository: `fintechbankx-openfinance-banking-metadata-service`
- Source monorepo: `enterprise-loan-management-system`
- Sync date: `2026-03-15`
- Sync branch: `chore/granular-source-sync-20260313`

## Applied Rules

- dir: `services/openfinance-banking-metadata-service` -> `.`
- file: `api/openapi/banking-metadata-service.yaml` -> `api/openapi/banking-metadata-service.yaml`
- dir: `infra/terraform/services/banking-metadata-service` -> `infra/terraform/banking-metadata-service`
- file: `docs/architecture/open-finance/capabilities/hld/open-finance-capability-overview.md` -> `docs/hld/open-finance-capability-overview.md`
- file: `docs/architecture/open-finance/capabilities/test-suites/banking-metadata-test-suite.md` -> `docs/test-suites/banking-metadata-test-suite.md`

## Notes

- This is an extraction seed for bounded-context split migration.
- Follow-up refactoring may be needed to remove residual cross-context coupling.
- Build artifacts and local machine files are excluded by policy.

