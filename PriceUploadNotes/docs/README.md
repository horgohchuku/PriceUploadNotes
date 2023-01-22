# Welcome to the NeoLife Price Setup Notes 🛠️  <!-- {docsify-ignore} -->

Before proceeding with the setup ensure you have the .csv file ready. 

Your file should have the following information below (Do not include the headers), Note you should only use the inclusive price


| Item Code | DP   | SRP  | PV | BV | MP   |
|:---------:|:----:|:----:|:---:|:---:|:----:|
| 2130      | 1000 | 1200 | 10 | 50 | 1100 |
| 2130C     | 1000 | 1200 | 10 | 50 | 1100 |

You can find a sample of the document <em><a href='priceupload.csv' download>Here</a></em>


## Batch Number
Assign a batch number for the file you are uploading, The batch number should be a unique numeric value with at least 8 characters. 

You can write this number down somewhere as you will need it later on after uploading the prices.

## Currency
Select the country (currency) you wish to update. 

## Vat Percentage and Shipping Vat Percentage 
Input the value for Vat in the country (currency) selected above e.g 4.5.


 <b> Note </b> Should there be a new VAT in the country (currency) being updated, you will need to first update the VAT in the Exigo Admin Console (Sandbox) before proceeding to the next step.

 You should only update the VAT in Exigo Admin Console (Production) when you are ready to go live with the new VAT. 

 [Information for Admin]*CustomServicesContext.VATPercentages*
 
 <br>

Choose the file from your local machine and proceed to click the *Upload* button. After Upload, wait for atleast 5mins (depending on the quantity of items uploaded) then visit [Sandbox Intranet](https://neolifeintranetuat.azurewebsites.net).

> After Uploading and testing that the uploaded prices are correct send an email to [IT](mailto:abioduns@ng.neolife.com?Subject=New%20Price%20Update%20Batch%20Number) with the Batch Number you assigned in the beginning of this process.

> Should there be an issue at any point during the uploading process, send an email to [IT](mailto:abioduns@ng.neolife.com;adenreleja@ng.neolife.com?Subject=Issue%20Using%20Price%20Upload%20Portal).


Thank you 💚