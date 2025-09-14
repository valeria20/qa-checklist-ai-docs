# Security Policy

Our app is built on Atlassian Forge, which provides secure infrastructure, storage, and authentication managed by Atlassian. We do not log or permanently store Jira issue content outside Atlassian services. Limited issue data (summary and description) is sent to OpenAI for processing to generate checklists. This data is processed transiently and not retained.

## Security Principles

- End-User Data is never logged or stored outside Atlassian services  
- All requests are authenticated through Atlassian’s standard mechanisms  
- Data in Forge storage is encrypted at rest and in transit by Atlassian  
- Access to stored data is restricted to authorized users within the Jira site  
- Upon uninstallation, all stored data is deleted automatically  

## Contact

For questions or to report a security concern, please contact: **sholomova96@gmail.com**
