* [__Brief and Objectives__](#brief-and-objectives)
  * [Project Brief](#project-brief)
  * [Project Overview](#project-overview)
  * [Project Objectives](#project-objectives)
* [__Project Scope and Tasks__](#project-scope-and-tasks)
  * [Project Scope](#project-scope)
    * [Server Requirements and Framework](#server-requirements-and-framework)
    * [Site Design and Development](#site-design-and-development)
    * [Information Architecture](#information-architecture)
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
* [__Deliverables and Components__](#deliverables-and-components)
  * [Deliverables](#deliverables)
  * [Components](#components) 
* [__Project Assumptions__](#project-assumptions)  
* [__Project Timescales__](#project-timescales)

  

# Brief and Objectives 
## Project Brief
THE REDEVELOPMENT OF THE CURRENT CANDIDATE ZONE TO IMPROVE FUNCTIONALITY, SECURITY, PROCESSES, UPDATES AND TO ENSURE 

### PROJECT OVERVIEW
This project will involve re-designing and re-developing existing features that are availble via the 'candidate zone' portal. The original version was built 10 years ago and is restricted via the framework for improving mainly security elements. Security should feature as a significant part of any new system. Part of the rebuild should also include improving functionality and streamlining existing services offered, making it also easier to offer further future new functionlity should it be requested. Third party data integration will be required for some external services so it also importaqnt this is considered and planned for.

The project will seek to place itself in a highly expanding and competitive market sector of recruitment solutions, therefore it is vital to use latest technologies that provide ability to expand in order to remain successful and relevant in the sector. The new site will offer the ability to screen candidates, providing interactive testing capabilities, dynamic form creation and allocation, staff screening of candidates, incorporate contract management and allow data analysis/reporting to monitor effectiveness of campaigns and response rate.

The new site will need the ability to provide its services on behalf of clients. To achieve this will involve the functionality to customise and uniquly brand sections of the portal specific to the client. Thie new site should allow any client to incorporate their identity and will ideally allow the ability to host unique domains. Where clients do not provide bespoke designs the system will need the ability to allow functionality to offer standard base template(s) that candidates would use.

The new site will need the ability to generate reports based on user submissions, any reports will need to be branded accordingly to related client. The existing format for reports is a PDF, this format is still required but other options should be considered and explored to easily present responses to clients and staff.

The new site will require the implementation of data analytic's and tracking so that candidate performance can be monitored. 

//Marketplaces, analytics, and social media must be centralised to allow automatic functionality and also be simple to use with a requirement to enable multiple users to contribute depending on access level.\\

//The site needs the ability to publish automatically to social media channels and established online market places.\\

The new site will be accepting user generated submissions mainly in the process of uploading documents required for evaluation. The documents will contain highly sensitive information, therefore serious consideration will be needed into types of encryption and security of data storage. Notification of when documents are ready for evaluation is essential.  

The candidate zone will need to be using the latest technology, allowing seamless updates for business continuity. Be able to adapt quick in response to new technolgies. Have backup and disaster recovery plan and include its own GIT repository for revisions blah blah blah

There may be a requirement for human resource functionality but this is yet to be decided.

There may be requirements for further features such as Video Interviews and Gamification, so the system needs the ability to be customised and developed further.

The scope and tasks required to complete this project will follow the time-lines outlined within in order to deliver the components at the associated times. A list of deliverables and assumptions is included herein.

### PROJECT OBJECTIVES
Proposal that re-development of existing candidate zone aims to achieve with the following objectives:

* __Objective 1__  
  * Decide framework that is well supported, allowing scalability and easily integrate external services. 
  * Plan hosting, backups and secure file storage/content delivery network (CDN).
  * Set-up robust working environment(s), allowing maximum effectiveness for production flow and further development. 
  * Put in place site specific version control for risk assurance i.e GIT 

* __Objective 2__
  * Accommodate design for a clean, modern recruitment portal, with the ability to switch between mutliple designs. 
  * Deliver a seamless and engaging candidate experience on behalf of a client. 
  * Deliver services for a wide range of sectors and clients accurately and efficiently.
  
* __Objective 3__
  * Incorporate and improve existing features whilst integrating any new functionality required.
  * Build a highly functional recruitment tool which allows easy management by staff and retains candidate activity and allows easy processing of analytical data.

* __Objective 4__
  * Integrate efficiently with any external services and existing internal services that may be required.

* __Objective 5__
  * Develop for maximum external sales ensuring existing marketplaces can be utilised.
  
* __Objective 6__
  * Ensure data analytics are in place to to help monitor client performance and candidate response. REPEAT

* __Objective 7__
  * Ensure an effective disaster recovery plan is in place to ensure maximum business continuity. Consider ongoing security, data protection, GDPR and standards that need to be applied to site(s).

## Project Scope and Tasks
### PROJECT SCOPE

#### Site Design and Development 
The design of the site will be provided in whatever appropriate format is required, the design of the site may not be finalised before the project has begun.  Design work will be signed off via senior management before proceeding to be implemented. Visuals will be available during the course of the project build to enable page and display structure. The site will include the feature of allowing client templates incorporating the latest technologies and web standards. The site will need to be responsive to accommodate various browser types and devices, this is extremely important to consider due to the different templates that will be avialable. Development will need to continue without final visuals.  
 
#### Server Requirements and Framework
The server will need the option for scaleability. Final decision has yet to made with the following options considered.
Iomart - current Virtual Private Server is hosted by them and may give option for easier data integration
AWS - Offers scaleable options and free for first 12 months providing developing within free resource limits. Any CDN will not be included within free resources.

The site will be built using the latest version of Laravel based on time project commences. This will then include an easy method to update to any latest releases thereafter. There will be additional work required when new versions are realeased however the structure of the production environment should mean little or no impact on businesss continuity..

The following requirements
Apache2 - 2.4.7?
Mysql - version?
PHP - < 7.2.16

Laravel was chosen due to its ever increasing popularity which offers great resources and continual development. Laravel offers great security.

#### Information Architecture  
The main information contained within the site will be hidden from the general public and will require a user logging in to access the majority of site services. Therefore most visitors to the site will be of 'invite only'.

<p align="center">
<img src="https://user-images.githubusercontent.com/52332471/134803133-91a91287-a2ff-43b4-8978-b5bc08cfc8da.png" />
</p>

__The pages for the default site visable to public will include:__ (no particular order)  
* ABOUT
* FAQS
* CONTACT
* TESTIMONIALS?
* TROUBLESHOOTING  

__The types of services that the site will offer include:__ (no particular order)  
* __CLIENT PORTAL__
  * Branded Template(s)
  * Custom and Unique Content
  * Candidate Managemnt/Reporting?
* __CANDIDATE FORMS__ 
  * Screening Forms
  * Additinal Information Forms
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

__The admin for the e-commerce site will include:__
* Dashboard (Access Levels Determines Display)
* Admin/Staff Managment
* User Management
* Group Management
* Client Management
* Test Management
* Form Management
* Contract Management
* Content/Blog Management
* Report/File Management
* Statistic & SEO Management
* Timesheet Calendar Management?
* Template Management (Client Portals, System Generated Message(s) & Emails, Newsletter/Marketing, Report Templates)
* 3rd Party/API Management (Data Connection Status)


#### Third Party Integration 
It is extremely important that early consideration is given to allowing the ability of third party integration of services. Historically this has genrally been via an Application Programming Interface (API). Any relevant API required should have all technical documentation provided by the supplier of services. 

JOB BOARDS  
Developing a system to automatically post to the ever growing number of popular job boards would involve major time and constant development, therefore it is has been decided to allow other systems to provide this service.

Current Considerations  
Job Adder  
https://developers.jobadder.com/docs/ 

Historical Job Posting Services
- Logic Melon

PYSCHOMETRIC TESTS  
Third party integration has also been required for psychometric tests, previously the API was provided by AQR 
https://aqrinternational.co.uk/

VIDEO INTERVIEWS  
Video storage and management was previously done via Ziggeo
https://ziggeo.com/


### High Level Technical Requirements    
  * [Client Portals](#client-portals)
  * Candidate Forms
  * Screening Forms
  * Candidate Tests
  * Contracts
  * Document Uploads
  * Candidate Auditing
 
#### Client Portals
The website will provide a portal recruitment solution for multiple clients. Candidates will access any services allocated to them via staff and then displayed in the relevant client template. 

Ideally a client could provide their own domain to direct candidates to the relevant area of the site portal. This client area of the site would be branded accordingly, the branding incorporating client content and final candidate reports.  
__IMPORTANT__ - Allowing multiple domains will involve a highly complex and technical solution, incorporating interaction and customisation to parts of the server managment console. Therefore deciding where the site will be hosted becomes an extremely important part of the process to enable this feature (if possible). Using unique domains also presents addtional difficulties in the testing process and ideally would be incorporated at later stages of the development schedule. However careful considerations will need to be made at the very beginning of development process, as changing and using different domain(s) has major implications on the root structure of files and folders which is essential to providing smooth running websites and services.

The style and design will vary between clients. The administration and creation of client templates should be built with maximum flexability to allow for customisation(s) to deliver any bespoke branding as closely as possible. This should include adhereing to latest web standards and frameworks to allow maximum versitility with ease of creation. Elements such Cascading Style Sheets (CSS) and allowing bespoke Javascript should be incorporated as standard.
  
#### Candidate Forms

The system should have the ability to easily create, manage and assign forms. Creating of forms should ideally be managed through some version of form builder. The existing form builder features on currrent candidate zone are very in depth and suitable, therefore we would look to replicate some of the important features already provided.  

Some current important form properties to be included:  
__Name__ - The unique name allocated to the form for database storage. This could be auto-populated, generally does not include special characters or spaces  
__Title__ - The user friendly name of the form that can include special charcters and spaces  
__Description__ - The long detailed description of the form and its purpose to enable easy identification  
__Last page is a thankyou__ - If selected after submisssion the candidate is re-directed to a page which explains this is the end of the form process. Can be toggled on/off.  
__Mail notifications__ - Forms should automatically notify the staff member who allocated it to the candidate. This would allow some extra notifications when complete  
__Form progress__ - An indicator to demonstrate to end user how much progress they have made in completing the form. Can be toggled on/off.  
__Save and continue__ - Allowing the user to save any current progress of the form and return at a later stage. Can be toggled on/off.  
__Override next/previous labels__ - Allow the labels on navigation buttons to be changed i.e. back/forward, step 12345  
__Label positions__ - Position the form element field label. Left, Right, Above, Below.  
__Visability rules__ - Mainly allows visability of the fields to be shown based on the conditional logic of another element. i.e. Do you need to provide further information YES/NO. If yes display textarea to allow more text to be submitted.  

Following existing form builder model, the creation process should be compromised of form layouts that include pages, sections and elements. The facility to easily adjust and position pages, sections and elements via 'drag and drop' method is essential to be included in any new version.

__Pages__ - Pages allow any default introduction text desription to be displayed if required. Pages will also determine where the appropriate next and previous buttons will be displayed. The final page will include button to submit information (unless the 'Last page is a thankyou' option is selected whereby the submit button will be the previous page to the final page)  
__Sections__ - Sections will also allow any default introduction text desription to be displayed if required. Sections also provide. A section also allow the display of any elements that are grouped within it, this will either be all elements in a row or a break after each element. Sections should also be included in any visability rules. i.e. If the option Yes is selected display section and all containing elements.  
__Elements__ - Elements should include element types that are already pre-defined.  
Some examples of element types - Textfield, text area, radio group, checkbox group, checkbox, select from list, file upload, hidden input, captcha, calander
readonly.  
Elements should have the ability to designate if that field is required, allowing input of the error message if the input is missing or incorrect.
Ideally elements (and forms) would need the ability to apply some conditional logic and allow some custom logic if required in certain special circumstance.
i.e. Standard logic - only allow number characters and no alphabet or special characters  
Custom Logic - validate the response on multiple date fields to ensure the date period is at least 10 years.  
This was achieved in earlier form software by the ability of action scripts.  

After any form is submitted the results should be contain in a report document, ideally a PDF that is branded accordingly. The ability to easily customise different form outputs is essential.   

The candidate should be able to upload files if required in the form, this will be stored appropriately and handled with maximum security protocol.

<p align="center">
<img src="https://user-images.githubusercontent.com/52332471/106425148-5709e580-645b-11eb-8f09-2159b86d14df.png" />
 </p>
  
#### Screening Forms

Screening forms will follow the same process of design and creation as standard forms following the page, section and element process. Screening forms with differ from standard forms mainly due to the requirement that screening forms will be processed on behalf of the user usually by an internal staff member as part of a telephone interview. The form submissions will be stored and then output in the relvant branded PDF template.

Screening forms may have some extra features to be included such as:
__Candidate Status__ - Pass/Fail/On Hold  
__Candidate Rating__ - Rate the total overall responses from the candidate (entire form elements) or rate individual elements. The scoring should include the flexability to change as required per form/element. i.e. select out of 100, select out of 20.  

<p align="center">
<img src="https://user-images.githubusercontent.com/52332471/106593958-59e30400-6549-11eb-83a0-4d31203a50c0.png" />
 </p>

#### Candidate Tests  
Candidate tests creation will be based in intial design functionalitly of forms with pages, sections and elements.

Test introductions before test begins to explain and on occasion provide examples. Do we need the ability to only display the text once?

Test time and perhaps time per question - extra consideration should be made so that time can not be altered by the end user
maximum number of questions
Questions in order or random
pass percentage
How many attempts before the test in not accessable anymore
change score per question - 
multiple correct answers
  
  * Data Checking
  * Numerical Estimation
  * Numerical Interpretation
  * Data Recognition
  * Word Relationships
  * Situational Judgement
  * Psychometric Tests (these tests can only be provided by a third party)
  * Typing and Speed Tests?

__Questions__
Questions will need to be able to be formatted ideally with a WYSIWG editor.

Questions will take the form of text images and video.

__Answers__
The answers submitted will need to be verified as to being correct

Current answer types - text, date 

answer not case sensitive
answers must be provided in a sequence
minimum/maximum characters allowed
answers must be in a specific sequence
the answer gets manually reviewed
overide individual question scores



#### Contracts

The contracts will involve the ability to create contracts

Contracts will need a contract template builder. This will include dynamic fields to prepopulate the contract

The potential employee will have the ability to review contract information 

There will be form elements such as agreement and enter name

Once the contract is signed and submitted it becomes locked. A final PDF contract in created.



#### Document Uploads 

Ideally the report printing will be handled externally with automated process managed internally or connected externally. Some considerations required by print operators

- Report resolution (3rd Party may be providing)
- Setting report in print template
- Additional print pages added to report (printers require total page count to be divided by 4 so blank pages need inserting accordingly)  
- Secure file transfer options
- Security & GDPR
- Print scheduling, accurate lead times to customer
- Estimated print numbers
- Timescales for go live - usually to incorporate practice print run and testing.

Short-term may require printing to be handled internally so any print management console needs to be robust to accommodate internal printing and different external print providers.

#### Candidate Auditing

The system will have a live chat feature which will notify the end user when staff are online and offline. The live chat will have the ability for end user and staff to communicate directly. Chat logs will be recorded for any further investigation or requests.  


### PROJECT TASKS

__1. Determine System Framework__  
Decide which architecture will used and give future proof etc etc. The options that have been considered are self hosted e-commerce - magento, external hosted shopify. There is now further consideration on using a complete framework options are, codeignitor, NodeJS and Laravel.  
__2. Setup Working Environments__  
I would initially propose to have 3 working environments. This would involve a Development Environment (DEV), a Staging Environment (STAGE) and a Live Environment (LIVE). All this environments should have a repository for version control in place. All initial development would take place in the DEV environment, when ready the work would move to the STAGE environment for more rigorous and thorough testing. Once the testing is complete and we have had the sign off that testing is complete and satisfactory, it would then move to the LIVE environment. If any problems are encountered at any point, work would move back to the DEV environment and then once again moved to STAGE for testing. Nothing would move to LIVE until everyone is completely happy for this to proceed.  
__3. Core Functionality and Internal Integration__  
Design and develop the key aspects that will be used for the core functionality of the site. Install e-commerce framework. Link LIFO reports with appropriate branding.  
__4. Site Design and Content Entry__  
Once the site design is completed and signed off, content provided to us will be entered onto the site pages. This will include text and pictures for each page to be created with the initial setup, along with meta data.  
__5. Develop External Integration__   
External reports, distribution and shipping and Printing  
__6. Checkout Payment Integration__  
Multiple payment options will be setup including Paypal, GoCardless and others to be confirmed. The entire shop experience shall be fully tested from general browsing through to product selection, checkout purchase and delivery notification.  
__7. Browser and Compatibility Testing__  
The site will be tested to make sure it works with a wide selection of browsers and to ensure it does not break when viewed on mobile devices or tablets.  
__8. Data Collection__  
A data collection pop-up invitation to the general mailing list as well as auto cart abandonment detection, general marketing and surveys. contact email and forms will be set up and tested.  

## Deliverables and Components

### Deliverables
1. Build Core Functionality  
We will need to prioritise building the e-commerce and LIFO reporting as urgent. Other features need the ability to be switched on and off when required as the project progresses.
2. E-commerce site Design  
Following the design being sent by the designer, one round of editing will be allowed before digital sign off is required to move forward to building the site.
3. Report/Email/Marketing branding needs to be appropriate to ALIVE and its products/services
4. Ensure shipping and printing is working correctly  .
5. Draft version of site, once all relevant content for the site we have been provided and applicable feature built this will be loaded in and testing can begin. Digital sign off will be required before deploying to the Live Site.
6. Final version of site
Relevant training will be conducted on features of site. 
7. Report building process reviewed, appointment booking and live feeds developed. Further integration with internal and external systems.

### Components

Component 1 | E-commerce User Account and Profile(s)  
Accounts can be created by registration or created manually, further access to other features like user, group and product management will be determined by user access levels.

Component 2 | Site Backup & Security  
A hard backup copy of the files associated with the site will be delivered on completion to the client on a memory stick, as well as backed up to appropriate secure location(s). Where appropriate the most secure encryption methods will be used.

Component 3 | Training Documents  
A reference document outlining how to make updates to the site along with a link to online resources will be built as project develops. 


## Project Assumptions
Key information we are working with

This agreement is based on the following assumptions:  

- Design with Home will be providing creative layout and designs.
- Shanti Infotech will be providing the development team.
- myWarehouse will be providing the distribution and shipping.
- CDL will be providing the printing and shipping. 
- vitagen-x.com will be providing the external DNA reports
- Appropriate secure file storage to be decided
- Appropriate linux hosting to be decided
    
Sign off may be required before for any of the above 3rd party involvement.


## Project Timescales

### KEY MILESTONES

| TASK                      | ASSIGNED TO    | DUE DATE  |
| ------------------------- |:--------------:| -----:    |
| Finish Technical Scope    | N Radcliffe    | ASAP      |
| Sign Statement Of Work    | TBC            | TBC       |
| Finalise Design           |                |           |
| Content Provided          |                |           |
| Build Core                |                |           |
| Internal Features         |                |           |
| External Features         |                |           |
| Finalise Testing          |                |           |
| Deploy to Staging Site    |                |           |
| Deploy to Client Domain   |                |           |
| Final Sign Off            |                |           |
| Code Stored Centrally     |                |           |
| Ongoing Support Agreement |                |           |




