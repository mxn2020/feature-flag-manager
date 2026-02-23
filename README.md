# Feature Flag Manager

## Pages & Features

### 1. Dashboard
- Total flags count (active, inactive, stale)
- Recent flag changes feed
- Flags nearing expiry / cleanup
- Environment overview (production, staging, dev)
- Quick toggle shortcuts

### 2. Flags
- Flag list with search, environment, status, tag filters
- Create flag (key, name, description, type: boolean/string/number/JSON)
- Flag detail: status per environment, targeting rules, history
- Toggle flag on/off per environment
- Archive / delete flags
- Flag lifecycle (created → active → stale → archived)

### 3. Targeting Rules
- User segment targeting (by user ID, email, attribute)
- Percentage rollout (0–100%)
- Rule builder (IF attribute = value THEN serve variant)
- Default & fallback values
- Priority ordering of rules
- Test rules with user preview

### 4. Environments
- Environment management (production, staging, dev, custom)
- Per-environment flag state
- Promote flag config between environments
- Environment-specific API keys

### 5. Segments
- Define user segments (beta users, internal, enterprise, etc.)
- Segment rules (attribute-based membership)
- Reuse segments across flags
- Segment member preview

### 6. Audit Log
- Complete history of flag changes (who, what, when)
- Filter by flag, user, action, date
- Diff view of configuration changes
- Export audit log

### 7. Experiments (A/B Testing)
- Create experiment linked to flag variants
- Define metrics to track (conversion, engagement)
- Experiment results with statistical significance
- Declare winner & roll out

### 8. SDKs & Integration
- SDK installation guides (JS, React, Node, Python, etc.)
- API key management
- Code snippets for each flag
- Webhook configuration for flag changes

### 9. Reports
- Flag usage across environments
- Stale flag identification
- Rollout history & impact
- Experiment results summary

### 10. Settings
- Organization profile
- Team members & roles (admin, developer, viewer)
- Approval workflows for production changes
- Default flag settings
- Notification preferences
