## SD Stores Manager Releases

### 3.0.6

#### Enhancements

- AppSource App - A minor modification was made to the Generate Picks functionality.

### 3.0.5

#### Enhancements

- AppSource App - A change was made to the licence expiry notification. The logic for checking for expiry dates was reworked.

- AppSource App - Enhancements were made to the App Request Subscription page.

- AppSource App - Additional phrases were added as search phrases for the SD Stores Manager pages.

- AppSource App - ToolTips were updated in the About, Product Activation, and Tenant Subscription pages.

### 3.0.4

#### Enhancements

- AppSource App - The standard Batch Post Sales Orders Report on the Route Overview page takes two new parameters in the InitializeRequest function. The action on the page was updated to supply the new parameters to the report.

- AppSource App - A change was made to the Assisted Setup functionality.

- AppSource App - The links in the About page were updated.

- AppSource App - The logo in the App was updated to the new logo.

### 3.0.3

#### Enhancements

- AppSource App - A change was made to limit the SD ISV Tenant Subscriptions page to display just our SD ISV AppSource Apps and not other SD PTE Apps.

#### Bug Fixes

- AppSource App - When selecting SD Stores Manager activity pages in the Tell Me/Search in a BCv22 environment, the activity pages were hanging.

- AppSource App - An error will raise in the Assisted Setup import if non sequential enum values exist in the imported data. This was fixed.

- AppSource App - A change was made to the ISV Licence Notification procedure in SD Stores Manager to fix an issue that would raise an error when the language is changed from English to another language.

### 3.0.2

#### Enhancements

- BCv21 App - The Licence Message displayed on first install of SD Stores Manager was changed to prompt the user to activate a free trial and to choose Assisted Setup from the Setup Card to create demo data.

### 3.0.1

#### Enhancements

- BCv20 App - Functionality was added to prevent workers from deferring all lines on a Job. 

#### Bug Fixes

- BCv20 App - An issue was fixed with posting Deferred Picks where an error was raised that there was nothing to post. Also, when shipping the job for the defer pick line the shortage quantity on the shortage line was also shipped. 

- BCV20 App - The About action was missing from the SD Stores Manager Setup Card. 

### 3.0.0

#### Enhancements

- BCv20 App - The v2.1.0 C/AL release of SD Stores Manager was converted from C/AL to AL extensions. 

- BCv20 App - A change was made to allow users search on the SD Stores Manager Role Centre Activities in the Tell Me. 

- BCv20 App - The Assisted Setup action and functionality to import the Assisted Setup was added. 

- BCv20 App - The usage category property was added to the pages for the Tell Me search. 

- BCv20 App - Permission sets were created for the product. 

- BCv20 App - The size of standard Dynamics 365 Business Central description and name fields used in the App were increased as as per the standard Dynamics 365 Business Central change. 

- BCv20 App - The latest version of the ISV About page was added to the product. 

- BCv20 App - The existing objects in the App were renamed to our ISV standards. 

- BCv20 App - The SD Stores Manger reports with barcodes were modified to use API calls to create the barcodes. This removed the need to install barcode fonts as part of the product installation. 

- BCv20 App - New fields and pages were added to the SD Stores Manager Setup card for the reworked barcode scanning functionality. 

- BCv20 App - Removed the barcode prefix field and the functionality used to determine the barcode type from the code base. 

- BCv20 App - Added functionality to focus the barcode field for barcode scanning. 

- BCv20 App - Background barcode scanning functionality was added to the App. 

- BCv20 App - The latest version of the ISV Controller was added to the App. 

- BCv20 App - A new KPI page was created to display key pick information.  

- BCv20 App - Four new reports were created to report on Pick Errors by Customer, Pick Errors by Item, Pick Errors by Picker, and Pick Errors by Reason Code. 

- BCv20 App - A KPI FastTab was added to the SD Stores Manager Setup Card. 

- BCv20 App - Changes were made to the Menu Groups in the Route Overview and a small typo was fixed on the page. 

- BCv20 App - A change was made to prevent the Cancel button on Confirm Job Card to allow users cancel out of Job. Users must either complete the job or leave the job incomplete and record a shortage. 

- BCv20 App - The caption and title of the Pick Shortages report was updated to differentiate it from the Shipment Shortages report. 

- BCv20 App - The caption and title of the Shipment Shortages report was updated to differentiate it from the Pick Shortages report. 

- BCv20 App - The Licence Expiry notification was updated to show the SD Stores Manager App name in the notification.  

- BCv20 App - A duplicate action cue was removed from the SD Stores Manager Manager Role Centre. 

- BCv20 App - Functionality was added to find the default bin for a substitute item and update the Job Lines and the Sales Order with the default bin. 

- BCv20 App - Changes were made to the footer in the Pick Shortage Report. 

- BCv20 App - The standard Sales Line page and table was extended with a new comment field that pulls through to the Pick Job Line and prints on the Pick Instruction report. 

- BCv20 App - The caption on the Background Scan Setup action on the SD Stores Manger Card was changed. 

- BCv20 App - On the Confirm Job Card the Auto Fill Qty. to Handle action was moved to the top most level of the page menu. 

-  BCv20 App - The caption on the SD Stores Manager Sales Order Activity group was updated to fix a small typo. 

- BCv20 App - The Stores GRN action was surfaced as an action cue on the Role Centres and placed in a SD Stores Manager Purchase Order Activities action group.    

- BCv20 App - ToolTips were updated on the SD Stores Manager Setup Card to explain the fields on the card. 

- BCv20 App - In the SD Stores Manager Setup Card certain fields were promoted to display on collapse of the FastTabs. 

- BCv20 App - A small typo on the SD Stores Manager Job History List was updated. 

- BCv20 App - Standard Dynamics 365 Business Central notes and link actions were removed from the SD Stores Manger pages to keep the page clean and clutter free. 

- BCv20 App - The Usage Category property was updated on pages and reports to allow users search for these objects in the Tell Me. 

- BCv20 App - A page was created to display all installed Simply Dynamics Apps and Subscription details for the tenant. 

- BCv20 App - The ISV Licence expiry message was updated to show the App name. 

- BCv20 App - A small typo was fixed on the Pick Shortage List. 

- BCv20 App - The message displayed when closing a job with lines that have a shortage was updated to fix a typo. 

- BCv20 App - A Generate Picks and a Route Overview action cue were added to the SD Stores Manager Role Centre. 

- BCv20 App - Functionality was added when shipping a Pick Job with a 0-quantity line on the Pick Job, SD Stores Manager updates the source Sales Order and sets the Quantity to 0, Unit Price to 0, Line Discount % to 0 and the Completely Shipped flag to true. This functionality can be enabled by choosing the Close Lines on Pick Post option on the SD Stores Manager Setup. 

- BCv20 App - The Product Activation page was updated to point to the new CRM URL. 

- BCv20 App - Tooltips were updated to look at our new website. 

- BCv20 App - Functionality was added to SD Stores Manager to allow for substitutions at Pick level/Job Line level. 

- BCv20 App - ISV Licence expiry validation checks were added to the code. 

- BCv20 App - A Test Codeunit was created for AppSource submission. 

- BCv20 App - The product was readied for AppSource submission. 

- BCv20 App - Standard notes and link actions were removed from the SD Stores Manager pages to keep these pages as streamlined and simplified as possible. 

- BCv20 App - Changes were made to the About page. The latest version of the product and the AppSource URL were added to the About page. 

- BCv20 App - Captions were updated on all objects for future translation requests. 

- BCv20 App - Flowfields were added to the Route Overview to allow filtering of <= Workdate and >Workdate fields. 

- BCv20 App - Functionality was added to allow Delivery Dockets to print off the Manifest. A new field was added to the SD Stores Manager Setup card to allow users define the Delivery Docket report to use. 

- BCv20 App - Orders Past and Orders Future flowfields with filters were added to the Route Overview to view flowfield counts of sales orders for future and past dates. 

- BCv20 App - KPIs were added to the Route Overview. 

- Bcv20 App - Functionality was added to allow users to Defer Picks. 

- BCv20 App - An Auto Assign Lot No Series field was added to the SD Stores Manager Setup card. 

- BCv20 App - Functionality was added to allow for over picking. 

- BCv20 App - Functionality was added to SD Stores Manager to allow for under picking. 

- BCv20 App - Changes were made to specify over pick tolerances per item. 

- BCv20 App - Functionality was added to log information on shortages and retain a history on the shortages. 

- BCv20 App - The layout of the SD Stores Manager Manager Role Centre was reviews and minor modifications were made. 

- BCv20 App - The layout of the SD Stores Manager Worker Role Centre was changed to make the logic of the workflow easier to follow. 

- BCv20 App - Minor changes were made to the SD Stores Manager Reports. 

- BCv20 App - An action item was removed from the SD Stores Manager Role Centre. 

- BCv20 App - The Activity panels in the Role Centre were split out into individual searchable pages. 

- BCv20 App - Lot Tracking was added to the Job Lines. 

#### Bug Fixes

- BCv20 App - On install of the App clicking no to activate licence key and was hiding all the cues in the Role Centre and displaying an error. This issue was fixed. 

