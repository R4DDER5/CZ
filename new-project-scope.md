* [__BRIEF AND OBJECTIVES__](#brief-and-objectives)
  * [Project Brief](#project-brief)
  * [Project Overview](#project-overview)
  * [Project Objectives](#project-objectives)
* [__PROJECT SCOPE AND TASKS__](#project-scope-and-tasks)
  * [Project Scope](#project-scope)
    * [Server Requirements and Framework](#server-requirements-and-framework)
    * [Site Design and Development](#site-design-and-development)
    * [Information Architecture](#information-architecture)
    * [User Management](#user-management)
    * [Access Levels](#access-levels)
    * [Group Management](#group-management)
    * [Third Party Integration](#third-party-integration)
    * [High Level Technical Requirements](#high-level-technical-requirements)
       * [Client Portals](#client-portals)
       * [Candidate Forms](#candidate-forms)
       * [Screening Forms](#screening-forms)
       * [Candidate Tests](#candidate-tests)
       * [Contracts](#contracts)
       * [Document Uploads](#document-uploads)
       * [Candidate Auditing](#candidate-auditing)    
  * [Project Tasks](#project-tasks)
* [__DELIVERABLES AND COMPONENTS__](#deliverables-and-components)
  * [Deliverables](#deliverables)
  * [Components](#components) 
* [__PROJECT ASSUMPTIONS__](#project-assumptions)  
* [__PROJECT TIMESCALES__](#project-timescales)

  

## BRIEF AND OBJECTIVES 
### PROJECT BRIEF
THE REDEVELOPMENT OF THE CURRENT CANDIDATE ZONE TO IMPROVE FUNCTIONALITY, SECURITY, PROCESSES, UPDATES TBC AFTER MEETING WITH ADAM 

### PROJECT OVERVIEW
This project will involve re-designing and re-developing existing features that are available via the 'candidate zone' portal. The original version was built 10 years ago and is now severely restricted via the original framework it was developed upon. The main goal for a re-development of the original s improving mainly security elements. Security should feature as a significant part of any new system. Part of the rebuild should also include improving functionality and streamlining existing services offered, making it also easier to offer further future new functionality should it be requested. Third party data integration will be required for some external services so it also important this is considered and planned for.

The project will seek to place itself in a highly expanding and competitive market sector of recruitment solutions, therefore it is vital to use latest technologies that provide ability to expand in order to remain successful and relevant in the sector. The new site will offer the ability to screen candidates, providing interactive testing capabilities, dynamic form creation and allocation, staff screening of candidates, incorporate contract management and allow data analysis/reporting to monitor effectiveness of campaigns and response rate.

The new site will need the ability to provide its services on behalf of clients. To achieve this will involve the functionality to customise and uniquely brand sections of the portal specific to the client. The new site should allow any client to incorporate their identity and will ideally allow the ability to host unique domains. Where clients do not provide bespoke designs the system will need the ability to allow functionality to offer standard base template(s) that candidates would use.

The new site will need the ability to generate reports based on user submissions, any reports will need to be branded accordingly to related client. The existing format for reports is a PDF, this format is still required but other options should be considered and explored to easily present responses to clients and staff.

The new site will require the implementation of data analytics and tracking so that candidate performance can be monitored. Any reporting or analytics need to be simple to use with a requirement to enable multiple admin users and potentially clients to view depending on access level(s).

The new site will be accepting user generated submissions mainly in the process of uploading documents required for evaluation. The documents will contain highly sensitive information, therefore serious consideration will be needed into types of encryption and security of data storage. Notification of when documents are ready for evaluation is essential.  

The new site will need to be using the latest technology, allowing seamless updates for business continuity. Be able to adapt quick in response to new technologies. Have backup and disaster recovery plan and include its own GIT repository for revisions.

There may be a requirement for human resource functionality but this is yet to be decided.

Phase 2 of the project is likely to incorporate features such as Video Interviews and Gamification, so the system needs the ability to be customised and developed further to accommodate these and additional feature requests.

The scope and tasks required to complete this project will follow the time-lines outlined within in order to deliver the components at the associated times. A list of deliverables and assumptions is included herein.

### PROJECT OBJECTIVES
Project objectives that any re-development of existing candidate zone or new site will aim to achieve:

* __Objective 1__  
  * Decide on a framework that is 'future proof'; well supported, secure, scaleable and offers the opportunity to expand in parallel to business growth. 
  * Ensure cost effective hosting, reliable backup procedures and secure/reliable storage incorporating a content delivery network (CDN).
  * Set-up robust working environment(s), achieving maximum efficiency for constant production flow and continual development. 
  * Integrate version control, enabling maximum risk assurance i.e GIT.

* __Objective 2__
  * Accommodate design for a clean, modern recruitment portal, with the ability to switch between multiple template designs for clients accordingly. 
  * Deliver a seamless provision of services required by any clients. 
  * Deliver services for a wide range of sectors and clients accurately and efficiently.

* __Objective 3__
  * Provide a multifunctional and enjoyable candidate experience. 
  * Achieve maximum candidate retention by incorporating engaging services that are both helpful and intuitive.
  
* __Objective 4__
  * Incorporate and improve existing features whilst integrating any new future functionality that may be required.
  * Build a highly functional recruitment tool which allows easy management by staff and clients to monitor candidate activity and also allow the easy processing of any analytical data.

* __Objective 5__
  * Integrate efficiently with any external services and existing internal services that may be required.

* __Objective 6__
  * Develop for maximum external clients in recruitment sector and all available existing candidate marketplaces that can be serviced, providing unique functionality that can not be provided elsewhere.

* __Objective 7__
  * Ensure an effective disaster recovery plan is in place to ensure maximum business continuity. Consider ongoing security, data protection, GDPR and standards that need to be applied to site(s).

## PROJECT SCOPE AND TASKS
### PROJECT SCOPE

#### Site Design and Development 
The design of the site will be provided in whatever appropriate format is required, the design of the site may not be finalised before the project has begun.  Design work will be signed off via senior management before proceeding to be implemented. Visuals will be available during the course of the project build to enable page and display structure. The site will include the feature of allowing client templates incorporating the latest technologies and web standards. The site will need to be responsive to accommodate various browser types and devices, this is extremely important to consider due to the different templates that will be available. Development will need to continue without final visuals.  
 
#### Server Requirements and Framework
The server will need the option for scaleability. Final decision has yet to made with the following options considered.  
Iomart - current Virtual Private Server is hosted by them and may give option for easier data integration  
AWS - Offers scaleable options and free for first 12 months providing developing within free resource limits. Any CDN will not be included within free resources.

The site will be built using the latest version of Laravel based on time project commences. This will then include an easy method to update to any latest releases thereafter. There will be additional work required when new versions are released however the structure of the production environment should mean little or no impact on business continuity..

The following requirements  
Apache2 - 2.4.7?  
Mysql - version?  
PHP - < 7.2.16

Laravel was chosen due to its ever increasing popularity which offers great resources and continual development. Laravel offers great security. MORE TO BE INCLUDED IN APPENDIX

#### Information Architecture  
The main information contained within the site will be hidden from the general public and will require a user logging in to access the majority of site services. Therefore most visitors to the site will be of 'invite only'.

<p align="center">
<img src="https://user-images.githubusercontent.com/52332471/134803133-91a91287-a2ff-43b4-8978-b5bc08cfc8da.png" />
</p>

__The pages for the default site visible to public will include:__ (no particular order)  
* ABOUT
* FAQS
* CONTACT
* TESTIMONIALS?
* TROUBLESHOOTING  

__The types of services that the site will offer include:__ (no particular order)  
* __CLIENT PORTAL__
  * Branded Template(s)
  * Custom and Unique Content
  * Candidate Management/Reporting?
* __CANDIDATE FORMS__ 
  * Screening Forms
  * Additional Information Forms
  * Declaration Forms
  * Worker/Employee Information Forms
  * Equal Opportunity Forms
  * Application Forms
* __CANDIDATE TESTS__ 
  * Data Checking
  * Numerical Estimation
  * Numerical Interpretation
  * Data Recognition
  * Word Relationships
  * Situational Judgement
  * Psychometric Tests (these tests can only be provided by a third party)
  * Typing and Speed Tests?
* __CONTRACTS__
  * Standard Contracts
  * Bespoke Contracts
  * Pension Agreements
* __CANDIDATE AUDITING AND PROGRESS__
  * Document Uploads
  * Progress and Stage Assessment?

__The user profile for the site will include:__
* Login/Registration
* Manage Profile - this could include stored information to easily pre-populate forms
* Access Historical Contracts
* Manage Holiday Requests?
* History? Perhaps a recording of the live video interview
* Reset Login Information
* Contact Assigned Staff Member?

__The admin for the site will include:__
* Dashboard (Access Levels Determines Display)
* Admin/Staff Management
* User Management
* Group Management
* Client Management
* Test Management
* Form Management
* Contract Management
* Content/Blog Management
* Report/File Management
* Statistic & SEO Management
* Time-sheet Calendar Management?
* Template Management (Client Portals, System Generated Message(s) & Emails, Newsletter/Marketing, Report Templates)
* 3rd Party/API Management (Data Connection Status)

#### User Management
The user management aspect of the site should include the basic requirements of any user functionality. This would include the name of user, email and encrypted password, with easily facility to reset the password where required. The feature to easily enable/disable a user is also a essential requirement. Additionally analytic information should be available recording when the user was registered to the system and when the user last logged into the system.  
Within user management candidate profile information should be able to be viewed and altered where required. The user manager may have additional fields such as notes which should not be visiable to the candidate.  
Any profile information contained in the user profile should have the ability to easily pre-populate any forms/screenings/contracts or tests where the relevant fields are requested.

#### Access Levels
Access levels will comprise of the following levels
- Public - Public users will see the default portal template with minimal features and the real goal to covert public users to potential candidates
- Candidate - Candidates will be assigned specific services related to a client. When the candidate logs into the system the relevant client template should be displayed with the associated services attached to the candidate
- Clients - A client should have access to a management console allowing the management of candidates associated to that specific client. The client should also be able to access data analytics regarding candidates and generate any associated reports.
- Staff - Staff should be able to view all client data and candidates and will have the additional management capability incorporating analytics and reporting.
- Admin - 

#### Group Management
The ability to add a candidate to a group will need to be incorporated into the system. Groups will mainly be related to specific clients. However stand-alone groups must also be considered.  
Groups should have the ability to include description text. This text may be displayed on the front-end.
Groups should have the ability to add services and features. Once a candidate is added to a group, the relevant services and features should automatically assigned to the candidate.

The group managemnt system will have the ability to incorporate the candidate audting sytem - 
The current system - Certain field are assigned via the group.  
the candidate progresses -> Next Group -> Previous group features are added ->> next group including previous features the list goes on and on.
the group allows layering -> i.e. whatever was added previosly is added on top of any functionality from new group.  ^as above


#### Third Party Integration 
It is extremely important that early consideration is given to allowing the ability of third party integration of services. Historically this has generally been via an Application Programming Interface (API). Any relevant API required should have all technical documentation provided by the supplier of services. 

##### Job Boards 
Developing a system to automatically post to the ever growing number of popular job boards would involve major time and constant development, therefore it is has been decided to allow other systems to provide this service.

Current Considerations  
Job Adder  
https://developers.jobadder.com/docs/ 

Historical Job Posting Services  
- Logic Melon

##### Psychometric Tests (possibly phase 2)
Third party integration has also been required for psychometric tests, previously the API was provided by AQR  
https://aqrinternational.co.uk/

##### Video Interviews (most likely Phase 2)
Video storage and management was previously done via Ziggeo  
https://ziggeo.com/


### High Level Technical Requirements    
  * [Client Portals](#client-portals)
  * [Candidate Forms](#candidate-forms)
  * [Screening Forms](#screening-forms)
  * [Candidate Tests](#candidate-tests)
  * [Contracts](#contracts)
  * [Document Uploads](#document-uploads)
  * [Candidate Auditing](#candidate-auditing)  
 
#### Client Portals
The website will provide a portal recruitment solution for multiple clients. Candidates will access any services allocated to them via staff and then displayed in the relevant client template. 

Ideally a client could provide their own domain to direct candidates to the relevant area of the site portal. This client area of the site would be branded accordingly, the branding incorporating client content and final candidate reports.  
__IMPORTANT__ - Allowing multiple domains will involve a highly complex and technical solution, incorporating interaction and customisation to parts of the server management console. Therefore deciding where the site will be hosted becomes an extremely important part of the process to enable this feature (if possible). Using unique domains also presents additional difficulties in the testing process and ideally would be incorporated at later stages of the development schedule. However careful considerations will need to be made at the very beginning of development process, as changing and using different domain(s) has major implications on the root structure of files and folders which is essential to providing smooth running websites and services.

The style and design will vary between clients. The administration and creation of client templates should be built with maximum flexibility to allow for customisation(s) to deliver any bespoke branding as closely as possible. This should include adhering to latest web standards and frameworks to allow maximum versatility with ease of creation. Elements such Cascading Style Sheets (CSS) and allowing bespoke JavaScript should be incorporated as standard.
  
#### Candidate Forms

The system should have the ability to easily create, manage and assign forms. Creating of forms should ideally be managed through some version of form builder. The existing form builder features on current candidate zone are very in depth and suitable, therefore we would look to replicate some of the important features already provided.  

Some current important form properties to be included:  
__Name__ - The unique name allocated to the form for database storage. This could be auto-populated, generally does not include special characters or spaces  
__Title__ - The user friendly name of the form that can include special characters and spaces  
__Description__ - The long detailed description of the form and its purpose to enable easy identification  
__Last page is a thank you__ - If selected after submission the candidate is re-directed to a page which explains this is the end of the form process. Can be toggled on/off.  
__Mail notifications__ - Forms should automatically notify the staff member who allocated it to the candidate. This would allow some extra notifications when complete  
__Form progress__ - An indicator to demonstrate to end user how much progress they have made in completing the form. Can be toggled on/off.  
__Save and continue__ - Allowing the user to save any current progress of the form and return at a later stage. Can be toggled on/off.  
__Override next/previous labels__ - Allow the labels on navigation buttons to be changed i.e. back/forward, step 12345  
__Label positions__ - Position the form element field label. Left, Right, Above, Below.  
__Visibility rules__ - Mainly allows visibility of the fields to be shown based on the conditional logic of another element. i.e. Do you need to provide further information YES/NO. If yes display text area to allow more text to be submitted.  

Following existing form builder model, the creation process should be compromised of form layouts that include pages, sections and elements. The facility to easily adjust and position pages, sections and elements via 'drag and drop' method is essential to be included in any new version.

__Pages__ - Pages allow any default introduction text description to be displayed if required. Pages will also determine where the appropriate next and previous buttons will be displayed. The final page will include button to submit information (unless the 'Last page is a thank you' option is selected whereby the submit button will be the previous page to the final page)  
__Sections__ - Sections will also allow any default introduction text description to be displayed if required. Any section should also allow the display of any elements that are grouped within it, this will either be all elements in a row or a break after each element. Sections should also be included in any visibility rules. i.e. If the option Yes is selected display section and all containing elements.  
__Elements__ - Elements should include element types that are already pre-defined.  
Some examples of element types - Text-field, text area, radio group, checkbox group, checkbox, select from list, file upload, hidden input, captcha, calendar
read-only.  
Elements should have the ability to designate if that field is required, allowing input of the error message if the input is missing or incorrect.
Ideally elements (and forms) would need the ability to apply some conditional logic and allow some custom logic if required in certain special circumstance.
i.e. Standard logic - only allow number characters and no alphabet or special characters  
Custom Logic - validate the response on multiple date fields to ensure the date period is at least 10 years.  
This was achieved in earlier form software by the ability of action scripts.  

The ability to easily copy elements or copy sections including any elements contained in the section is a feature that will be required to avoid unnecessary repetitive tasks.

After any form is submitted the results should be contain in a report document, ideally a PDF that is branded accordingly. The ability to easily customise different form outputs is essential.   

The candidate should be able to upload files if required in the form, this will be stored appropriately and handled with maximum security protocol.

<p align="center">
<img src="https://user-images.githubusercontent.com/52332471/134808207-e1e0a243-6dee-462f-b028-8dd8c07b463c.png" />
 </p>
  
#### Screening Forms

Screening forms will follow the same process of design and creation as standard forms following the page, section and element process. Screening forms with differ from standard forms mainly due to the requirement that screening forms will be processed on behalf of the user usually by an internal staff member as part of a telephone interview. The form submissions will be stored and then output in the relevant branded PDF template.

Screening forms may have some extra features to be included such as:  
__Screening Status__ - Pass/Fail/On Hold  
__Screening Rating__ - Rate the total overall responses from the candidate (entire form elements) or rate individual elements. The scoring should include the flexibility to change as required per form/element. i.e. select out of 100, select out of 20.  

#### Candidate Tests  
Candidate tests will incorporate the functionality to be built in the same method as the form builder with pages, sections and elements. The difference will be that the response submitted will be verified to determine whether the input is correct.  
Examples of some previous types of tests:
  * Data Checking - basic number and data checking
  * Numerical Estimation - the ability to estimate the correct data
  * Numerical Interpretation - interpretation of different data sets and the corresponding results
  * Data Recognition - the ability to recognise and identify important data from tables and charts
  * Word Relationships - how verbal English words are related, including opposites and similar s
  * Situational Judgement - the measured judgement response from a variety of different situations
  * Psychometric Tests - test responses evaluated in psychometric categories such as personality (these tests can only be provided by a third party)
  * Typing and Speed Tests - calculate the input speed and accuracy based on inputting a provided selection of text.

The tests should have some form of introductions before test begins to explain and on occasions where required provide examples, this should be handled via the page functionality in the form builder. There has been the requirement to only display introduction page/text once and then remove from view if the candidate attempts to return to the previous page.

The general format is that test are done under a time constraint. It is therefore important to eliminate the ability for any candidate to alter, override or pause any time constraints applied to the test.

Some current important test properties to be included:  
__Test Time__ - how much time is available to complete the test.  
__Maximum number of questions__ - the maximum number of questions to be displayed should there be a central pool of questions.  
__Questions display__ - questions are displayed in order created or randomly displayed.  
__Pass percentage__ - the required correct answer percentage to certify as a pass.  
__Number of attempts__ - How many attempts the candidate is allowed on specific test. Default is 1.  
__Answer Score__ - By default 1 correct answer would score 1 point. The ability to override all the answer scores for all questions. 

##### Questions
Questions will need to be able to be formatted ideally with a WYSIWYG editor. This will allow easy formatting of questions. Questions should be able to include images, tables and video questions.

Historical requests have been a selection of images and the correct image needs to be selected or watch the video and answer the provided questions related to the video.

##### Answers
Answers are currently distinguished by type   
Current answer types - text, date, checkbox, radio, select from list, text-area.  
The answers submitted will need to be verified as to being correct, therefore the correct answer will need to be included. There has previously be the requirement to include multiple correct answers. i.e answer options 12345, answers 3 and 5 are correct.

__Answer Score__ - By default 1 correct answer would score 1 point. The ability to override specific questions to alter associated answer score.  
__Multiple correct answers__ - Whether the answer has multiple correct answers to choose from.  
__Answer is case sensitive__ - when selected the answer is only correct if the correct case and formatting is used  
__Answers sequenced__ - the answer results must be submitted in correct sequence i.e options 12345 must be submitted 54321  
__Minimum/maximum characters allowed__ - generally when answers have free text option and to limit the number of characters inputted  
__Manually scored__ - again generally on free text answers and the answer is not correct or has appropriate score unless staff or admin has manually reviewed  


#### Contracts

Contracts will need to be created via a template builder to enable formatting and ensure correct legal information is contained correctly.  
Contracts will also need form elements to allow staff or admins to manipulate contracts with individual contractual requirements. Once the contractual elements are prepared for the individual the admin or staff will have the ability to review the document.
The document is then locked and distributed to the potential employee. if any changes need to be made before the contract is agreed by potential employee then the document can be unlocked and altered accordingly.
The employee is notified and has the option to review the presented contractual agreement. If the potential employee is satisfied then there will be various form elements to select such as checkboxes for agreement of terms, input name and input date signed.
The document should automatically be recording when the contract is opened and the date the contract agreement was submitted regardless of what information is provided by the potential employee.

Once the contract has been digitally signed and submitted it becomes locked and can no longer be unlocked by a staff or admin member. The staff member is notified once the potential employee has submitted agreement to the contract.  

A final PDF contract in then available for download by the staff member or the new employee.

Contracts will continually change therefore an adaptable system needs to be incorporated that allows contract revisions to be made but does not alter the original document and any historical documents that have been agreed by previous employees

#### Document Uploads 

The system should be able to allow document uploads associated to a specific candidate. A candidate should be able to upload documents and also staff members should be able to upload documents on their behalf.

- Document previews without downloading directly. 
- Secure file transfer options
- Security & GDPR
- Document upload notifications

Extra consideration should be given to the secure encryption and storage of documents. Also file limit sizes and document types.

#### Candidate Auditing

Candidates will need to be audited at each stage of their progress.  
Currently this is done via group management, questions are asked, relevant details are completed - this could be better
The whole idea of candidate auditing depends on stages - this has been handled via groups, layering? The previous level of answers and responses should layer on top of any new questions presented at any new stage. At all stages notifications should be sent to releant people included in notifications.
Candidate auditing = stages of progress in the candidate cycle  
Ideally in any new system we would use forms combined with groups to achieve existing functionality.  
The questions are the same as screening - they will all need some type of form element - text, checkbox, select from list
The diifference is entirely due to progress, 


### PROJECT TASKS
bo
__1. Determine System Framework__  
Decide which architecture will used and give future proof etc etc. The options that have been considered are Private VPS or AWS. There is now further consideration on using a complete framework options are, codeignitor, NodeJS and Laravel.  
__2. Setup Working Environments__  
I would initially propose to have 3 working environments. This would involve a Development Environment (DEV), a Staging Environment (STAGE) and a Live Environment (LIVE). All this environments should have a repository for version control in place. All initial development would take place in the DEV environment, when ready the work would move to the STAGE environment for more rigorous and thorough testing. Once the testing is complete and we have had the sign off that testing is complete and satisfactory, it would then move to the LIVE environment. If any problems are encountered at any point, work would move back to the DEV environment and then once again moved to STAGE for testing. Nothing would move to LIVE until everyone is completely happy for this to proceed.  
__3. Core Functionality - Forms__  
Forms and the appropriate form builder provide the basis for forms, screening forms, tests and contracts so extra development time needs to be allocated to ensure this process is correct and this therefore needs to take priority in development.  
__4. Core Functionality - Tests, Screening, Contracts__  
Once the form builder and forms functionality is completed it will allow us to proceed on building the screening forms, tests and contracts.  
__5. Develop External Integration__   
External integration of job boards and psychometric testing  
__6. Document Upload and Storage__  
Incorporate CDN secure encryption and secure access of any uploaded documents.  
__7. Browser and Compatibility Testing__  
The site will be tested to make sure it works with a wide selection of browsers and to ensure it does not break when viewed on mobile devices or tablets.  
__8. Data Collection__  
All data collection analysis needs to be tested such as notifications of when emails sent, candidates have logged onto sites, tests, forms and contracts are completed.  

## DELIVERABLES AND COMPONENTS

### Deliverables
1. Build Core Functionality  
We will need to prioritise building the form features initially as so many other components depend on them. Other features need the ability to be switched on and off when required as the project progresses.
2. Portal site design  
Replicate existing client site templates.
3. Reporting on all aspects of system functionality
4. Ensure third party data connections can be monitored and are working correctly  .
5. Draft version of site, once all relevant content for the site we have been provided and applicable feature built this will be loaded in and testing can begin. Digital sign off will be required before deploying to the Live Site.
6. Final version of site with relevant training that will be conducted on features and administration of the site. 
7. Plan any additional phase 2 requirements.

### Components

Component 1 | User Account and Profile(s)  
Accounts primarily will be created but registration to the site should also be available, further access to other features like user, group and allocated services will be determined by user access levels.

Component 2 | Site Backup & Security  
A hard backup copy of the files associated with the site will be delivered on completion to the client on a memory stick, as well as backed up to appropriate secure location(s). Where appropriate the most secure encryption methods will be used with data transfer.

Component 3 | Training Documents  
A reference document outlining how to make updates to the site along with a link to online resources will be built as project develops. 


## PROJECT ASSUMPTIONS
Key information we are working with

This agreement is based on the following assumptions:  

- Neil Radcliffe - Project Management/Development
- Adam Bevan - MBA Lead Contact
- Tasol will be providing the development team.
- jobadder will be providing the access to job posting boards.
- No new client templates will be requested until existing templates have been replicated. 
- Appropriate secure file storage to be decided
- Appropriate linux hosting to be decided
    
Sign off may be required before for any of the above 3rd party involvement.


## PROJECT TIMESCALES

### KEY MILESTONES

| TASK                      | ASSIGNED TO    | DUE DATE  |
| ------------------------- |:--------------:| -----:    |
| Finish Technical Scope    | N Radcliffe    | ASAP      |
| Sign Statement Of Work    | TBC            | TBC       |
| Finalise Design           |                |           |
| Build Users & Groups      |                |           |
| Build Form Builder        |                |           |
| Build Screening Forms     |                |           |
| Build Tests               |                |           |
| Build Contracts           |                |           |
| Build Document Upload     |                |           |
| Candidate Auditing        |                |           |
| 3rd Party Integration     |                |           |
| Finalise Testing          |                |           |
| Deploy to Staging Site    |                |           |
| Deploy to Client Domain   |                |           |
| Final Sign Off            |                |           |
| Code Stored Centrally     |                |           |
| Ongoing Support Agreement |                |           |




