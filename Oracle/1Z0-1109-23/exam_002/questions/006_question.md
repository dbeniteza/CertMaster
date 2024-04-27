# An application is continously logging sensitive information, which needs to be configured with restricted access to this log data. Which of the following could be a solution?

> Log groups are considered as logical containers for logs. One of the key purposes of Log groups is to segregate logs based on purpose. Logs with sensitive data could be configured within a separate log group and IAM policies created to restrict access to that log group.

1. [ ] Transition all sensitive logs into Object Storage using Service Connector.
1. [ ] By default, OCI Logging identifies and restricts access to any sensitive logs.
1. [ ] Configure Notifications Topic to alert when any sensitive data is logged in to Logging Service.
1. [x] Choose separate logs group for sensitive logs and use IAM policies.