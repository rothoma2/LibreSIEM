# Problem Statement

SIEM are important Security Tools. SIEM systems aggregate security events in a single console for Analyst to be able to identify, triage, threat hunt and review security events.
As Systems Complexity Increases SIEM tools become a more critical central component of Secure Systems. 

However we feel currently state of Open Source and SIEM markets lacks of Proper Modern Open Source SIEM tool. Commercial SIEM tools are expensive and out of reach for a lot of Organizations.
Splunk and other Commercial Tools, but Specially Splunk are so expensive the World is a more insecure place as a result.

Some of the items that we idenfity as problems with most current Open Source SIEM. Most SIEM Like Solutions are centralized Log Collectors with Dashboards and Stored Search. Most of them currently operate on the following way:

- Aggregate Text Based Security Logs in a Single Storage. Usally Lucene Derived Index such as (ELK).
- Have some sort of "stored Searches" that allow to search for specific patterns, or "higher priority events"
- Have some level of Dashboards, that provide graphs on top of the "stored searches" for a series of events.

Most of the current solutions we have evaluated (Wazuh, ELK Siem, SIEMonster) Lack the following Capabilities:

- Require Large amount of Humman Hours to manually review Security Events by Analyst.
- Lack of Transformation of Security Event into a Unified Event Models that is easy to parse, read, search.
- Lack Mapping to Cyber Kill Chain Stage and Tactics such as MiTTRE Framework.
- Lack of Clustering of Meaningfull events to Separate Security Incidents from isolated noise activity.
- Lack of Advanced MAchine Learning for Outlier Analysis, and Anomalous Behaviour.
- Lack of Structured Workflow for Security Incident Investigation and Response.
- Lack of Grouping of Suspected Related events to a Security Incident.
- Lack of Explainability derived from Recent Advancements in Large Language Models AI.
- Lack of Open OSSINT Indicator of Compromise and Feed Integration.
- Lack of Auto Response Playbook integration.  

The Challenge with this are the following:

- Focus is mostly on collecting an reporting a large amount of Events.
- Implicitly expected Analyst to Review all, or a large portion of the Events.
- Analyst still need to perform Investigations, Extract incidents and Identify Kill Chains Manually.
- Lack of Auto Discovery of Malicious, or Anomalous Behaviour.
- Lack of Overall Kill Chain Visibility and prioritization.

We believe an Open Source SIEM, built on top of existing Open Source Log Collectors, will be a net benefit to the Open Source Community and to make the world a Safer Place.

# Mission Statement.

Make the World a Safer Place through the combination of Centralized Security Event Monitoring and recent Advancements on AI built with Open Source Technologies.

# Vision Statement.

Become the DeFacto Modern Open Source SIEM solution.
