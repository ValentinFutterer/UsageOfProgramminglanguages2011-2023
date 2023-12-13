# UsageOfProgramminglanguages2011-2023

This repository was created during the Programming Language Ecosystem project from TU Wien.

It contains a python script, that was used to extract the knowledge on how the usage of programming Languages in the last 12 years shifted. It uses 3 datasets as inputs, they are stored in data. These datasets are not uniform and need a lot of personalized data extraction, therefore the script is most likely not reusable. For example, the PYPL_survey_2004-2023 is a js file.

After extracting the data, the script generates the csv file usage_of_programming_languages_2011-2023 in the results folder. This file contains a column for the year and then many columns for the different languages, denoting their usage in percent. Every language mentioned in the three datasets is going to be present in this csv file. Additionally, the script generates a vertical barchart and a piechart for each year plus a line graph for each language over the whole timespan as png's. if you need different charts, you are free to extend it.

## Usage

Run in the console with

```python
python generate_results.py
```

This generates the result csv dataset and different graphs and puts them into the results folder.

## License

[MIT](https://choosealicense.com/licenses/mit/)

Note that the MIT license is just for the code - so everything except the data and results folders. The READMEs in data denote, which licenses the datasets have. Everything that gets produced from the code (and is put into results by default) falls under the Open Data Commons Open Database License (ODbL) v1.0 https://opendatacommons.org/licenses/odbl/1-0/ license, since they are created by using the PYPL_survey dataset.