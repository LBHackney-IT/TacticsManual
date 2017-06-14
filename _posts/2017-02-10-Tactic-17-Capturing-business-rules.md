Our services are conditioned by the business and legislative rules that determine how we can design something. The ‘gherkin syntax’ provides a common way of capturing these in a simple format. 

The structure of a Gherkin syntax is:
<ul><li>Feature</li>
<li>Scenario</li>
<li>Given, When, Then, And, But (Steps)</li>
<li>Background</li>
<li>Scenario outline</li>
<li>Examples</li></ul>

This is an example from a cash machine
<ul><li>Feature: Account Holder withdraws cash</li>
<li>Scenario: Account has sufficient funds</li>
<li>Given the account balance is £100</li>
<li>And the card is valid</li>
<li>And the machine contains enough money  </li>
<li>When the Account Holder requests £20</li>
<li>Then the ATM should dispense £20</li>
<li>And the account balance should be £80</li>
<li>And the card should be returned</li></ul>
