# Disaster-Recovery Test Plan Template

## 1. Test Overview

| Field | Value |
|---|---|
| Test reference | |
| Service or application | |
| Business owner | |
| Technical lead | |
| Planned date and duration | |
| Approved change reference | |
| Test type | Tabletop / Component / Application / Full service |
| Recovery location | |

## 2. Objectives

- Validate the documented recovery sequence.
- Measure actual Recovery Time Objective (RTO).
- Confirm the selected restore point meets Recovery Point Objective (RPO).
- Validate infrastructure, application and business-service dependencies.
- Produce evidence and corrective actions.

## 3. Scope

### Included

- Workloads:
- Data:
- Infrastructure components:
- Teams:

### Excluded

- Production changes not approved for the exercise:
- External services:
- Destructive failover activities:

## 4. Dependencies

| Dependency | Owner | Validation Method | Status |
|---|---|---|---|
| Identity and access | | | |
| DNS and network | | | |
| Compute and virtualization | | | |
| Storage | | | |
| Backup or replication | | | |
| Database and application | | | |
| Monitoring and communications | | | |

## 5. Entry Criteria

- [ ] Scope, roles and decision authority approved
- [ ] Recovery point identified
- [ ] Required credentials and access tested
- [ ] Target capacity confirmed
- [ ] Network and security paths validated
- [ ] Backup catalog and media availability confirmed
- [ ] Stakeholders notified
- [ ] Rollback and cleanup steps approved

## 6. Planned Sequence

| Step | Activity | Owner | Expected Duration | Validation |
|---:|---|---|---:|---|
| 1 | Declare exercise start | | | |
| 2 | Prepare recovery target | | | |
| 3 | Restore infrastructure or data | | | |
| 4 | Start required services | | | |
| 5 | Validate dependencies | | | |
| 6 | Complete application testing | | | |
| 7 | Obtain business validation | | | |
| 8 | Restore monitoring and protection | | | |
| 9 | Complete cleanup and closure | | | |

## 7. Communications

| Event | Audience | Method | Owner |
|---|---|---|---|
| Exercise start | | | |
| Material issue or delay | | | |
| Technical recovery completed | | | |
| Business validation completed | | | |
| Exercise closed | | | |

## 8. Success Criteria

- [ ] Recovery completed within RTO
- [ ] Restore point satisfies RPO
- [ ] Data and application validation passed
- [ ] Security and access controls validated
- [ ] Monitoring and backup protection restored
- [ ] Evidence recorded
- [ ] Actions assigned with owners and due dates

## 9. Final Result

Overall result: **Pass / Pass with actions / Fail**

Summary:

Residual risks:

Next test date:
