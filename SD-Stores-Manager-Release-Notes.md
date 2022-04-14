## SD Stores Manager Releases

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

