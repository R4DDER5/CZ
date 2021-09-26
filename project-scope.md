* [__Brief and Objectives__](#brief-and-objectives)
  * [Project Brief](#project-brief)
  * [Project Overview](#project-overview)
  * [Project Objectives](#project-objectives)
* [__Project Scope and Tasks__](#project-scope-and-tasks)
  * [Project Scope](#project-scope)
    * Server Requirements and Framework
    * [Site Design and Development](#site-design-and-development)
    * [Information Architecture](#information-architecture)
    * [SEO strategy, analytics, and social media integration](#seo-strategy-analytics-and-social-media-integration)
    * [High Level Technical Requirements](#high-level-technical-requirements)
       * [Candidate Forms](#candidate-forms)
       * [Screening Forms](#screening-forms)
       * [Candidate Tests](#candidate-tests)
       * [Mobile Application ALF](#mobile-application-alf)
       * [Printers](#printers)
       * [Live Chat](#live-chat)    
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
This project will involve re-designing and re-developing existing features that are availble via the 'candidate zone' portal. The original version was built 10 years ago and is restricted via the framework for improving mainly security elements. Security should feature as a significant part of any new system. Part of the rebuild should also include improving functionality and streamlining existing services offered, making it also easier to incorporate any new further functionlity required. Third party data integration will be required for some external services so it also importaqnt this is considered and planned for.

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
The design of the site will be provided in whatever appropriate format is required, the design of the site may not be finalised before the project has begun.  Design work will be signed off via senior management before proceeding to be implemented. Visuals will be available during the course of the project build to enable page and display structure. The site will include the feature of allowing client templates incorporation latest technologies and web standards. The site will need to be responsive to accommodate various browser types and devices, this is extremely important to consider due to the different templates that will be avialable. Development will need to continue without final visuals.  
 
#### Server Requirements and Framework
The server will need the option for scaleability. Final decision has yet to made with the following options considered.
Iomart - current Virtual Private Server is hosted by them and may give option for easier data integration
AWS - Offers scaleable options and free for first 12 months providing not going over data limits

The site will be built using the latest version of Laravel based on time project commences. This will then include an easy method to update to any latest releases thereafter. There will be additional work required when new versions are realeased however the structure of the production environment should mean little or no impact on businesss continuity..

The following requirements
Apache2 - 2.4.7?
Mysql - version?
PHP - < 7.2.16

Laravel was chosen due to its ever increasing popularity which offers great resources and continual development. Laravel offers great security.

#### Information Architecture  
The main information contained within the site will be hidden from the general public and will require a user logging in to access the majority of site services. Therefore most visitors to the site will be of 'invite only'.

<p align="center">
<img src="https://user-images.githubusercontent.com/52332471/134803133-91a91287-a2ff-43b4-8978-b5bc08cfc8da.png" align="center" />
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


#### Third Party Integration.  
It is extremely important that early consideration is given to allowing the ability of third party integration of services. Historically this has genrally been via an application programming interface (API). Any relevant API required should have all technical documentation provided by the supplier of services. 

JOB BOARDS  
Developing a system to automatically post to the ever growing number of popular job boards would involve major time and development, therefore it is has been decided to allow other systems to provide this service.

Current Considerations  
Job Adder  
https://developers.jobadder.com/docs/ 

Historical Job Posting Services
- Logic Melon

PYSCHOMETRIC TESTS  
Third party integration has also been required for psychometric tests, previously the API was provided by AQR 
https://aqrinternational.co.uk/

VIDEO INTERVIEWS  
Video storage and management was done via Ziggeo
https://ziggeo.com/


### High Level Technical Requirements    
  * Client Portals
  * Candidate Forms
  * Screening Forms
  * Candidate Tests
  * Contracts
  * Document Uploads
  * Candidate Auditing
 
#### Client Portals
The website will provide a portal recruitment solution for multiple clients. Candidates will access any services the via the relevant client template. 

Ideally a client could provide their own domain to direct candidates to the relevant area of the site portal. This client area of the site would be branded accordingly. Allowing a domain to be used will be highly technical and involve accessability to parts of the overall server managment, therefore whoever hosts the site becomes extremely important in this process. Using unique domains also presents addtional difficulties in the testing process and ideally would be incorporated at later stages of developmen, however considerations will need to be made at the very beginning as the changing of domain names has implications on the root structure of files and folders which is essential for a running website

There will be a wide variety of template designs for various clients so the maintenace should be as flexiable as possible to incorporate bespoke branding. Ideally the administration will incorporate the latest design standards to incorporate features such as Cascading Style Sheets (CSS) and Javascript.

Javascript

  
#### Candidate Forms

The system should have the ability to easily create, manage and assign forms. The creation of forms will include a version of form builder built on features available in existing system. The structure of the form layout should include pages, sections and elements. This will allow drag and drop facility so that questions can be easily reordered and moved  

Form Properties
Name 
Title
Description
Last Page is a thankyou
Mail Notifications
Form Progress
Save and Continue
Override next/previous labels
Label positions
Visability Rules

Pages will allow default introduction text to be displayed and will be determined with next and previous buttons. The final page will include the submit button

Sections will allow for the grouping of elements and any default text to appear within the form
Element Display - Row or break after each element

Elements - 
Types - Textfield, text area, radio group, checkbox group, checkbox, select from list, file upload, hidden input, captcha, calander
Readonly
Validation - error message

The forms will need to include the ability to add standard features such as conditional logic based on a form response.  

The form will need to have the ability to add special features such as Calender Verification  

There will be more feature requests so this will need the flexability to customise 

PDF Report generation of response with the flexability to incorporate client branding and design  

Action scripts  


__Some Examples__


__SUB HEADING__  

<p align="center">
<img src="https://user-images.githubusercontent.com/52332471/106425148-5709e580-645b-11eb-8f09-2159b86d14df.png" />
 </p>
  
#### Screening Forms

Screening forms will follow the standard form creation process. Screening forms with differ from standard forms mainly due to the requirement that screening forms will be processed on behalf of the user usually by an internal staff member input recorded and then final document generated.

Screening forms will need to also have the ability of conditional logic

Pass/fail/hold


Rate the candidate response


Storage file types and delivery options mainly method 1 need to be reviewed in detail. Content Delivery Network, AWS?



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
  * Typing Tests?

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

##### Candidate Auditing

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




