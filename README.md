# Currency Converter

This project is a currency converter that can convert three currencies to each other (USD)(KWD)(SAR). The idea is very simple I used switch to make the program more readable and easy to understand.You can also add any currency.

## Methodology 
Most of the work is done in function named (convertButtonActionPerformed). This function work when the button is clicked, we extrect the selected (from) and (to) currencies then the (from) currencey goes to a switch cases ( USD or KWD or SAR) each case calls its converter function which have the selected coefficients to make the conversion. If you want to add another currency, just add two things:
<ol>
  <li>add the new currency in the switch cases in function named(convertButtonActionPerformed). (</li>
  <li>add a converter function for the new currency then call it in its corresponding case.</li>
  
</ol>





