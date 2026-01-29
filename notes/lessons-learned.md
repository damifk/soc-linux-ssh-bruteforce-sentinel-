# Lessons Learned

## Technical
- Azure Monitor Data Collection Rules are the modern and preferred ingestion method for Linux logs
- Linux auth and authpriv syslog facilities provide strong signals for SSH attack detection
- Small KQL optimisations significantly reduce false positives
- Sentinel analytics rules integrate seamlessly with Defender XDR incidents
- Logic Apps provide flexible and reliable SOAR capabilities

---

## Operational
- Cloud security tooling often enforces regional and policy constraints
- Working within guardrails is a realistic SOC skill
- Verifying log ingestion early prevents wasted effort later
- Detection logic matters more than tooling complexity

---

## Improvements for Future Iterations
- Correlate failed logins by source IP
- Identify distributed brute-force attempts
- Add geo-location enrichment
- Automate response actions such as blocking IPs
