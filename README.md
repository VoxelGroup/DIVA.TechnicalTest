# DevoluIVA Technical Test

This is a project where you can show us your potential.

## Instructions

For this technical test you will need to have this in mind:

* Create a new branch on this repository with your name.
* Upload the working solution to your branch with instructions on how to run/use it.
* The implementation is up to you but the problem needs to be solved.

## The Problem

Given 3 images that you can find under the folder ``images`` generate an array of data with the information inside them. 

Next write a program that takes for input the array and extracts the relevant data from them classified.

**Extra**: Export the output as an excel sheet.

Example input:

```c#
string[] image1 = new string[]{ “1234567”, “20/01/2020”, “10.00”, “2.87” };
```

Expected output:
```json
{
  "ticket_number": "1234567", 
  "ticket_date": "20/01/2020", 
  "ticket_total": 10.00, 
  "ticket_tax": 2.87
}
```

## Hints

* If you're brave you can try to do an optical recognition of the images to extract the data into an array of strings, if not you can just write the data by hand.

* To know which data goes where you can use RegEx

* The input data might not be always ordered, it could be unordered.
