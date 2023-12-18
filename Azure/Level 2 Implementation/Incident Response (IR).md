The following table provides a list of practice statement and objectives, and Microsoft Entra guidance and recommendations to enable you to meet these requirements with Microsoft Entra ID.

|CMMC practice statement and objectives|Microsoft Entra guidance and recommendations|
|---|---|
|IR.L2-3.6.1  <br>  <br>**Practice statement:** Establish an operational incident-handling capability for organizational systems that includes preparation, detection, analysis, containment, recovery, and user response activities.  <br>  <br>**Objectives:**  <br>Determine if:  <br>[a.] an operational incident-handling capability is established;  <br>[b.] the operational incident-handling capability includes preparation;  <br>[c.] the operational incident-handling capability includes detection;  <br>[d.] the operational incident-handling capability includes analysis;  <br>[e.] the operational incident-handling capability includes containment;  <br>[f.] the operational incident-handling capability includes recovery; and  <br>[g.] the operational incident-handling capability includes user response activities.|Implement incident handling and monitoring capabilities. The audit logs record all configuration changes. Authentication and authorization events are audited within the sign-in logs, and any detected risks are audited in the Identity Protection logs. You can stream each of these logs directly into a SIEM solution, such as Microsoft Sentinel. Alternatively, use Azure Event Hubs to integrate logs with third-party SIEM solutions.  <br>  <br>**Audit events**  <br>[Audit activity reports in the Azure portal](https://learn.microsoft.com/en-us/entra/identity/monitoring-health/concept-audit-logs)  <br>[Sign-in activity reports in the Azure portal](https://learn.microsoft.com/en-us/entra/identity/monitoring-health/concept-sign-ins)  <br>[How To: Investigate risk](https://learn.microsoft.com/en-us/entra/id-protection/howto-identity-protection-investigate-risk)  <br>  <br>**SIEM integrations**  <br>[Microsoft Sentinel : Connect data from Microsoft Entra ID](https://learn.microsoft.com/en-us/azure/sentinel/connect-azure-active-directory)[Stream to Azure event hub and other SIEMs](https://learn.microsoft.com/en-us/entra/identity/monitoring-health/howto-stream-logs-to-event-hub)|