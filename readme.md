

# Budget and Expenses Excel sheet

## Calculates your end of month net income after taxes, bills and expenses.
-----

### Formulas used in this excel:

- Sum of all Bill and Incomes.
    - =SUM(G12:G33)
    - =SUM(I4:I7)
- Tax deduction of varying percentage.
    - =(G7-(H4*G4))
- Difference from Income and True bill amount.
    - =SUM(I8-[@[True_Amount]])
- Nested "IF" condition. Determines deduction amount from income if optional "active" or "Split" values selected.
    - =IF(D9="YES",IF(E9="YES",F9/2,F9), F9-F9)
<br>

! No Macros included !

----

<br>

## Blank template included in download


![chart1](https://user-images.githubusercontent.com/52839097/217944202-63363ad1-b942-4113-b246-ac7600a21fbf.PNG)


----

<br>


## Example of a completed Budget sheet

![chart2](https://user-images.githubusercontent.com/52839097/217942493-5c5d862b-b3a1-47d9-bc1f-3e03ea8ec715.PNG)

