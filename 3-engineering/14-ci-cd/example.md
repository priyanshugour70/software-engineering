# Example CI/CD Pipeline – Digital SME Lending

## Stage 1: Build
- Compile backend services, run linters.
- Build frontend assets.
- Build Docker images and tag with commit SHA.

## Stage 2: Unit & Component Tests
- Run unit tests for all services and components.
- Enforce minimum coverage threshold (e.g., 80%).

## Stage 3: Static & Security Analysis
- Run ESLint, Prettier, Checkstyle.
- Run SAST and dependency scanning.
- Fail build on high-severity vulnerabilities.

## Stage 4: Integration & Contract Tests
- Spin up dependent services via docker-compose.
- Run contract tests against mock providers.
- Verify compatibility with shared APIs.

## Stage 5: Package & Publish Artifacts
- Publish Docker images to registry.
- Publish Helm charts to chart repo.

## Stage 6: Deploy to Staging
- Use IaC and deployment scripts to update staging.
- Run database migrations.

## Stage 7: Smoke & E2E Tests
- Run automated E2E tests via Cypress/Playwright.
- Execute smoke test suite.

## Stage 8: Production Deployment
- Triggered manually or automatically based on policies.
- Canary or blue/green deployment.
- Monitor KPIs during rollout and roll back on failure.