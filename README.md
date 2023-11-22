# Earthquake data analysis using pyspark

### Dependencies:
- Python (https://www.python.org/downloads/)
- Spark Engine (https://spark.apache.org/downloads.html)
- winutils (https://github.com/steveloughran/winutils)
- Jupyter Notebook
- Pyspark
- MySql Database (https://www.mysql.com/downloads/)
- SQL connector (https://dev.mysql.com/downloads/connector/j/)

### Basic Checks:
- Check if jupyter is installed. If not, run "pip install jupyter" to install in your environment.
- Check if pyspark is installed. If not, run "pip install pyspark" to install in your environment.
- Check if mysql connector jar file is present at spark home address.

### High level Steps:
- Import necessary libraries
- Create connection between python and mysql
- Read the Data from the local using pandas
- Load the data from the mysql into pyspark application
- Do the analysis

