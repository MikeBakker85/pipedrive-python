# pipedrive-python
Using Python to extract data from Pipedrive using its API

This code is to extract all data from CRM software Pipedrive using its API. You need to be 'administrator' to get the API which will access all your company's data, otherwise it's limited to just yours. 

The API allows to extract 500 entries max, so I created a work-around to pull up to 1000 entries.

Finally, the code merges both activities and deals to 1 Excel file