- BCv20 App - Fixed an issue where users could bypass the validation on the Confirm page by choosing the x to close the page. 

- BCv20 App - Some field captions in the Manifest report are not displaying in full. 

- BCv20 App - The Product Activation page was changed to disable Activate button unless the Product Key is filled in to avoid an error being raised when the Activate button is chosen. 

- BCv20 App - A change was made to the Manifest Report to print the Shipment Date entered on the report request page on the Shipment Date in the report header. 

- BCv20 App - A fix was made to the SD Stores Manager  - Pick List Report to stop the barcode image wrapping on the report. The image space for the barcode was extended. 

### 2.1.0

#### Enhancements

- Added Pick Generation Events.

- Updated the Time Spent Caption in the Worker Productivity Report to Time Spent on Completed Jobs.

#### Bug Fixes

- Fixed bug where when logged in as a Picker/Worker, and selecting to Request/Confirm Job, if a pre-Assigned Pick is at Pendingstatus, the Pick was not being assigned.

- Added filters to the Worker Productivity Report to allow a Stores Manager to filter on reported productivity within a filtered daterange/time frame - filtering on Job Header/Line and Job History Header/Line tables.

- Fixed bug in Route Overview Page on Ship Routes Action.

- Prevented Re-Opening of Sales Order when a Pick exists for the Sales Order.

- Fixed Caption on the Required Fiter Heading in SD-SM Manifest Report.

- Change was made to include Barcode Font in MSI.

- Fixed an issue with NAV 2017 rendering of the Barcode Font.

- Error raised when importing data from xml file into SD Stores Manager.

- Limited the characters that can be used in the Worker Code to ones that the Barcode supports.

- In the Worker Table changed the DropDown Field Group to Code,Name,Location Code.

### 2.0.0

#### Enhancements

- Created a new Job Line Reason Code table, page and functionality.

- Created a Readme.txt file.

- Upgraded code to NAV 2016.

- Additions to the Manager Role Centre.

- Route Overview Table - add a Date Filter flowfilter field and update the calcformulas to use this - apply the filter to the "shipmentdate" on the job header and sales header.

- Created a new Activities Centre for the Stores Manager Role Centre. Created Cues for All Sales Orders, Open Orders (by status),Released Orders (by Status).

- Route Overview page - Ship Routes Action - allow to ship incomplete picks in the routes.

- Created Pick Job picker tracking functionality.

- Add the Item Description to the Job History Line table.

- Improvements to the Stores Manager Role Centre.

- Pick Instructions - Add a field to the setup table, "Pick Comment Field No.", this is the field no on the sales line for the comment thatwill be copied to the job line on generation of the pick.

- Add an "Assign Priority" Action to the Job List page that will display a page that allows the user to enter a priority and assign theentered value to the selected pending job header records.

- Added Pick Error and Solution Logging functionality.

- Created Pick Solution Logging functionality.

- Created Pick Error and Solution Reporting.

- Assign a Picker to a Shipping Agent.

- Allow for Zonal Picks.

- In the Role Centre, in the Sales Order Summary Activities allow drilldown on Sales Order Cues.

- In the Job Header List Page and the Job History Header List Page, surface Zone Code, Bin Prefix, and Bin Code fields.

- In the Job Header/Lines Pages and Job History Header/Lines pages, surface the new Issued field on Job Header/Lines and Job HistoryHeader/Lines Pages so a Store Manager can view how long a Pick has been sitting with a Picker.

- Remove the Stock Take Action from the SD Worker Role Centre.

- On the Job Lines Page and the Job History Lines Page - surface the Comment field.

#### Bug Fixes

- Pick Worker Mapping List - When setting up a record in the Pick Worker Mapping List, users can select the Location Code, theShipping Agent, Take Effect but cannot enter a Worker. The Worker field is read only, this field needs to be changed to editable.

- SD-SM Job Header Table - Assigned and Issued Date-Time Stamp Fields - Fixed bug that caused per-assigned Jobs to be assignedagain on Job request.

- Route Overview> Job List (Pending) SD-SM Job Header List > Assign to Worker. When assigning a Worker with no Location specifiedin the Worker table to an Order, an error was raised.

- Error raised when running Worker Productivity Report.

- Fixed bug in Worker Pick Errors Chart.

- Fixed bug in Customer Pick Errors.

- Fixed bug in Item Pick Errors.

- Fixed bug in Error Reason Pick Errors.

- Job Header List Page - Printing a Pick Instructions from the Job Header List page applied a filter to the page.

### 1.0.0

#### Enhancements

- Created installation instructions.

- Improved the Barcode Scanning AddIn.

### 0.12.3

#### Enhancements

- This was an early release of SD Stores Manager.

