# Office 365 Forensic and IR Tools

# o365auditor.py

This is a WORK IN PROGRESS.  DO NOT assume the results produced by this script are complete.  In some cases I already know they are not.

It's also easier to ingest these logs into ELK. This was more for playing around.

Takes in exported (csv) Office 365 audit logs and parses the JSON into a more readable format.

    python o365auditor.py -f AuditLogs.csv -o myauditlogs
