# ISAC Email Processing with Copilot for Security
Author: Chaitanya Belwal

In this Logic App ISAC emails containing CVEs are processed by analyzing the mailbox, extracting the CVEs and using Copilot for Security the presense of those CVEs are analyzed in your environment. 

The information for CVEs detected in your environment is then enriched with data from MDTI and consolidated HTML report is then emailed to one of more specified mailbox(es).

This way the generic ISAC email that contains a list of CVEs is converted to an actionable email containing only the CVEs that exist in your environment. The CVE information if further enriched with relevant information from Microsoft Defender Threat Intelligence.

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2FCopilot-For-Security%2Fmain%2FLogic%2520Apps%2FISAC-Email-Processing%2Fazuredeploy.json" target="_blank">
<img src="https://aka.ms/deploytoazurebutton"/>
</a>



<br>
