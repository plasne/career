# Notable Projects

The following are notable projects I led or was involved in. These start with the most recent and work back through time.

## Transition to Office 365
* I managed the transition of more than 100 WSS, MOSS, SP2010, and Lotus Notes systems to SharePoint Online via Office 365. This involved almost 10,000 sites, about 4.5TB of data, and more than 100 applications. Since this was moved into a shared tenant model, all applications had to be redeveloped as SharePoint-Hosted and Provider-Hosted solutions.

## Standardized Solutions Framework
* Suitable business solutions often require significant customization but IT leadership is often very concerned about the time and cost of custom solutions. I implemented standards that both groups could live with in the form of a framework. The framework consisted of documentation, a configurator, sample projects, and significant custom code. By using the configurator, a BA could design a solution that is constrained to acceptable limits. The output is a detailed description that the developers can then implement. The implementation is very consistent from app to app, almost eliminating design, speeding development, and significantly reducing review and testing.

## Workflow Engine
* I designed and implemented a web service based workflow engine to take over all the workloads that had previously been SharePoint 2010, SharePoint 2013, Nintex, or K2 Appit workflows in the SPX environment. Maintaining our own code base and API for workflows significantly reduced the time to develop and debug workflows while providing a range of features that are not offered in other products. For example, each stage in a workflow could define field/role level permissions as those change throughout the process.

## Platform Services
* I developed an API for the development group to use that provided a consistent way to expose standard services to our SharePoint applications. This included things like a robust access control system, post office services, managing scheduled jobs, etc. This API reduced the development and code review time for custom solutions while improving the quality of the deliverables.

## Governance
* I designed and wrote several hundred pages of governance documentation for SPX around the configuration, management, usage, security, development, best practice, etc. for the enterprise SharePoint platform.

## CIO Business Review Process (Sogeti @ Bank of America)
* I developed a suite of automation tools for the Bank that allowed the monthly production of the CIO Scorecard to be largely automated.  The suite leveraged SharePoint 2010 and Office 2010 functionality including PerformancePoint, REST feeds, PowerPoint Add-Ins, Silverlight, and Web Services.  This was so well received by the IT CIO that they are in the planning phase to significantly expand the scope of the project and the groups that would use it.  This was also a high-profile case for Microsoft as it was one of the first big uses of SharePoint 2010 functionality.

## SharePoint 2010 Enterprise Planning (Sogeti @ SPX)
* SPX has 7 SharePoint 2007 and WSS 3.0 farms that are used by their more than 15,000 employees, but the sophistication and usability of the environments is very low.  I worked with their IT staff and the business for 3 months to plan an effective SharePoint 2010 consolidation of all their farms that leverages a strong Governance and Information Architecture plan.  The project will move into the implementation phase in Dec 2010 or Jan 2011.

## Microsoft Enterprise Agreement
* I worked for more than 4 months as the primary on crafting a new $4.5 million, 3-year Enterprise Agreement.  This included discovery of our existing liability, contracts, and licenses, building models of options, justification for the Board, and vetting vendors.  After the agreement was signed, I was the primary administrator for all Microsoft agreements and services including the EA, Professional Services, and Dedicated Service Engineer and responsible for all reporting of our licensing to our business units and the roll-out of Microsoft software across the corporation.

## Corporate Intranet (MedWeb)
* I designed, coded, and implemented 4 iterations of our company Intranet (ASP, COM+, .NET, ASP.NET) over 10 years.  This is used by over 6,000 employees, contains more than 25,000 documents, and features dozens of applications, electronic forms, and reports.

## User/Group Automation
* I designed, coded, and implemented 3 iterations of tools (.NET WinForm, Web Services, Windows Service) to manage user account automation for Active Directory over 8 years.  The system handles user creation, property synchronization from multiple sources, account renames, company moves, status changes, termination, disposition of resources (email and home directory) for review, deletion, and many other tasks. The system provides Role-Based Access Control determined by properties from a variety of sources (SQL, LDAP, SharePoint Lists, SharePoint Groups, Web Services, etc.).  It can then disposition that membership information to Active Directory groups, SharePoint Groups, or a custom Web Service.

## Information Technology Insights
* I designed, coded, and implemented 2 iterations of tools (SharePoint/Web Services/Excel, .NET WinForm/SSAS/PerformancePoint) to manage computer software and hardware inventory over 3 years.  The system pulls data from SCCM and Active Directory, normalizes it, and dumps it into a data warehouse.  From there I cubed the data and then built dashboards (with drill-through to supporting evidence) so we can monitor operational metrics as well as report information around hardware and software compliance.

