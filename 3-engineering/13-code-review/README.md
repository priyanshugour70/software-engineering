## Code Review

### Overview

**Code Review** is a critical quality and knowledge-sharing practice where engineers **review each other’s changes** before merging. In enterprises, it also supports **compliance, security, and auditability**.

Code review helps catch defects early, ensures consistency, and spreads understanding across the team.


### Objectives

- **Identify defects and vulnerabilities** early.
- **Maintain coding standards and architectural consistency**.
- **Share knowledge** about code, architecture, and domain.
- **Improve maintainability** and reduce technical debt.
- **Provide a lightweight governance mechanism** for changes.


### Activities

- **Pull Request (PR) Creation**
  - Prepare small, focused PRs with clear descriptions.
  - Link PRs to issues, requirements, and RFCs.

- **Review Process**
  - Reviewers examine code changes, tests, and documentation.
  - Use checklists to cover correctness, security, performance, and style.
  - Discuss alternatives and improvements via comments.

- **Feedback Application**
  - Author addresses comments, refactors, and clarifies.
  - Additional review cycles as needed.

- **Approval and Merge**
  - Ensure required approvals are obtained (e.g., 2 reviewers, security sign-off for sensitive changes).
  - Merge via fast-forward, squash, or merge commit based on policy.

- **Post-Merge Follow-Up**
  - Monitor CI results and production behavior.
  - Capture lessons learned for future changes.


### Inputs

- **Source code changes** and associated tests.
- **Coding standards and guidelines**.
- **Architecture and design documents**.


### Outputs

- **Reviewed and improved code** merged into main branches.
- **Review comments and discussions** recorded in the system.
- **Knowledge transfer** to reviewers.


### Roles Responsible

- **Primary**
  - Software Engineers (as authors and reviewers)

- **Supporting**
  - Tech Leads (for complex or architectural changes)
  - Security Engineers (for sensitive areas or periodic security reviews)


### Tools Commonly Used

- Pull request systems in GitHub, GitLab, Bitbucket.
- Static analysis and code quality plugins integrated into PRs.
- Code review bots for automated checks.


### Example Review Checklist

- **Correctness**
  - Does the code do what the story/requirement describes?
  - Are edge cases handled?

- **Tests**
  - Are tests present and sufficient?
  - Do tests align with acceptance criteria?

- **Style and Readability**
  - Is code easy to understand and follow?
  - Are names meaningful and consistent?

- **Architecture and Design**
  - Does the code align with architecture decisions and patterns?
  - Any unnecessary coupling or duplication?

- **Security and Privacy**
  - Any sensitive data handled correctly?
  - Proper input validation and error handling?

- **Performance and Scalability**
  - Any obvious inefficiencies?
  - Proper use of caching, batching where needed?


### Example Scenario

For **digital SME lending**, a PR refactors the document upload flow:

- Reviewers identify that error handling around storage failures is insufficient.
- They suggest:
  - Adding retries with exponential backoff.
  - Logging structured error events for monitoring.
  - Updating tests to cover storage error paths.

The author updates the code and tests, and the PR is approved and merged, avoiding potential production incidents.


### Best Practices

- **Keep PRs small and focused**: Easier and faster to review thoroughly.
- **Provide context**: Good descriptions, screenshots for UI changes, and links to issues.
- **Be respectful and constructive**: Focus on code, not individuals.
- **Automate what you can**: Use linters and CI to catch basic issues.
- **Rotate reviewers**: Spread knowledge and avoid silos.
- **Use checklists**: Standardize review coverage.


### Common Mistakes

- **Huge PRs** that are hard to review and lead to superficial approvals.
- **Rubber-stamping** approvals without real review.
- **Personal criticism** instead of constructive feedback.
- **Not linking PRs to requirements**, causing traceability gaps.
- **Ignoring security and performance** in reviews, focusing only on style.

Well-run code reviews **improve quality, share knowledge, and create a culture of engineering excellence**.