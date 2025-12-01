# API Documentation

## Endpoints
### Case Intake
- **Description**: Collect, validate and normalize care plans from CPOE; attach a runId and timestamp for traceability.
- **Type**: Processing

### Delegate
- **Description**: Execute delegate phase for the Multi-Agent pattern: persist interim state, enforce guardrails, and emit structured JSON results.
- **Type**: Processing

### Handoff
- **Description**: Execute handoff phase for the Multi-Agent pattern: persist interim state, enforce guardrails, and emit structured JSON results.
- **Type**: Processing

### Monitoring
- **Description**: Monitoring across joined datasets; branch on thresholds using decision gates; write metrics (success/error counts) for observability.
- **Type**: Processing

### Eligibility Match
- **Description**: Eligibility Match across joined datasets; branch on thresholds using decision gates; write metrics (success/error counts) for observability.
- **Type**: Processing

### Normalization
- **Description**: Normalization across joined datasets; branch on thresholds using decision gates; write metrics (success/error counts) for observability.
- **Type**: Processing

### Documentation
- **Description**: Documentation across joined datasets; branch on thresholds using decision gates; write metrics (success/error counts) for observability.
- **Type**: Processing

### Intervention
- **Description**: Intervention across joined datasets; branch on thresholds using decision gates; write metrics (success/error counts) for observability.
- **Type**: Processing

### Optimization
- **Description**: Optimization across joined datasets; branch on thresholds using decision gates; write metrics (success/error counts) for observability.
- **Type**: Processing

### Compliance Report
- **Description**: Assemble final payload with status, artifacts, KPIs and audit trail; store to CPOE; return response JSON for the client.
- **Type**: Processing
