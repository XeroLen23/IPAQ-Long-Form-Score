# IPAQ-Long-Form-Score
Allows you to assign a discrete score to the long version of the International Physical Activity Questionnaire (IPAQ). Three possible values of physical activity: Low, Moderate, High.

Notebook "1 - Scoring_IPAQ_LongForm - CSV_Output.ipynb" takes as input a file like the attached "input - IPAQ_spreadsheet.csv" example. All information must be given in minutes, so be sure to convert all responses.
By running "1 - Scoring_IPAQ_LongForm - CSV_Output.ipynb" will generate a new .csv file with the physical activity level obtained from the response provided. The file "output - subjects_categories.csv" shows an example of a possible output.

Notebook "2 - Check_Data_Distribution.ipynb" creates three lists, one for each possible level of physical activity (Low, Moderate, High). It allows to check how many subjects we have for each of the three possible categories. 
