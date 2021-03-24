# DataSamples

## Links to actual deliverables

## Notes

### Data Used
The data for this projeect was retrieved from:
- acquisition data: https://www.kaggle.com/shivamb/company-acquisitions-7-top-companies (edited sheet available: -- link to google sheet -- )
- price data: -- make this a link to the google sheet --, price data retrieved using the `googlefinance` function: https://support.google.com/docs/answer/3093281?hl=e

Acqusition data was edited in Google Sheets, including the following changes: 
- Acquisitions were filtered to include those after January 1, 2010, for Facebook and Google/Alphabet only
- A date value field was added to combine Month, Day and Year to make consistent with the price data format
- If a date did not include a day of the month, it was updated to be the first of the month, if a month was not included the acquistion was not included in the analysis. 

 
### Tools Used
https://jupyter.org
https://colab.research.google.com/notebooks/intro.ipynb
https://pandas.pydata.org
https://numpy.org
https://matplotlib.org
