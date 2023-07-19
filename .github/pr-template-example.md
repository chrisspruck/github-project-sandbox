# Overview
The overview represents a high-level description of the changes which were introduced, including why they were introduced, and how they impact the user/developer experience. If appropriate, add screenshots/screen recordings reflecting the impact the change has to the user experience.

## Type of change

_Please delete options that are not relevant._

- [ ] Bug fix (non-breaking change which fixes an issue)
- [ ] New feature (non-breaking change which adds functionality)
- [ ] Breaking change (fix or feature that would cause existing functionality to not work as expected)
- [ ] This change requires a documentation update

# Checklist:

_Only check items that are applicable_

## General Considerations
- [ ] Does all new SQL in this PR (except for schema modifications) have an EXPLAIN attached?
- [ ] Is additional logging or monitoring advisable (text logs, CloudWatch metrics, etc.)?
- [ ] Does this PR use obsolete components?
- [ ] New and existing unit tests pass locally with proposed changes?
- [ ] Any dependent changes have been merged and published in downstream modules?

## Security Considerations
- [ ] Does this PR restrict brand ownership or other access controls?
- [ ] Does this PR have proper form validation and use prepared statements?
- [ ] Does this PR take the [OWASP Top Ten](https://owasp.org/www-project-top-ten/) into consideration?

## Privacy Considerations
- [ ] Does this PR involve sensitive information?
- [ ] Does this PR only store information that we need to store?
- [ ] Does this PR store information that requires encryption?
- [ ] Does this PR have any data law ramifications (GDPR, CCPA, etc.)?

# Notes
* This section can be omitted if the scope of the change does not necessitate it.

# Reversion Plan
_(only update if required)_

For reverting code changes, a new PR removing the changes introduced (e.g. `git reset HEAD~1`)
For reverting infrastructure changes, create a new PR removing the changes here (e.g. `git reset HEAD~1`) and confirm the terraform plan output.

# Refs
* [JIRA Ticket](https://shootproof.atlassian.net/browse/FOR-)
