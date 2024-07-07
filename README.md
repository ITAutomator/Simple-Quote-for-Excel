## Simple Quote for Excel  
User guide: [PDF](https://github.com/ITAutomator/M365-Teams-Policy-Update/blob/main/Simple%20Quote%20for%20Excel%20Readme.pdf)    
Download: [ZIP](https://github.com/ITAutomator/M365-Teams-Policy-Update/archive/refs/heads/main.zip)    
Website: [WWW](https://www.itautomator.com/m365-teams-policy-report-and-update/)   
(or click the green *Code* button (above) and click *Download Zip*)     

**Overview**   
Create simple PDF quotes using an Excel table.  
![image](https://github.com/ITAutomator/Simple-Quote-for-Excel/assets/135157036/6759c5aa-81d7-4f7b-8419-c45320afd75c)

**Features**   
Enter descriptions, quantities, and prices.  Include links to product pages.  
Copy and paste existing quotes to new quotes.  
Easily export to PDF, named by quote number etc.  
Template with a customer header, logo, etc.  
Group items into ItemGroups within your quote.  

**Screenshots**  
![image](https://github.com/ITAutomator/Simple-Quote-for-Excel/assets/135157036/8ff37aae-9529-4ad8-a37b-a8b25f707ea1)
![image](https://github.com/ITAutomator/Simple-Quote-for-Excel/assets/135157036/e633a71c-228b-4a5c-b775-01e01a6a3546)


**Pricing**  
Up to 10 quotes are free. Old quotes can be removed to continue to use free version.
Up to 100 quotes $20
Up to 1000 quotes $100
Unlimited quotes $500
See www.itautomator.com to purchase or for more information.

**Quick start**  
Press New Quote  
Enter the information for your quote.  
Press Quote to PDF, then Export PDF to create the pdf file.  

**Customizations**  
**PDF tab**  
Change the highlighted portions of the template.  
Change the top right area using your logo and contact information.  
Change any quote disclaimers necessary.  
![image](https://github.com/ITAutomator/Simple-Quote-for-Excel/assets/135157036/45aee300-57fe-4e47-b136-186e51b10519)

**Info tab**  
Change information in the orange cells.  
varQuoteBase: enter the starting number of your quotes.  
varLicenseKey: enter the license key you’ve purchased (or leave blank to use free version)  
varFilePrefix: if you want your pdf names prefixed with something, put it here.
![image](https://github.com/ITAutomator/Simple-Quote-for-Excel/assets/135157036/4236a098-aa9e-4d41-8489-7277986786eb)

**Entering Quotes**  
**Quotes tab**  
Fill in the Orange (required) columns.  
Header columns are dark orange and must be repeated (copied down)  
Detail columns are light orange  
Detail columns can be grouped by repeating the Item Group name (copied down)  
Non-orange columns are optional  

**Quote columns**  

|Name|Description|
|--|--|
|QuoteNo|Enter a valid quote number (or use New Quote button)|
|QuoteCustomer|Customer Name|
|QuoteNo|Enter a valid quote number (or use New Quote button)|
|QuoteCustomer|Customer Name|
|Agent|Employee Initials|
|QuoteName|Quote Name|
|QuoteDate|[enter data]|
|LineNo|See SortBy column for sorting rows|
|ItemGroup|Create ItemGroups by repeating a group name (Optional)|
|ItemDescription|[enter data]|
|MoreInfo|put URL link here (type the word link and press Ctrl-K to enter a URL)|
|Qty|[enter data]|
|UnitPrice|Per Unit Price|
|PriceExt|[calc]|
|Vendor|purchased from|
|UnitCost|cost per unit|
|CostExt|[calc]|
|ItemCode|Does this item need to be taxed on invoice (Enter a T or any suitable item code)?|
|Shipping|Does Shipping and Handling apply (Enter any amout to appear as additional line  charge for invoice)|
|Profit|[calc]|
|Status|Status codes are customizable|
|QuoteTtl|[calc]|
|QuoteCost|[calc]|
|QuoteProfit|[calc]|
|SortBy|sort by this col|
|QuoteNote|This appears on quote header|
|InternalNotes|Does not show on quote|

**Quote Exporting to PDF**  
Enter the Quote number and click Quote Lookup or click PDF Quote  
Click Export to PDF to save the quote (to the current folder)  

