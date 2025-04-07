# Business-Workflow-Observability-Platform-on-Azure
- This project mainly focused on designing and developing an **Integration Platform as a Service (IPaaS)** for the workflows modernized during the Workflow Integration and Modernization project, focusing on Logging, Monitoring, and Alerting.
## Architecture
![architecture](https://github.com/Chennakesava-Avvaru/Business-Workflow-Observability-Platform-on-Azure/blob/main/IPaaS.drawio.png)
- This is the centralized subscription where any subscription can connect to this and maintain the logs and get alerts whenever the workflows will fail.
- All the business workflows hosted on different azure serviecs will connect to the Log analytical workspace through the diagnostic settings and save and maintain all the logs and metrics of those workflows.
- We have developed an instant alerting system where the concerned group of team will get alerts through the outlook mail, microsoft teams and servicenow ticketing will also be created for troubleshooting that issue for workflow failure.
- Azure logic apps will run every 5 min and check the logs based on the KQL and pass them into the Kibana for monitoring and dashboarding.
## Technologies Used
- Azure Logic Apps
- Liquid Templates
- REST API
- Log Analytics workspace
- KQL
- Application Insights
- Kibana
## Achivements & contributions
- Streamlined operations with detailed logging and monitoring dashboards, automated alerts via email and Microsoft Teams, and reduced resolution time for critical issues by 60%.
