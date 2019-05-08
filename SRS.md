# SRS
## 1. Introduction

### 1.1 Purpose
This SRS aims to define and clarify all the requirements for the realization of a web page on a photographic session business, in which you can make reservations for dates for events, consult packages, prices, as well as review photographs of previous sessions.

The requirements that will be seen here, will be provided by the client and defined so that both the client and the developer of the website can understand and apply them in the best possible way.

### 1.2 Scope
The website to develop "Valdez fotografias" will be a place where people can enter to perform any of the following actions:
* Verify availability of dates and reservations.
* Check packages and prices.
* See previous works.

The purpose of the website is to provide the client with a way to manage their business in a more optimal way, since now everything is done through Facebook, promoted by Facebook, upload their previous work through Facebook, if a user wants Information about a packet is made through Facebook messages, etc. that is why having the website a large part of the information that users need will be available in a more simple way, avoiding having to send a message to the facebook page and wait for an answer, this helps customers to get the information in an easier and faster way, while reducing the burden for the owner to have to answer messages individually for each client.

### 1.3 Definitions, acronyms, and abbreviations
* **etc:** Abbreviation of etcetera, an expression used to replace the rest of an enumeration that is understood thanks to the context.
* **reservations:** Save or set aside something in the future, in this case set a date in the near future.
* **Slider:** It is an element of a web page that shows multiple images and text that alternate between them.
* **Domain:** A domain is the unique and exclusive name with which a web page will be identified on the Internet.
* **Hyperlink:** It is a link that connects one document with another, that allows a new page on the Internet with just a click on it.
* **TBD:** To Be Determined.

### 1.4 References

### 1.5 Overview
The rest of the document contains the functions of the web page in more detail, section 2 looks in depth at the product perspective, the function of the product and the characteristics of the user, the constraints, as well as the assumptions and dependencies, in Section 3 is where the specific requirements of the website are discussed.

## 2. Overall description

### 2.1 Product perspective
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
  
### 2.2 Product functions
On the website the owner will be able to:
* Add, modify or delete information found on the website.
* Add or delete photographs that are on the website.
* Receive emails through the website.

On the website, the user will be able to:
* Send emails through the website.
* Reserve dates for events.
  
### 2.3 User Characteristics
| User    | Details           |
| ------------- |:-------------:|
| Administrator | The administrator will be responsible for adding, modifying or deleting content from the website, he will be responsible for keeping the information on the website updated and available to users. |
| Client   | The client or user is the one in charge of using the website, enter the different sections and fill out the contact forms as required.  | 

### 2.4 Constraints

* To be able to add a photo to the website you must have the permission of those involved in it.
* All emails entered on the website must be used only and exclusively for informational purposes.
* The calendar that will be used is an extension of google.
* The domain of the website must be .MX at the request of the business owner.

### 2.5 Assumptions and dependencies
* The consent of the clients is required to place their photos on the website.
* The connection with the Google calendar extension and a Google mail account is required for this to work.

## 3. Specific requirements
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
