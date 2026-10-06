# IIS Monitor: inspect website activity and HTTP errors

## Start an IIS monitoring session

1. Request the **IIS Compatibility Tester** through [support](SUPPORT.md) before purchasing, and check the intended Windows IIS server.
2. Obtain the portable application and license through the [official product page](https://aicreatenow.com/IISMonitor.html).
3. Activate using the supplied 10-digit code and complete the initial online verification.
4. Select the discovered IIS websites you want to include and start monitoring.
5. Review selected-site activity and server resources, then stop the session cleanly before reviewing or packaging the final reports.

## Investigate an HTTP-error spike

Use the HTTP-error and content tables to identify the affected site, status and time period. Compare that interval with server-resource changes and the site's normal operational logs. An error count is a starting point for investigation; it does not by itself establish the cause.

The application keeps detailed CSV, TXT and JSON reports and can package a monitoring session as a ZIP. Include the relevant session interval when requesting help.

## Common questions

**Does monitoring reconfigure IIS?** No. It does not change websites, application pools, bindings, firewall rules or official IIS logs.

**Why can Cloudflare show more traffic than IIS?** Content served entirely from Cloudflare's cache does not reach the IIS server. IIS Monitor measures activity at the origin server.

**Are connections the same as visitors?** No. Connection counts are not unique visitor counts. Completed requests appear after IIS finishes processing them.

**How often does the dashboard update?** Dashboard updates occur every three seconds. Review the completed session reports for the recorded detail.

Share only the diagnostic information needed for a support case and remove credentials and unrelated customer information before sending logs.

[Back to product overview](README.md) · [Support](SUPPORT.md)
