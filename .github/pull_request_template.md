---
name: Data Model Pull Request
about: Propose a change to a dbt data model
title: 'type(scope): A short description of the change'
labels: 'data-model'
---

### Description

*A clear and concise summary of the change and the business reason behind it. Why is this change necessary? What problem does it solve?*

---

### Type of Change
*Please check the boxes that apply.*
- [ ] New data model (feature)
- [ ] Model enhancement (feature)
- [ ] Bug fix (non-breaking change which fixes an issue)
- [ ] Refactor (non-breaking change which improves code quality)
- [ ] Documentation update

---

### Related JIRA Ticket / Task ID

*Link to the relevant task, e.g., [PROJ-1234]*

---

### Data Models Affected
*List the key models being created, modified, or downstream models that will be impacted.*
- `models/ingest/...`
- `models/staging/...`
- `models/curated/...`

---

### Testing Done
*Describe the tests you ran to verify your changes. Be specific.*
- [ ] `dbt build` ran successfully.
- [ ] `dbt test` passed on all modified models.
- [ ] Manually queried the development tables to validate data integrity.
- [ ] Compared row counts before and after the change.

---

### Reviewer Checklist
- [ ] The code follows the team's style guide.
- [ ] The change solves the intended problem.
- [ ] The documentation has been updated accordingly.

---

### Tags
*[e.g., #invoice, #cost, #finance]*
