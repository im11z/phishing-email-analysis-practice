## SPF / DKIM / DMARC Analysis

### Sample 1
- SPF: Fail (unauthorized sending IP)
- DKIM: Missing signature
- DMARC: Policy alignment failed

### Impact
Failure of all three authentication mechanisms confirms spoofing.
