##  A/R Invoice Printing (AR.F2)

<PageHeader />

##

![](./AR-F2-1.jpg)

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
  
**Print Company Name** Check this box if you want the company name and address
printed on the page. You would normally check this box if you were printing to
blank paper so that the company name would appear on the form. Unchecked
allows you to use standard letterhead which already contains the company name
and address.  
  
**AR Item** Enter all of the invoice numbers to be printed, or leave this
field blank to print a range of invoices by previous print date range, or
invoice number range. To print all invoices that were not printed previously,
leave this field and all of the remaining fields blank.  
  
**Company Code** This field is used with the date/invoice range fields. If
left blank all company codes will be selected else only invoices with the
specified company codes will be included.  
  
**Starting Date** Enter the starting date to be used in selecting previously
printed invoices.  
  
**Ending Date** Enter the ending date to be used when selecting previously
printed invoices.  
  
**Use Print Date** Check this box if you wish select invoices based on the
date the invoice was originally printed. If this box is not checked, the
invoices will be selected based on the invoice date.  
  
**Starting Invoice** If selecting invoices by invoice number range, enter the
first invoice number in this field.  
  
**Ending Invoice** Enter the ending invoice number to be used when printing a
range of invoice numbers.  
  
**Last Status Message** Contains the last status message generated by the
program.  
  
**Last Status Date** The date on which the last status message was generated.  
  
**Last Status Time** The time at which the last status message was generated.  
  
  
<badge text= "Version 8.10.57" vertical="middle" />

<PageFooter />