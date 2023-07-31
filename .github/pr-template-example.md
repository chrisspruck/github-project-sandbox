# Overview
This should be a description of the changes which were introduced, including why they were introduced. If appropriate, add screenshots or screen recordings showing UI changes, for understanding and visual confirmation.

# Checklist:
_Only check items that are applicable. Please delete options that are not relevant._

## General 
- [ ] Are there appropriate tests (new or modified) for the proposed changes?
- [ ] For new SQL (other than schema modifications), has performance been considered and/or tested, was an EXPLAIN plan run, was the change discussed with others, etc.?
- [ ] Is additional logging or monitoring advisable (activity_log db entries, CloudWatch metrics, etc.)?
- [ ] Are there any infrastructure changes needed or other infrastructure implications to make people aware of?
- [ ] Does this change require a documentation update (API or other)?

## Security and Privacy Considerations
- [ ] Does this PR have proper form validation and use prepared statements?
- [ ] Does this PR involve sensitive information?
- [ ] Does this PR only store information that we need to store?
- [ ] Does this PR store information that requires encryption?
- [ ] Does this PR have any data law ramifications (GDPR, CCPA, etc.)?

## Reversion and related branches
- [ ] Please describe any special issues that might come up if a reversion is needed.
- [ ] Please list any other branches you might have included besides `master`, to help with merging and reversions.

# Other Notes
* This section can be omitted as needed.

# Related Issue(s)
* #123 (Github ticket number)
