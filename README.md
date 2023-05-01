# Government Responses and Impact on CoVID-19
## Impact of various government responses and policies on confirmed cases/fatality ratio of COVID-19

This project aimed to get a better understanding of how different governmental policies and responses shaped the COVID-19 pandemic as of 9/21/2020. We compare the following countries and label their response to the pandemic:
- Sweden: presumed relaxed
- United States: presumed moderate
- South Korea: presumed strict

To generate these labels and quantify governmental policies, we used [The Oxford COVID-19 Government Response Tracker](https://github.com/OxCGRT/covid-policy-tracker).
The policy indices are intended to be a measure of how many of the relevant indicators a government has acted upon, and to what degree with a higher score indicating a more 'strict' response. We looked at:
- Overall government response index (all indicators)
- Containment and health index
- Stringency index
- Economic support index
For a better understanding of the [index methodology](https://github.com/OxCGRT/covid-policy-tracker/blob/master/documentation/index_methodology.md), please visit [The Oxford COVID-19 Government Response Tracker](https://github.com/OxCGRT/covid-policy-tracker).

We compared these indices to the number of confirmed cases, number of confirmed deaths, and fatality ratio for each respective country. This data was retrieved from the [COVID-19 Data Repository by the Center for Systems Science and Engineering (CSSE) at Johns Hopkins University](https://github.com/CSSEGISandData/COVID-19).
Fatality ratios were calculated based on the WHO formula of total death/total confirmed.

For our initial project proposal, see: https://github.com/lindbergag/GovernmentResponsesandImpactCoVID19/blob/main/ProjectProposal.pdf

For the data cleaning, aggregation, manipulation, visualization, and analysis, see: https://github.com/lindbergag/GovernmentResponsesandImpactCoVID19/blob/main/ProjectProposal.pdf

For our full write-up, see: https://github.com/lindbergag/GovernmentResponsesandImpactCoVID19/blob/main/FInalPaperandConclusions.pdf

## Requirements
* Python 3.6+
* Pandas
* Numpy
* Sqlite3
* Seaborn
* Matplotlib
* Six
* PySpark

## Setup
1. Clone the repository.
2. Install the required packages.
3. Run the script.


## Contributing

Feel free to fork the repository and submit pull requests with any improvements or bug fixes.

## Author's notes

Any critical thinking or decision making generated from the information provided in this repo should be compared against the wealth of other information available.
