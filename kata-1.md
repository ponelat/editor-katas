HTML list from text
-------------------

Taken/Inspired from: [http://code.joejag.com/2016/text-editing-kata.html]()

Convert this list of strings into the expected html

Example:
```text
Dealer Options
```

Becomes...
```html
<dt runat="server" id="dtDealerOptions"> Dealer Options </dt>
<dd runat="server" id="ddDealerOptions"> </dd>
```

### The list
```text
Basic Price
Discount
Sub total
Factory options
Dealer options
Fuel and mats
Road fund licence 
Number plates and delivery
Registration fees 
Sub total
Service plan
Autocare
Protect
VRI
Our Insurance
Sub total 
Customer contribution
Part exchange value
Cash back
Settlement
Sub total
Credit card handling charge
Vat
Total to pay
```

### The expected result
```html
<dt runat="server" id="dtBasicPrice">Basic Price</dt>
<dd runat="server" id="ddBasicPrice"></dd>

<dt runat="server" id="dtDiscount">Discount</dt>
<dd runat="server" id="ddDiscount"></dd>

<dt runat="server" id="dtSubTotal">Sub total</dt>
<dd runat="server" id="ddSubTotal"></dd>

<dt runat="server" id="dtFactoryOptions">Factory options</dt>
<dd runat="server" id="ddFactoryOptions"></dd>

<dt runat="server" id="dtDealerOptions">Dealer options</dt>
<dd runat="server" id="ddDealerOptions"></dd>

<dt runat="server" id="dtFuelAndMats">Fuel and mats</dt>
<dd runat="server" id="ddFuelAndMats"></dd>

<dt runat="server" id="dtRoadFundLicence">Road fund licence</dt>
<dd runat="server" id="ddRoadFundLicence"></dd>

<dt runat="server" id="dtNumberPlatesAndDelivery">Number plates and delivery</dt>
<dd runat="server" id="ddNumberPlatesAndDelivery"></dd>

<dt runat="server" id="dtRegistrationFees">Registration fees</dt>
<dd runat="server" id="ddRegistrationFees"></dd>

<dt runat="server" id="dtSubTotal">Sub total</dt>
<dd runat="server" id="ddSubTotal"></dd>

<dt runat="server" id="dtServicePlan">Service plan</dt>
<dd runat="server" id="ddServicePlan"></dd>

<dt runat="server" id="dtAutocare">Autocare</dt>
<dd runat="server" id="ddAutocare"></dd>

<dt runat="server" id="dtProtect">Protect</dt>
<dd runat="server" id="ddProtect"></dd>

<dt runat="server" id="dtVri">VRI</dt>
<dd runat="server" id="ddVri"></dd>

<dt runat="server" id="dtOurInsurance">Our Insurance</dt>
<dd runat="server" id="ddOurInsurance"></dd>

<dt runat="server" id="dtSubTotal">Sub total</dt>
<dd runat="server" id="ddSubTotal"></dd>

<dt runat="server" id="dtCustomerContribution">Customer contribution</dt>
<dd runat="server" id="ddCustomerContribution"></dd>

<dt runat="server" id="dtPartExchangeValue">Part exchange value</dt>
<dd runat="server" id="ddPartExchangeValue"></dd>

<dt runat="server" id="dtCashBack">Cash back</dt>
<dd runat="server" id="ddCashBack"></dd>

<dt runat="server" id="dtSettlement">Settlement</dt>
<dd runat="server" id="ddSettlement"></dd>

<dt runat="server" id="dtSubTotal">Sub total</dt>
<dd runat="server" id="ddSubTotal"></dd>

<dt runat="server" id="dtCreditCardHandlingCharge">Credit card handling charge</dt>
<dd runat="server" id="ddCreditCardHandlingCharge"></dd>

<dt runat="server" id="dtVat">Vat</dt>
<dd runat="server" id="ddVat"></dd>

<dt runat="server" id="dtTotalToPay">Total to pay</dt>
<dd runat="server" id="ddTotalToPay"></dd>
```
