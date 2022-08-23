# iog-dba-weeklyrelease-service
IOG DBA Weekly Release Service
===================================
Overview
Provide resource to run needed database MySQL scripts weekly for HPCC/Backoffice releases as requested by application teams. 
Process
DBA team receives list of tickets on Tuesday as part of JIRA DBA Weekly Backoffice Master Release JIRA ticket. Set of DBAs responsible for weekly release will review list of tickets for accurate information and then review the sql scripts attached to the request to see if they are accurate and valid. DBA will then run the scripts in lower non-prod envs for application teams for testing. DBA will then look for BU Approvals to run the requested scripts in Production on Wednesday nights as part of weekly release agreement.  Some tickets require to be ran over weekend due to size of tables needing alterations.
Team
•	DBA members
SLI (Thing to Measure)	SLO (Team Goals)	SLA (Guarantees to Users)
Availability	99% W-Th (10PM-6AM) EST
99% F-M (10PM-6AM) EST
	95% M-F (10PM-6AM) EST
95% Fri-Mon (10PM-6AM) EST
Completion	99.9% W-Th (10PM-6AM) EST
5% F-M (10PM-6AM) EST	95% to be completed by 6AM Thursday
4% to be completed by following Monday morning 6AM that are too large to run on Wed evening and require weekend.
1% to be completed after Monday morning 
Accuracy	99% for scripts provided	95% based on scripts provided and reviewed

 
