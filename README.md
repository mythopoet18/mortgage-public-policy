## The Question
Does public policy affect homeowner's mortgage payment decision?<br>

We exam the following termination events and look for patterns related to the loan's geographical origin.
<ul type="disc">
	<li>borrower foreclose within a year/after a year</li>
	<li>borrower make prepayment to exit the mortgage within a year/within one to five years/beyond five years</li>
	<li>short sale </li>
	<li>loan modification</li>
</ul>
  
Borrower' payment decision involves both long-term and short-term consideration. 
<ul type="disc">
	<li>Long-term: permanent income hypothesis tells us that the monthly payment schedule should match the expected income stream. If the macroeconomic policies are different among states, borrowers would choose different house and financial plan. </li>
	<li></li>
	<li></li>
</ul>

## Data

[Construct dataset](https://placehold.it/15/c5f015/000000?text=+)<br>
<ul type="disc">
	<li>Single Family mortgage and payment information from Freddie Mac</li>
	<li>Single Family mortgage and payment information from Fannie Mae</li>
	<li>FHsecurityFA loan information</li>
	<li>Fundamentals: https://united-states.reaproject.org/data-tables/selected-indicators/</li>
</ul>
 
[Basic Features](https://placehold.it/15/c5f015/000000?text=+)<br>
<ul type="disc">
	<li>Single Family mortgage and payment information from 1999 to 2018</li>
	<li>  open cases and closed cases</li>
	<li></li>
	<li></li>
</ul>

[Policy of interest](https://placehold.it/15/c5f015/000000?text=+)<br>
<ul type="disc">
	<li>Tax:Payroll Tax;State Tax;Corporate Tax. </li>
	<li>Labor Market: Unemployment subsidy. </li>
	<li>Childcare: Tax reduction and subsidy. link (http://www.taxcreditsforworkersandfamilies.org/state-tax-credits/
) </li>
	<li>Education: School scores; state funding scholarship. </li>
	<li>Housing: Recourse/Non-reccourse statue; loan modification.</li>
	<li>Healthcare: Medicare and Medicaid. </li>
	<li>Other social security: SCHIP; OASDI; TANF;SSI</li>
</ul>

## Method
We are facing two major challenges.
<ul type="disc">
	<li> Survival bias: we adopt cox survival model with loan origin time as fixed effect. </li>
	<li> Large-scale data: we adopt map reducing method. </li>
</ul>
## Preliminary results
<ul type="disc">
  <li>The states adopted expanded Medicaid had lower foreclosure probability, similar prepayment probability.</li>
  <li>Tax, labor Market, childcare and education policies are highly correlated with housing price. They are not significant in determing payment events.</li>
  <li>Housing policy is significant on both default risk and prepayment risk.</li>
  </ul>
  
## Project Site Link
https://mythopoet18.github.io/mortgage-public-policy/ <br>

