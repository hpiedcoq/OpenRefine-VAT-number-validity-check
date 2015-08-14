# OpenRefine-VAT-number-validity-check

A simple recipe for OpenRefine, that allows you to perform a check of validity on the VIES platform, for european VAT numbers.

HOW-TO

Copy/paste a list of VAT numbers in OpenRefine
Create the project.

Click on Undo/Redo---> Apply
Paste the recipe
Click on perform operations

If the VAT number is French, the recipe checks first its technical validity (col "validité", Y/N) using the Luhn Algorithm.
NOTA BENE : for other countries this column is always N.
It also identify the official owner of the VAT number.






