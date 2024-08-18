# Welcome to SOC_Automation_Lab

This lab is a fully integrated SOAR solution incorporating Wazuh & TheHive for case management. While I have created Wazuh and Hive on cloud, I have also utilized other tools such as Sysmon to help integrate the logs from windows client to Wazuh. 
Further Shuffle makes the ends meet by connecting Wazuh to the hive and also sends emails to the client if an alert was detected followed by a response setup. 

# Workflow
Wazuh monitors logs and detects potential security incidents, generating alerts based on predefined rules. These alerts are sent to Shuffle, which automates workflows by forwarding the alerts to The Hive. 
The Hive receives the alerts and automatically creates cases, enriching them with additional context for incident response. Once a case is created in The Hive, Shuffle can trigger further actions, such as sending email notifications to relevant stakeholders. This seamless workflow ensures quick detection, automated case management, and timely communication for effective incident resolution.

Check out my portfolio for this lab here: https://tejalbguttal1.wixsite.com/mysoclab