## Avaya VoIP Phone System
* I compared VoIP phone solutions for a long-term corporate-wide rollout from Cisco, ShoreTel, Nortel, and Avaya.  This was a considerable technical examination of all platforms around how we could integrate that technology with our existing Microsoft solutions.  We wanted to deliver a complete solution to the user's desktop using only Microsoft tools (Outlook and Communicator) but still have complete call control and handling.  I managed the product roll-out across the 3 sites that initially adopted this platform.  I also wrote all the documentation and provided all training for 2 of the sites.  This 3 site deployment was close to a million dollar deal.

## Strategic Plans
* I researched the Microsoft Operations Framework (MOF) and Standardized Systems Management (SSM) methodologies and put together a 3 step (roughly 5 year) strategic plan for improving our IT operations.  I could not find an Information Management framework that fit what we were trying to do, and so also wrote a framework around that.  For the past two years, we used those plans to formulate yearly tactical plans and benchmarked against the larger schedule.  I also wrote a MedCath-specific MOF documentation template for our administrators to use for each Service IT provided.

## SOX Audit
* I designed, coded, and implemented a solution for our quarterly SOX audits that ingests user access lists from various system reports, builds Excel spreadsheets with the data, provides additional information from the directory (whether or not the employees are still employed, whether their account information matches what it should, etc.), collects approvals from the appropriate people, sends reminder and escalation emails, and finally reports on the results.  This SharePoint solution was designed to keep the CFOs (data owners) in a familiar application (Excel) but still provide non-repudiation and a high degree of back-end control.

## Performance Review System
* I coded and implemented a peer review system for our annual performance review process.  This system was based on uploading Word documents to an ASP.NET website (the Intranet) which would then send the file to a bank of .NET WinForms.  One of those would pick up the document, read the data from it, and supply the in XML back to the engine, which would in turn commit the data to a SQL database.  There was a full aggregation and reporting system I built for this as well.

## Corporate Storage Assessment
* I compared archive, SAN, and backup solutions from EMC, IBM, Quantum, Compellant, and 3PAR in an effort to satisfy our 50% annual data growth rate.  This was an exhaustive examination of all aspects of the technology and how it would relate to our long-term strategic plans for Information Management.  It would have resulted in a $3 million deal over 5 years.

## Employee Records
* I designed a process using KnowledgeLake Capture software and scanners in our Human Resources department to store all employee records to SharePoint for our corporate office.  This also required me to write a couple of custom interfaces for accessing the data in a more natural way.  This solution was so successful it was eventually rolled to several hospitals.

## Competency Checklists
* I designed, coded, and implemented a solution to track employee's competency across all systems managed by IT.  This SharePoint solution used a number of Custom Lists to support Document Libraries of Excel documents.  There were custom Web Service workflows that managed the process, reminder emails to those missing information, and escalation emails to management to let them know what wasn't complete or skills areas that were deficient.

## Time Track Cube
* I designed, coded, and implemented a solution to ingest Excel documents from multiple SharePoint Document Libraries.  These documents contained hours from various IT departments related to project and support work allocated by facility.  The Web Service would read all the data for a month and dump that into a data warehouse.  I then cubed the data and IT Directors could use it in Excel for their monthly, quarterly, and yearly reporting.

## IS Portal
* I built a highly customized portal on SharePoint for our Information Services group.  This included a number of "master" libraries and lists that contained metadata allowing them to classify resources around services, systems, facilities, etc.  Custom WebParts were then deployed that automatically filtered that data to show what was relevant based on the site they were on. 

## P&P Portal
* I was a member of the MedCath P&P Task Force that was assigned the job of collecting all P&P manuals and presenting them in a single location.  I designed, coded, and implemented an AJAX solution that allowed policy owners to upload and categorize documents to our Intranet (ASP.NET).  This solution allowed for policies to be categorized around any number of groups (allowed a policy to be displayed in more than one location), full search capability, versioning, and the storage of "masters" (Word documents) along with "distributable" copies (Acrobat documents).

## Single Sign-On
* I researched SSO products from Citrix, Sentillion, Imprivata, and IBM.  I elected the Imprivata solution and managed the roll-out of that solution across all 10 hospitals.

## Sleuth
* I designed, coded, and implemented a solution that would crawl all files shares on the domain, crack open the documents, index them, and provide search capability.  This solution was used for Enterprise Searching on our Intranet for a few years but was later abandoned as Microsoft's indexing solution improved.

## Denials Management
* I coded and implemented an ASP.NET solution that tracked denied payment requests across the hospitals.  This was a very robust solution with nearly a dozen forms, several dozen reports, a very extensive data import mechanic, and a number of security roles.  This project us to track and ultimately receive payment on million dollars per month.
