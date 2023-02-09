

# Expenses Excel sheet

## Calulates your end of month net income after taxes, expenses and bills
-----

### Formulas used in this excel:

- Sum of all Bill and Incomes.
    - =SUM(G12:G33)
    - =SUM(I4:I7)
- Tax deduction of varying percentage.
    - =(G7-(H4*G4))
- Difference from Income and True bill amount.
    - =SUM(I8-[@[True_Bill_Deduction]])
- Nested "IF" condition. Determines deduction amount from income if optional "active" or "Split" values selected.
    - =IF(D9="YES",IF(E9="YES",F9/2,F9), F9-F9)

<br>


![chart1](https://user-images.githubusercontent.com/52839097/217931305-b975393b-6bf5-4f1f-bb96-095db8abc7aa.PNG)
