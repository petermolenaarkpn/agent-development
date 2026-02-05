# Quality Review Checklist

Complete this checklist before publishing any agent.

## Requirements &amp; Design

- [ ] Use case clearly documented in Project Tracker
- [ ] Target users identified
- [ ] Success criteria defined
- [ ] Duplicate check completed (documented in Project Tracker notes)
- [ ] Similar agents reviewed and justification for new agent documented

## Technical Implementation

- [ ] All topics have clear, complete descriptions
- [ ] Actions use appropriate connectors
- [ ] Error handling implemented for all actions
- [ ] Rate limits documented and considered
- [ ] Authentication configured correctly
- [ ] No hardcoded credentials or sensitive data

## User Experience

- [ ] Conversation flows tested with real users
- [ ] Fallback topics created for unhandled scenarios
- [ ] Tone appropriate for target audience
- [ ] Help and support guidance provided
- [ ] Clear escalation path if agent cannot help

## Documentation

- [ ] README.md complete with:
  - Overview of what agent does
  - How to use it
  - Examples
  - Known limitations
- [ ] CHANGELOG.md updated with version info
- [ ] knowledge-sources.md lists all data sources
- [ ] Agent Catalog entry created/updated
- [ ] GitHub repository updated

## Security &amp; Compliance

- [ ] No sensitive data in prompts or knowledge base
- [ ] Appropriate connector permissions configured
- [ ] User consent requirements met
- [ ] Compliance with data handling policies

## Testing

- [ ] Tested in Copilot Studio test pane
- [ ] Tested common user scenarios
- [ ] Tested error scenarios
- [ ] Verified with at least 2 different users

## Publishing

- [ ] Peer review completed (GitHub pull request)
- [ ] Reviewer name and date: _______________
- [ ] Agent Catalog status updated to "Published"
- [ ] Team notified via Teams channel
- [ ] Monitoring plan in place for first week

---

**Reviewer Signature**: _______________  
**Date**: _______________  
**Approval to Publish**: [ ] Yes [ ] No
