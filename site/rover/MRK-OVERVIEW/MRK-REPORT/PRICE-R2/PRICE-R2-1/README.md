##  Configuration Price Breakdown (PRICE.R2)

<PageHeader />

##

![](./PRICE-R2-1.jpg)

**Job ID** Enter a unique ID if you wish to enter and save the parameters to
this procedure for future use. If you only need to run the procedure and do
not want to save your entry then you may leave this field empty.  
  
**Destination** Select the destination for the output from this procedure.  
  
**Process** Select the method to be used for processing the report. Foreground
is always available and must be used when output is directed to anything other
than a system printer (i.e. printers spooled through the database on the host
computer.) Depending on your setup there may be various batch process queues
available in the list that allow you to submit the job for processing in the
background or at a predefined time such as overnight. A system printer must be
specified when using these queues.  
  
**Format** Select the format for the output. The availability of other formats
depends on what is allowed by each procedure. Possible formats include Text,
Excel, Word, PDF, HTML, Comma delimited and Tab delimited.  
  
**Layout** You may indicate the layout of the printed page by specifying the
appropriate setting in this field. Set the value to Portrait if the page is to
be oriented with the shorter dimension (usually 8.5 inches) at the top or
Landscape if the longer dimension (usually 11 inches) is to be at the top.
Portrait will always be available but Landscape is dependent on the output
destination and may not be available in all cases.  
  
**Copies** Enter the number of copies to be printed.  
  
**Run Process** Click on the button to run the process. This performs the save
function which may also be activated by clicking the save button in the tool
bar or pressing the F9 key or Ctrl+S.  
  
**Part Number** Enter the part number that will be used for the configuration
price listing.  
  
**Quantity** Enter a quantity if you want to have it used in the price configuration process. This would apply if quantity price breaks are defined in [ PRICE.E ](../../../../../rover/AP-OVERVIEW/AP-ENTRY/ACCT-CONTROL/ACCT-CONTROL-1/ar-e/CUST-E/CUST-E-1/PRICE-E) . If no quantity is entered, then a quantity of one is assumed.   
  
**Cust ID** Enter a customer number if contract pricing is to be considered in
the price breakdown.  
  
**Cust Name** The customer name is displayed here for information only.  
  
**Cust Code** Enter the customer code used to determine pricing for the item.
This field will be defaulted from the customer if a customer number was
entered. It can be entered without an associated customer number, or left
blank.  
  
**Effectivity Date** If you want to specify a particular date for contract or
price effectivity, enter the date here. If not entered, the current date will
be used.  
  
**Last Status Message** Contains the last status message generated by the
program.  
  
**Last Status Date** The date on which the last status message was generated.  
  
**Last Status Time** The time at which the last status message was generated.  
  
  
<badge text= "Version 8.10.57" vertical="middle" />

<PageFooter />