User Manual

Step 1:

The tool can be executed by running the “kbc_trading.py” file from either a) Atom PowerShell b) Spyder (from Anaconda Suite) c) any other python environment [out of scope of this document]

Following are the commands to download the libraries: Commands in Anaconda Environment

conda install scikit-learn
conda install -c plotly plotly
conda install -c conda-forge regex
conda install -c jmcmurray os
conda install -c conda-forge fbprophet or Commands in Python Environment
pip install -U scikit-learn
pip install plotly==4.3.0
pip install regex
pip install os-win
pip install fbprophet
Step 2:

Analyst/User is now requested to either search the company symbol (if the analyst is aware, type ‘Y’ in any case) or search for the company (if the analyst is not sure, type ‘N’ in any case) by typing a part of the company name. The later, finds a list of all the company names matching the entered text. If user wants to exit from searching company symbol, type ‘E’.

Step 3:

On refining the company search symbol, system asks the user to confirm the company symbol, so that other analytical tools can be made available. The chosen company symbol will be validated, if all holds good tool goes to the next step otherwise, tool continues to ask user to finalize the symbol. (User Inputs are case insensitive, although user needs to follow specific date format of YYYY-MM-DD).

Step 4:

Following is the available list of activities that a user can do with finalized company symbol. The user needs to select one of the numbers from 1-12 and hit enter. After selecting the option, the system will come back to the same menu, so that users can visualize other aspects of data for the company or select another company symbol or exit the program altogether.

Step 5:

For most of the options selected by the user, there will be timeframe asked from the user. Start date and end date are dependent on the analyst, how much data needs to be analyzed. User needs to provide these dates as and when asked by the system. There are few other analyses which require specific inputs: - Window (in case of moving averages) & Particular date (prediction on that day). Inputs for Date range: Start Date and End Dates are inputs for option 2 through 9. If user wants to start the analysis with new date range, he/she can select option 10.

Step 6:

The tool also allows the user to compare closing data of the two companies so that the analyst can advise which company is better for investment. The Graph would show data of both companies on a common timescale.

Step 7:

User can select another company symbol without exiting the program and continue slicing and dicing just like from step 2 – step 5. To perform this functionality, user can select option 11 for analyzing new company.

USP's of the Product: -

1.More personalized approach to design, to match NY time, system automatically handling time zone changes, used UTC time.
2.Personalized Welcome Message on the landing page.
3.For Database, we use CSVs, same file is reused, instead of hitting the network again and again since these data is stored in csv files, data can be shared with platforms easily. In cases of file of company being lost, up-to date data can be fetched almost immediately by the system automatically.
4.Search function of a company, pattern search using regular expression.
5.Case in-sensitive search everywhere
6.Flexible user menu designed with minimalistic approach; repetitive questions avoided
7.Highly interactive graphs, users can download and check data at low & High granular level data, giving a better user experience
8.Elements of artificial intelligence introduced in prediction, with concepts of hyper parameter tuning.
