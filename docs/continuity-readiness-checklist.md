# Continuity Readiness Checklist

Use this checklist during design reviews, operational handover and before a recovery exercise.

## Governance

- [ ] Critical services have named business and technical owners
- [ ] RTO and RPO targets are approved
- [ ] Recovery authority and escalation paths are documented
- [ ] Supplier and vendor contacts are current
- [ ] Change and incident processes cover recovery activities

## Architecture and Dependencies

- [ ] Application and infrastructure dependencies are mapped
- [ ] Identity, DNS, network and security dependencies are included
- [ ] Recovery sequencing is documented
- [ ] Capacity at the recovery target is sufficient
- [ ] Required licences, subscriptions and quotas are available

## Protection

- [ ] Backup and replication policies match the approved requirements
- [ ] Independent or immutable copies are maintained where required
- [ ] Backup catalog, keys and configuration are protected
- [ ] Retention and archival retrieval procedures are documented
- [ ] Capacity and failure alerts are monitored

## Procedures

- [ ] Recovery runbooks identify prerequisites and owners
- [ ] Commands and screenshots exclude embedded credentials
- [ ] Application-consistency requirements are documented
- [ ] Rollback, cleanup and return-to-service steps are included
- [ ] Procedures are reviewed after platform changes

## Testing

- [ ] File-level recovery is tested
- [ ] Application or full-workload recovery is tested
- [ ] RTO and RPO are measured rather than assumed
- [ ] Business owners validate recovered services
- [ ] Evidence and issues are recorded
- [ ] Corrective actions are tracked to closure

## Operational Handover

- [ ] Monitoring and alerting are active
- [ ] Support teams have access and training
- [ ] Recovery contacts and documentation locations are known
- [ ] Expiry dates for licences, certificates and credentials are monitored
- [ ] The next exercise is scheduled
