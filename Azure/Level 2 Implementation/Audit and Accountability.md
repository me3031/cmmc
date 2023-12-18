The following table provides a list of practice statement and objectives, and Microsoft Entra guidance and recommendations to enable you to meet these requirements with Microsoft Entra ID.

|CMMC practice statement and objectives|Microsoft Entra guidance and recommendations|
|---|---|
|AU.L2-3.3.1  <br>  <br>**Practice statement:** Create and retain system audit logs and records to enable monitoring, analysis, investigation, and reporting of unlawful or unauthorized system activity.  <br>  <br>**Objectives:**  <br>Determine if:  <br>[a.] audit logs (for example, event types to be logged) to enable monitoring, analysis, investigation, and reporting of unlawful or unauthorized system activity are specified;  <br>[b.] the content of audit records needed to support monitoring, analysis, investigation, and reporting of unlawful or unauthorized system activity is defined;  <br>[c.] audit records are created (generated);  <br>[d.] audit records, once created, contain the defined content;  <br>[e.] retention requirements for audit records are defined; and  <br>[f.] audit records are retained as defined.  <br>  <br>AU.L2-3.3.2  <br>  <br>**Practice statement:** Ensure that the actions of individual system users can be uniquely traced to those users so they can be held accountable for their actions.  <br>  <br>**Objectives:**  <br>Determine if:  <br>[a.] the content of the audit records needed to support the ability to uniquely trace users to their actions is defined; and  <br>[b.] audit records, once created, contain the defined content.|All operations are audited within the Microsoft Entra audit logs. Each audit log entry contains a user’s immutable objectID that can be used to uniquely trace an individual system user to each action. You can collect and analyze logs by using a Security Information and Event Management (SIEM) solution such as Microsoft Sentinel. Alternatively, you can use Azure Event Hubs to integrate logs with third-party SIEM solutions to enable monitoring and notification.  <br>[Audit activity reports in the Azure portal](https://learn.microsoft.com/en-us/entra/identity/monitoring-health/concept-audit-logs)  <br>[Connect Microsoft Entra data to Microsoft Sentinel](https://learn.microsoft.com/en-us/azure/sentinel/connect-azure-active-directory)  <br>[Tutorial: Stream logs to an Azure event hub](https://learn.microsoft.com/en-us/entra/identity/monitoring-health/howto-stream-logs-to-event-hub)|
|AU.L2-3.3.4  <br>  <br>**Practice statement:** Alert if an audit logging process fails.  <br>  <br>**Objectives:**  <br>Determine if:  <br>[a.] personnel or roles to be alerted if an audit logging process failure is identified;  <br>[b.] types of audit logging process failures for which alert will be generated are defined; and  <br>[c] identified personnel or roles are alerted in the event of an audit logging process failure.|Azure Service Health notifies you about Azure service incidents so you can take action to mitigate downtime. Configure customizable cloud alerts for Microsoft Entra ID.  <br>[What is Azure Service Health?](https://learn.microsoft.com/en-us/azure/service-health/overview)  <br>[Three ways to get notified about Azure service issues](https://azure.microsoft.com/blog/three-ways-to-get-notified-about-azure-service-issues/)  <br>[Azure Service Health](https://azure.microsoft.com/get-started/azure-portal/service-health/)|
|AU.L2-3.3.6  <br>  <br>**Practice statement:** Provide audit record reduction and report generation to support on-demand analysis and reporting.  <br>  <br>**Objectives:**  <br>Determine if:  <br>[a.] an audit record reduction capability that supports on-demand analysis is provided; and  <br>[b.] a report generation capability that supports on-demand reporting is provided.|Ensure Microsoft Entra events are included in event logging strategy. You can collect and analyze logs by using a Security Information and Event Management (SIEM) solution such as Microsoft Sentinel. Alternatively, you can use Azure Event Hubs to integrate logs with third-party SIEM solutions to enable monitoring and notification. Use Microsoft Entra entitlement management with access reviews to ensure compliance status of accounts.  <br>[Audit activity reports in the Azure portal](https://learn.microsoft.com/en-us/entra/identity/monitoring-health/concept-audit-logs)  <br>[Connect Microsoft Entra data to Microsoft Sentinel](https://learn.microsoft.com/en-us/azure/sentinel/connect-azure-active-directory)  <br>[Tutorial: Stream logs to an Azure event hub](https://learn.microsoft.com/en-us/entra/identity/monitoring-health/howto-stream-logs-to-event-hub)|
|AU.L2-3.3.8  <br>  <br>**Practice statement:** Protect audit information and audit logging tools from unauthorized access, modification, and deletion.  <br>  <br>**Objectives:**  <br>Determine if:  <br>[a.] audit information is protected from unauthorized access;  <br>[b.] audit information is protected from unauthorized modification;  <br>[c.] audit information is protected from unauthorized deletion;  <br>[d.] audit logging tools are protected from unauthorized access;  <br>[e.] audit logging tools are protected from unauthorized modification; and  <br>[f.] audit logging tools are protected from unauthorized deletion.  <br>  <br>AU.L2-3.3.9  <br>  <br>**Practice statement:** Limit management of audit logging functionality to a subset of privileged users.  <br>  <br>**Objectives:**  <br>Determine if:  <br>[a.] a subset of privileged users granted access to manage audit logging functionality is defined; and  <br>[b.] management of audit logging functionality is limited to the defined subset of privileged users.|Microsoft Entra logs are retained by default for 30 days. These logs are unable to modified or deleted and are only accessible to limited set of privileged roles.  <br>[Sign-in logs in Microsoft Entra ID](https://learn.microsoft.com/en-us/entra/identity/monitoring-health/concept-sign-ins)  <br>[Audit logs in Microsoft Entra ID](https://learn.microsoft.com/en-us/entra/identity/monitoring-health/concept-audit-logs)|