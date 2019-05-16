  <h3 align="center"> Universidad Autónoma de Ciudad Juárez</h3>
  <h3 align="center"> División Multidisciplinaria de Ciudad Universitaria </h3>
  <h3 align="center"> Departamento de Ingeniería de Electricidad y Computación </h3>
  <p align="center"><img src="https://github.com/RequirementEngineering/ch-re-159949IvanValdez/blob/master/Mind%20Map/Logo.png" height="260" width="260"></img></p>
  <h3 align="center">Web Page "Valdez Fotografias"</h3>
  <h3 align="center">Luis Ivan Valdez Anchondo  159949</h3>
  <h3 align="center">Development of Software Requirements</h3>
  <h3 align="center">May 2019</h3>

## Table of Contents and Index
* [1. Introduction](#Introduction)
  * [1.1 Purpose](#Purpose)
  * [1.2 Scope](#Scope)
  * [1.3 Definitions, acronymus, and abbreviations](#Definitions,-acronymus,-and-abbreviations)
  * [1.4 References](#References)
  * [1.5 Overview](#Overview)
* [2. Overall Description](#Overall-Description)
  * [2.1 Product Perspective](#Product-Perspective)
  * [2.2 Product Functions](#Product-Functions)
  * [2.3 User Characteristics](#User-Characteristics)
  * [2.4 Contraints](#Constraints)
  * [2.5 Assumptions and dependencies](#Assumptions-and-dependencies)
* [3. Specific requirements](#Specific-requirements)
  * [3.1 User requirements](#User-requirements)
  * [3.2 System requirements](#System-requirements)
  * [3.3 Functional Requirements](#Functional-Requirements)
  * [3.4 Non functional requirements](#Non-functional-requirements)
* [4. Supporting Information](#Supporting-Information)
  * [4.1 Appendixes](#Appendixes)
    * [4.1.1 Elicitation process](#Elicitation-process)
    * [4.1.2 BPMN](#BPMN)

# SRS
## Introduction

### Purpose
This SRS aims to define and clarify all the requirements for the realization of a web page on a photographic session business, in which you can make reservations for dates for events, consult packages, prices, as well as review photographs of previous sessions.

The requirements that will be seen here, will be provided by the client and defined so that both the client and the developer of the website can understand and apply them in the best possible way.

### Scope
The website to develop "Valdez fotografias" will be a place where people can enter to perform any of the following actions:
* Verify availability of dates and reservations.
* Check packages and prices.
* See previous works.

The purpose of the website is to provide the client with a way to manage their business in a more optimal way, since now everything is done through Facebook, promoted by Facebook, upload their previous work through Facebook, if a user wants Information about a packet is made through Facebook messages, etc. that is why having the website a large part of the information that users need will be available in a more simple way, avoiding having to send a message to the facebook page and wait for an answer, this helps customers to get the information in an easier and faster way, while reducing the burden for the owner to have to answer messages individually for each client.

### Definitions, acronyms, and abbreviations
* **etc:** Abbreviation of etcetera, an expression used to replace the rest of an enumeration that is understood thanks to the context.
* **reservations:** Save or set aside something in the future, in this case set a date in the near future.
* **Slider:** It is an element of a web page that shows multiple images and text that alternate between them.
* **Domain:** A domain is the unique and exclusive name with which a web page will be identified on the Internet.
* **Hyperlink:** It is a link that connects one document with another, that allows a new page on the Internet with just a click on it.
* **TBD:** To Be Determined.

### References
* https://sensacionweb.com/que-es-slider/
* https://es.ryte.com/wiki/Hyperlink


### Overview
The rest of the document contains the functions of the web page in more detail, section 2 looks in depth at the product perspective, the function of the product and the characteristics of the user, the constraints, as well as the assumptions and dependencies, in Section 3 is where the specific requirements of the website are discussed.

## Overall description

### Product perspective
The system to develop consists of a web page that will be of help to the business owner, helping him to provide the basic information of the business to the users, also the users will be benefited thanks to the web page because the information will be at its reach each time you want, plus you can see availability of dates and make your reservations from the internet.

The web page will consist of a main page, a section of contact information, an "About us" section, a calendar section with the available dates, a section with the previous works and a section with the packages and their respective prices .

* **Main page:** It will be the first screen that the user will see when he enters, this screen must contain the following:
  * A banner with the logo of the business and the name of the page.
  * A tab to go to the contact information section.
  * A tab to go to the "About us" section.
  * A tab to go to the calendar section.
  * A tab to go to the section of previous works.
  * A tab to go to the package section.
  * A slider with the most outstanding previous works.
  
* **Contact tab:** In this tab you will find the necessary information so that users can contact the business owner, it must include the following:
  * A section with the business phone.
  * A section with the business email.
  * A section in which the user can send an email from the page by means of a form in which the client enters his name, his electronic mail and the description of what he needs.
  * A section for the legal notice, specifying that the use of the electronic mail is only for communication purposes and the information will not be used or sold to third parties.
  
* **About us tab:** In this tab you will find the information of the business so that the user can know about it, it must include the following:
  * Information about what the business does and why it does it.
  * The history of the business.
  * A presentation of the people involved in the business.
  * A photograph of the people involved in the business.
  
* **Calendar tab:** This tab shows a calendar in which you can display information about business events, this tab should include the following:
  * A calendar in real time.
  * A form in which the client enters his name, email and the description of the service he would like to hire when selecting a calendar date.
  * A section for the legal notice, specifying that the use of the electronic mail is only for communication purposes and the information will not be used or sold to third parties.
  
* **Previous works tab:** In this tab some of the previous works of the business will be shown as a sample for the users, this tab should include:
  * Photo galleries divided according to the type of event.
  * Legal notice to let you know that the images shown are for sample only and are subject to copyright.
  
* **Package tab:** This tab describes the photo packages that the business handles, it should include:
  * The name of the package, what that package contains, its price and description.
  * A legal notice to warn that the packages are subject to price changes and availability.
  
### Product functions
On the website the owner will be able to:
* Add, modify or delete information found on the website.
* Add or delete photographs that are on the website.
* Receive emails through the website.

On the website, the user will be able to:
* Send emails through the website.
* Reserve dates for events.
  
### User Characteristics
| User    | Details           |
| ------------- |:-------------:|
| Administrator | The administrator will be responsible for adding, modifying or deleting content from the website.|
| User   | The user is the one in charge of using the website, enter the different sections and fill out the contact forms as required.|
| Manager | The manager will be responsible for keeping the information on the website updated and available to users.|
| Assistant| The assistant will manage the business email and respond to users.|


### Constraints

* To be able to add a photo to the website you must have the permission of those involved in it.
* All emails entered on the website must be used only and exclusively for informational purposes.
* The calendar that will be used is an extension of google.
* The domain of the website must be .MX at the request of the business owner.

### Assumptions and dependencies
* The consent of the clients is required to place their photos on the website.
* The connection with the Google calendar extension and a Google mail account is required for this to work.

## Specific requirements
### User Requirements
The website must be composed as follows:
* **Main page:** It will be the first screen that the user will see when he enters, this screen must contain the following:
  * A banner with the logo of the business and the name of the page.
    * This banner should be found at the top of the page.
  * The tab bar for the different sections of the page should be under the banner and its operation should be like a menu.
    * When the user clicks on one of the tabs it will be redirected to the corresponding tab, also when the user puts the cursor on the tab a popup menu will appear with hyperlinks in which the user can click to go directly.
  * A slider with the most outstanding previous works.
    * The slider must contain 8 photos, it must have a button on the left and another on the right so that when the click user can scroll either forward or backward.
    
* **Contact tab:** In this tab you will find the necessary information so that users can contact the business owner, it must include the following:
  * A banner with the logo of the business and the name of the page.
    * This banner should be found at the top of the page.
  * The tab bar for the different sections of the page should be under the banner and its operation should be like a menu.
    * When the user clicks on one of the tabs it will be redirected to the corresponding tab, also when the user puts the cursor on the tab to popup menu will appear with hyperlinks in which the user can click to go directly.
  * A section with the business phone, email and facebook.
    * This section should go under the tab bar on the right side.
  * A section in which the user can send an email from the page by means of a form in which the client enters his name, his electronic mail and the description of what he needs.
    * This section should go under the tab bar on the left side, it should contain 3 text fields, one for the user to enter their name, another field for the user to enter their email address and another to describe what you need, below the text fields should be 2 buttons, one on the left side to send the information and the other on the right side to clean the form.
  * A section for the legal notice, specifying that the use of the electronic mail is only for communication purposes and the information will not be used or sold to third parties.
     
* **About us tab:** In this tab you will find the information of the business so that the user can know about it, it must include the following:
  * A banner with the logo of the business and the name of the page.
    * This banner should be found at the top of the page.
  * The tab bar for the different sections of the page should be under the banner and its operation should be like a menu.
    * When the user clicks on one of the tabs it will be redirected to the corresponding tab, also when the user puts the cursor on the tab to popup menu will appear with hyperlinks in which the user can click to go directly.
  * The information and history of the business.
    * This information should be located just below the tab bar, the text should be justified.
  * A presentation and a photograph of the people involved in the business.
    * The photograph of the person involved must go from the left side and the text must be justified and surrounding the photograph.  

* **Calendar tab:** This tab shows a calendar in which you can display information about business events, this tab should include the following:
  * A banner with the logo of the business and the name of the page.
    * This banner should be found at the top of the page.
  * The tab bar for the different sections of the page should be under the banner and its operation should be like a menu.
    * When the user clicks on one of the tabs it will be redirected to the corresponding tab, also when the user puts the cursor on the tab to popup menu will appear with hyperlinks in which the user can click to go directly.
  * A calendar in real time.
    * The calendar should be under the tab bar, it should be centered.
  * A form in which the client enters his name, email and the description of the service he would like to hire when selecting a calendar date.
    * This form should be under the calendar on the left side, it should contain 3 text fields, one for the user to enter their name, another field for the user to enter their email address and another to describe what you need, below the text fields should be 2 buttons, one on the left side to send the information and the other on the right side to clean the form.
   * A section for the legal notice, specifying that the use of the electronic mail is only for communication purposes and the information will not be used or sold to third parties.
     * This section should be located at the bottom of the web page, below the buttons of the form so that the user can see it.

* **Previous works tab:** In this tab some of the previous works of the business will be shown as a sample for the users, this tab should include:
  * A banner with the logo of the business and the name of the page.
    * This banner should be found at the top of the page.
  * The tab bar for the different sections of the page should be under the banner and its operation should be like a menu.
    * When the user clicks on one of the tabs it will be redirected to the corresponding tab, also when the user puts the cursor on the tab to popup menu will appear with hyperlinks in which the user can click to go directly.
  * Photo galleries divided according to the type of event.
    * The photo galleries must be under the tab bar, they must be separated according to the event, starting with XV party, children's party, baptism, smash cake, baby welcome, seasonal. The first 3 events will be aligned below the tab bar and the other 3 events will be below them.
    * Clicking on a gallery will show all the photos of that gallery ordered, by clicking on a photograph of the gallery you will enter a full screen mode and you can navigate with the directional arrows or by clicking on the side buttons.
  * Legal notice to let you know that the images are shown for sample only and are subject to copyright.
    * This message should be just below the galleries of the events and within each gallery.

* **Package tab:** This tab describes the photo packages that the business handles, it should include:
  * A banner with the logo of the business and the name of the page.
    * This banner should be found at the top of the page.
  * The tab bar for the different sections of the page should be under the banner and its operation should be like a menu.
    * When the user clicks on one of the tabs it will be redirected to the corresponding tab, also when the user puts the cursor on the tab to popup menu will appear with hyperlinks in which the user can click to go directly.
  * The name of the package, what that package contains, its price and description.
    * The information must be on the left side below the tab bar.
    * TBD the order and information of the packages, the business owner does not provide that information yet, it is looking to schedule a meeting to get the details.
  * A legal notice to warn that the packages are subject to price changes and availability.
    * This information must be located right at the end of the information of the packages so that the user can see it easily.
### System Requirements
### Functional Requirements
### Non functional requirements

## Supporting Information 
### Appendixes
#### Elicitation process
All the information in this document was obtained through an informal interview with the client on April 7, 2019, he was asked questions about the functions that the website would like to have, and suggestions about some of those functions.

The client already had a design in mind for the page, the main page should contain the logo and the name of the business at the top so that when it was entered the page would be the first thing that was visible, under the logo and the name wanted a bar with different tabs that would function as hyperlinks to the other sites on the website, he mentioned that he wanted the user to click on the tab and be redirected to the corresponding tab, the suggestion was made to add in addition to that the option that when the user puts his cursor on a tab a menu will be displayed with the hyperlinks related to that tab giving the option to the user to go directly to the section he wanted, the client accessed this function and it was agreed to make the tab bar in this way, both the logo and name at the top of the page and the tab bar below, is something that will be present you in all the sites of the web page according to the client. He also mentioned that under the bar he wanted a slider of images that contained the 8 most representative photographs of his work selected by him, the slider must contain a button on the left and one on the right side so that users can move between the images.

In the contact tab, the client wants to show the necessary information so that users can contact the owner of the business, specific that it must contain the same structure as the home page, which would be the logo and name in the top of the page, the tab bar below the logo as mentioned above. Below the tab bar on the right side you will find a section with the business phone number, email and business Facebook page. Under the tab bar on the left side you should find a form so that the user can contact the business owner from the page if they wish, the form must contain a field to enter the customer's name, another field to enter your email and a field where you can add a description of what the customer needs, the specific client that under the form must contain 2 buttons, a button on the left side to send the form information and another on the side right to clean the information on the form. In addition, the client wants a legal notice added below the buttons so that the user can read it, in which it is specified that the use of electronic mail is only for communication purposes and that the information will not be used or sold to third parties.

In the about us tab, the client wants to show the information related to the business so that users can know about the origin of the business and those involved in it. As specified above, the structure of the logo and the tab bar is applied in the same way, the logo and name on the top and below the tab bar. Under the tab bar you will find a section with a brief history of the business and the text of the story should be justified, below the history of the business you should find a presentation section, in which a photograph should appear of those involved in the business with their name and a brief introduction of themselves, the photograph must go from the left side and the text must be justified and surrounding the photograph.

In the calendar tab, the structure of the logo and name is followed in the upper part and below the tab bar. The client wants a calendar to be displayed under the tab bar in the center, he wants the calendar to be shown in real time, with the dates that are already reserved with events and with the dates available for events, under the calendar it will be You will find a form on the left side in which users enter their name, email and a description of the service they want to hire with the date they would like, below the form there will be 2 buttons, one on the left side to send the information of the form and on the right side another button to delete the form information. A legal notice must be added specifying that the use of the electronic mail is only for communication purposes and that the information will not be used or sold to third parties, this notice must be just below the form buttons where the user can read it.

In the previous works tab, the structure of the logo and name in the upper part and the tab bar below is the same. Under the tab bar you will find photo galleries arranged according to the type of event, starting with XV party, children's party, baptism, smash cake, baby welcome, seasonal. The first 3 events will be aligned below the tab bar and the other 3 below them. Clicking on a gallery will display all the images of that gallery ordered and clicking on an image will enter full screen mode where you can navigate with the directional arrows or click on the side buttons. Below the galleries you will find a legal notice informing you that the images shown are only a sample and are subject to copyright.

In the packages tab, the same structure is still used, the logo and business name in the upper part and below the tab bar. In this section the name of the package will be added below the tab bar, which contains the package, its price and its description. The information should go from the left side just below the tab bar. Under all packages you should find a legal notice informing that the price of the packages may be subject to price and availability changes.

#### Process
With this the part of the functions of the website was terminated, now the client told us how the process should be on the page, the process begins when the user enters the website.

When the user enters the web page must be redirected to the main page, on this page the user can check the page and decide if it is of interest, here the user can click on the tabs to see the other sections of the web page depending on what is of your interest.

If the user wants to see the "contact" section, he / she must click on the contact tab and this will be redirected to the contact page, here the user can observe the information that is provided or contact the manager directly through the page, if you want to contact the manager through the page you must fill out the form that is on the page, you must enter your name, your mail and a description with the questions you have or the reason why you are contacting the person in charge, the user has the option to send the information or clean the form in case of having made a mistake in the data he entered. When you press the send button, an email is sent to the business email account and is received by the administrator assistant, once the assistant receives the email, it verifies the user's information and depending on the description provided by the assistant contact to answer your questions, according to the medium that the user gave the contact is done by phone or email, if both media were provided the priority will be to contact him by phone because it is a faster and more direct than the email. The contact process would be this way, the response time may vary, but on average it takes 2 to 3 hours to respond to the user once the assistant received the email.

If the user wants to know about the business, then you must click on the "About us" tab to be redirected to it, here you will find the history of the business, as well as the people who are related to it.

If you want to make a reservation, the user must click on the "Calendar" tab where you can see a calendar in real time with the available dates, if you want to reserve a date you must fill out a form that is below the calendar, the user enters their name, email and description of the service they want to hire, also all the information related to what they need such as place, date and time, type of event and anything related to the job, then if the information is You can press the send button or you can clean the form, if you press the send button, an email will be sent to the business email and received by the administrator assistant. When the assistant receives the email, it reviews the user's data and work requirements and then evaluates whether the work can be done, if it is possible to carry out the work, the assistant contacts the person in charge, the person in charge reviews the information and assigns a photographer for the event, the photographer confirms the data and the information is provided to the assistant again, once the assistant has all the work information contact the user, the means of contact depends on the information provided by the user, if I provide email and phone, priority is given to contacting a phone call as it is a faster and more direct means.

If the user is interested in seeing the previous work of the business, you can click on the "Previous Works" tab, where you can see image galleries according to the types of events, depending on the type of event you want to see, the user you only have to click on the gallery of your choice to see the images, if you click on an image you enter in full screen mode and if you want you can go back to see the other galleries.

Finally, if the client wants to see the information related to the packages already established, he should only click on the "Package" tab and there he will be able to see all the information.

Once the client finished specifying the process, the functions and the order he wanted the web page to have, he checked the requirements to ensure that they were interpreted in the way he had wanted it, the client accepted the way that the requirements were interpreted and these requirements were added to the SRS document.

### BPMN
* General Process

![Proceso General](/BPMN/General.jpg)

  * Sub Process Contact tab
  
  ![Contact Tab](/BPMN/ContactTab.jpg)
  
  * Sub Process About Us tab
  
  ![About Us Tab](/BPMN/AboutUsTab.jpg)
  
  * Sub Process Calendar tab
  
  ![Calendar Tab](/BPMN/CalendarTab.jpg)
  
  * Sub Process Previous Works tab
  
  ![Previous Works Tab](/BPMN/PreviousWorksTab.jpg)
  
  * Sub Process Package tab
  
  ![Package Tab](/BPMN/PackageTab.jpg)
