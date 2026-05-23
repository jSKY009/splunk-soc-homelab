# Splunk SOC Home Lab — Windows Security Log Analysis

## Project Overview
A hands-on SOC analyst home lab project using Splunk Enterprise to ingest, 
analyse, and investigate Windows system security logs. This project demonstrates 
core SOC skills including SIEM deployment, SPL querying, anomaly detection, 
timeline analysis, and formal incident reporting.

## Tools Used
- Splunk Enterprise 10.4.0
- Splunk Processing Language (SPL)
- Windows System Logs (CBS Event Data)
- macOS — MacBook Pro 2018

## What I Did
- Deployed Splunk Enterprise locally and ingested 1,744 Windows security events
- Wrote SPL queries to identify errors, warnings, and failure patterns
- Discovered anomalous after-hours activity spikes at 02:00 and 04:00
- Found 370 events (21.2%) classified as warnings or failures
- Identified repeated CBS_E_MANIFEST_INVALID_ITEM errors indicating potential 
  failed patch application or update tampering
- Built a 3-panel Splunk security monitoring dashboard
- Produced a formal incident analysis report

## Key Findings
- Anomalous activity spikes outside business hours (02:00 and 04:00)
- 21.2% error rate during spike period
- Persistent Windows update component failures across multiple dates

## Files
- `Incident_Report_Windows_Log_Analysis.pdf`  Full incident report
- `screenshots/`  Evidence screenshots from the investigation

## Skills Demonstrated
SIEM | Splunk | SPL | Log Analysis | Anomaly Detection | 
Incident Reporting | Windows Event Logs | Security Monitoring
