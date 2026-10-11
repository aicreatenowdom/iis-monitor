# Get started with ServerSight Pro

See the activity reaching your Windows IIS server, investigate HTTP errors and keep local session reports.

## Install and choose your access

1. Check that the computer runs **64-bit Windows with IIS**, **.NET Framework 4.8 or newer**, and the monitoring components and existing W3C logging fields required for your measurements. Administrator access is required. See [system requirements](https://serversightpro.com/download.html) and [setup help](https://serversightpro.com/help.html#requirements).
2. Download the [ServerSight Pro 3.0.20 Windows installer](https://download.aicreatenow.com/software/ServerSightPro3.0.0.20microsoft2.exe). Before installing, check the file's **Properties → Digital Signatures** for **AI Creations Now Software Development**.
3. Run Setup, review the installation and privacy information, and launch the installed application.
4. Choose **Start Two-Day Free Trial**, or enter your delivered **10-digit license key**. The trial starts only when you explicitly choose to start it; installing alone does not start the clock. Initial license activation requires Internet access.

Setup does not install IIS or enable missing counters and logging fields. Available measurements depend on the Windows/IIS components and log fields already present.

## Record your first session

1. Select the discovered IIS websites you want included.
2. Choose a recording duration: **1, 6, 12, 24, 48, 72 or 168 hours**.
3. Select **Start Monitoring** and explore the six main views.
4. Use **Stop & Finalize** to end the session early when you have the evidence you need.
5. Review the saved CSV, TXT and JSON reports. Package a finalized session as a ZIP if you want to share it.

Results are normally saved in the application's results folder on your Desktop. Monitoring results are not automatically uploaded. The application does not provide native PDF or HTML report export.

Sessions extending beyond the trial's 48-hour deadline require activation. Available storage, Windows uptime and other interruptions also affect recording. Minimizing keeps the monitoring worker running; a normal application close finalizes the session and removes the product-owned worker.

## Investigate an HTTP-error spike

Open **Requests & Errors**, filter HTTP 4xx/5xx responses and identify the affected site, status and time period. Read the status explanation and suggested action, then compare the interval with resource changes in **Live Overview** and the site's ordinary operational logs.

An error count is a starting point for investigation; it does not establish the cause by itself. Include the relevant session interval when requesting help, and review exported reports for sensitive data before sharing.

## Common questions

**Does monitoring reconfigure IIS?**  
No. It reads existing evidence without changing websites, application pools, bindings, logging fields, firewall rules, DNS or original IIS logs. It creates its own monitoring files, worker and licensing state.

**Why can Cloudflare show more traffic than the application?**  
Requests served entirely from a CDN cache do not reach IIS. ServerSight Pro shows origin evidence and separate server-network measurements. Public external connections can include Cloudflare proxy connections.

**Are connections the same as visitors?**  
No. A browser, person or proxy can establish several connections. Connection counts are not unique human visitor counts.

**Why do network and IIS byte totals differ?**  
Physical-adapter traffic includes other applications, protocols and LAN activity. Completed IIS totals come from existing records for your selected sites. Their scopes are different.

**How often does the display update?**  
Core telemetry updates every three seconds. Detailed live tables publish up to once a minute when changed, and at finalization. Completed request details become available after IIS processing is recorded in the existing logs.

**Why is a field unavailable?**  
Coverage depends on available counters and existing IIS logging fields. Missing data is not proof of zero activity. Individual request detail may be sampled at high load.

**When does the free trial end?**  
It lasts 48 elapsed hours from your explicit trial start, including time while the app is closed. At expiry, recording stops and finalization is requested. Saved results remain on disk. Reinstalling does not restart the trial.

**How do I activate?**  
Purchase a [$39.99 lifetime license for one computer](https://buy.stripe.com/5kQdRb77Z28UfME5ZQ5kk03), then enter the delivered 10-digit key in the application. You can activate before the trial, during it from **Safety & Help**, or after it expires. Payment alone does not activate the software. Hardware or Windows changes can require reactivation.

**What remains after uninstalling?**  
Ordinary uninstall removes installed application files and shortcuts after product-owned recording is stopped and finalized. Saved Desktop results and separate trial and registration records remain. Original IIS and Windows logs are not removed.

[Full help & measurement guidance](https://serversightpro.com/help.html) · [Privacy information](https://serversightpro.com/privacy.html) · [Support](SUPPORT.md) · [Back to overview](README.md)
