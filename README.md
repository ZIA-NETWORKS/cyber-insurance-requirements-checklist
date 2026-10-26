# cyber-insurance-requirements-checklist
Cyber insurance requirements checklist: the security controls insurers now expect before they’ll write or renew a policy. Maintained by ZIA Networks.
# Cyber Insurance Requirements Checklist

> Cyber insurance is getting harder to get. This checklist covers the security controls insurers now expect to see before they approve or renew a policy.

Maintained by **ZIA Networks**.

## Why this exists

Ransomware claims became more frequent and far more expensive, and insurers responded by tightening their rules. Many businesses now face long security questionnaires, higher premiums, reduced limits, or non-renewal, even with a clean claims history.

Underwriters also verify answers themselves. Many run external scans of your domains and public IP addresses and compare the results with your application. If the two don't match, expect trouble.

The cyber insurance requirements below come up again and again. Use this list as a self-assessment before your next renewal.

## How to use this checklist

1. Fork or copy this README.
2. Tick each item that is **fully in place and provable**. If you can't show evidence, leave it unticked.
3. Fix the high-impact items first (sections 1 to 3).
4. Save your evidence (screenshots, reports, policies) in one folder for the underwriter.

## The checklist

### 1. Multi-factor authentication (MFA)
- [ ] MFA on email and cloud applications
- [ ] MFA on remote access (VPN, remote desktop)
- [ ] MFA on all administrator and privileged accounts
- [ ] MFA protecting access to backups

**Why it matters:** Stolen credentials drive a large share of breaches. Many carriers won't offer a policy without MFA.

### 2. Endpoint detection and response (EDR)
- [ ] EDR or managed detection and response (MDR) on all laptops, desktops, and servers
- [ ] Alerts are monitored by a person or a service, not just collected
- [ ] Legacy antivirus-only machines have been replaced or upgraded

### 3. Backups that survive ransomware
- [ ] Backups are offline, immutable, or separated from the main network
- [ ] Backup access is protected with MFA
- [ ] A full restore has been tested in the last 6 to 12 months
- [ ] Restore results are documented

> A backup you have never restored is a hope, not a control.

### 4. Patch and vulnerability management
- [ ] Critical patches are applied within a defined window
- [ ] Vulnerability scans run on a regular schedule
- [ ] End-of-life software is removed or has a retirement plan

### 5. Email security and awareness training
- [ ] Email filtering for malicious links and attachments
- [ ] SPF, DKIM, and DMARC configured
- [ ] Regular staff security awareness training
- [ ] Phishing simulations run and results tracked

### 6. Privileged access management
- [ ] Separate admin accounts from daily-use accounts
- [ ] No shared logins
- [ ] Accounts removed promptly when staff leave
- [ ] Least-privilege access applied to sensitive data

### 7. Logging, monitoring, and incident response
- [ ] Security logs are collected and retained
- [ ] Someone reviews or monitors the logs
- [ ] A written incident response plan exists
- [ ] The plan has been rehearsed (for example, a tabletop exercise)

### 8. Network segmentation and remote access
- [ ] Critical systems are segmented from the general network
- [ ] Unnecessary open ports are closed
- [ ] Remote desktop is not exposed directly to the internet

## Scoring yourself

| Ticked items | What it suggests |
|---|---|
| 26 to 28 | Strong position. Gather evidence and apply early. |
| 18 to 25 | Decent base, but fix gaps before renewal. |
| Below 18 | Likely to face higher premiums or a decline. Prioritize sections 1 to 3. |

*This scoring is a rough guide, not an insurer's formula. Every carrier sets its own criteria.*

## Renewal preparation tips

- Request the questionnaire **months** in advance, not days.
- Be honest in your gap assessment.
- Answer application questions accurately. An incorrect answer can put a future claim at risk.
- Keep evidence organized: policies, test results, and training records.

## Need help?

**ZIA Networks** helps organizations understand what their insurer expects, close security gaps efficiently, and assemble the evidence underwriters want to see. We offer cyber insurance readiness reviews and ongoing managed security.

Contact: [https://www.zianetworks.net/blog/cyber-insurance-is-getting-harder-to-get-the-security-controls-insurers-now-require/]

## Contributing

Spotted a missing control or an outdated item? Open an issue or submit a pull request.

## Disclaimer

This checklist is for general information only. It is not legal, insurance, or financial advice, and requirements vary by insurer, region, and policy. Always confirm details with your broker or carrier.

## License

Released under the CC BY 4.0 license. Feel free to share and adapt with attribution to ZIA Networks.
