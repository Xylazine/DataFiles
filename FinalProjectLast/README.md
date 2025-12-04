

This pipeline assumes that all required R packages will be pre-installed and that 
RStudio will have access to a copy of Python in order to create a virtual environment. 
All Python libraries will be installed within the virtual environment created within this
project folder.

To execute the full pipeline, knit **Main_File.Rmd**. This will automatically render the data 
pre-processing file, **data_prep.Rmd**. In order to knit this prep file independently, the first 
72 lines of **Main_File.Rmd** must first be executed in order to load packages, establish the
virtual environment, and create/populate the SQL database not done already. 

Required R packages:
- reticulate
- RSQLite



