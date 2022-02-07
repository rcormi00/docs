##  Invoice E-Form Printing (AR.F4)

<PageHeader />

##

![](./AR-F4-1.jpg)

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
  
**Invoice Number** Enter all of the invoices you want to have printed. If you
wish to print all invoices not yet printed, then leave this and all other
fields null. Otherwise, you may leave this field null and select a range of
dates or invoices to print.  
  
**Use Foreign Currency** Check this box if you want the invoice to print with
the foreign currency amount and not in U.S. dollars. The amount will print for
the currency code entered on the invoice. If no currency code has been entered
on the invoice, the amount will appear in U.S. dollars.  
  
**Customer** If you wish to print invoices for a specific customer, enter the
customer number(s) in this field. If you enter a invoice number, this field
will be ignored.  
  
**Company Code** If you are printing invoices for a date or invoice number
range and only want to select the invoices for a specific company codes enter
those company codes in this field. If you enter a invoice number, this field
will be ignored.  
  
**Form Name** Select the form to be used.  
  
**Start Date** If you wish to reprint all invoices which were originally
printed on a selected date, or for a range of dates, enter the starting date
for the range.  
  
**End Date** If you wish to reprint all invoices which were originally printed
on a selected date, or for a range of dates, enter the ending date for the
range.  
  
**Use Print** Check this box if you wish select invoices based on the date the
invoice was originally printed. If this box is not checked, the invoices will
be selected based on the invoice date.  
  
**Starting Order** To print a range of invoice numbers, enter the starting
number here.  
  
**Ending Order** Enter the ending number if you wish to print a range of
invoices.  
  
**Last Status Message** Contains the last status message generated by the
program.  
  
**Last Status Date** The date on which the last status message was generated.  
  
**Last Status Time** The time at which the last status message was generated.  
  
  
<badge text= "Version 8.10.57" vertical="middle" />

<PageFooter />