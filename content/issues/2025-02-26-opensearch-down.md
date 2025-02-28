---
title: OpenSearch Login Disabled
date: 2025-02-26 08:13:00
resolved: false
<!-- resolvedWhen: 2018-04-25 04:13:59 -->
# Possible severity levels: down, disrupted, notice
severity: disrupted
# affected:
#   - Staging Backend
#   - Production Backend
#   - Testing Backend
section: issue
---

<!-- _Resolved_ - -->
<!-- We believe all users experiencing issues have been able to connect at this time. {{< track "2018-05-25 05:54:00" >}} -->

<!-- _Monitoring_ - We believe the connectivity issues are being caused by an isolated ISP issue. We've had reports that swapping to Google DNS servers (see here; https://developers.google.com/speed/public-dns/docs/using) resolves the problem for users. {{< track "2018-05-25 04:40:00" >}} -->

_Investigating_ - AWS development opensearch instances keeps resetting its password after certain time.
