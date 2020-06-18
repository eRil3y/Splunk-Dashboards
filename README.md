# Splunk-Dashboards

Splunk custom built Dashboards

ePO Threat Events Dashboard:
- Dashboard to view McAfee ePO threat events, alerts, and detections. To modify for a different environment change the query to match the fields in your Splunk instance. I also added a time modification to my query to display events in EST so you can modify that as well to match your timezone.
- Tables displayed in dashboard are "ePO events by signature", "ePO events by event_description", and if any infected files were found the dashboard lists all of the files and information in a table "AV Detected Infected Files".
-Couldn't find any other dashboards to display the McAfee ePO data I wanted so I built this one.

Firepower Intrusion Events Dashboard:
- Shows Firepower intrusion events sorted by count. Change the query to match the fields in your Splunk environment. Created this as a simple and reliable view of intrusion events because the Firepower App by Cisco wouldn't always work or I would have to troubleshoot it so I needed a way to still easily look at intrusion events.
