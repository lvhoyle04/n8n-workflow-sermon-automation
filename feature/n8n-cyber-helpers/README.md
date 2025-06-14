# n8n Cyber Helper Workflows

This branch contains auxiliary n8n automation workflows developed during my internship. These tools extend the main sermon publishing automation system with a focus on security, resilience, and utility. Each workflow is modular and can be adapted or repurposed for general use.

## Included Workflows

### 1. IP Reputation Checker
Queries third-party APIs like AbuseIPDB or VirusTotal to check the trustworthiness of an IP address.

### 2. Email Verification & Filtering
Uses email verification APIs (e.g., NeverBounce) to validate email addresses and flag temporary or risky domains.

### 3. Rate Limit & Usage Audit
Tracks user or IP behavior on webhook endpoints. Detects usage spikes, potential DDoS behavior, or abuse patterns.

### 4. Credential Vault & API Key Rotation
Logs API key expirations and automates alerting and rotation scheduling to reduce security risks.

### 5. OSINT Surveillance Workflow
Periodically scans news, blogs, forums, and search engines for mentions of key terms, such as your church, organization name, or domain.

### 6. Failover Logic Middleware
Implements redundancy logic for critical nodes. Routes workflows to backup APIs or secondary workflows if failures are detected.

---

## Structure

Each workflow is stored as a JSON export from n8n and accompanied by a helper `.md` file describing:

- Workflow purpose
- Node-by-node breakdown
- API credentials required
- Environment variables (if any)

---

## Usage

These workflows are not deployed by default in the live production pipeline but are intended to:
- Strengthen cybersecurity posture
- Support observability
- Add administrative tooling for future automation expansions

---

## Author

**Lukas Hoyle**  
Cybersecurity Major | Anderson University  
Intern at Five More Talents  
