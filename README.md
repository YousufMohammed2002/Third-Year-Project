# Psychological Impacts of the COVID-19 Pandemic
## Yousuf Mohammed - Supervised by Dr Martine Barons
### Completed 2nd May 2023

This repository contains the report and code which I complted for my third year project at the University of Warwick as a MSci Data Science Student.

The code is in the form RMarkdown files (.Rmd and knitted .pdfs) and Netica files (Bayesian Network).

The code and report are free to download and view. 

## File Explainations and how to run the code: 

This submission folder contains the following documents: 

camhData.Rmd - The RMarkdown file which includes all the code and analysis completed to analyse the second data set (CAMH Data). R and RStudio are required to open this, and to run
all the code yourself, some packages are required which are shown in the first chunk of code (library()). The raw .csv file of the data set is also required in the directory to load the data set into the r environment (survey1_encoded.xls). 

camhData.pdf - the pdf version of the RMarkdown file which can be viewed with any pdf viewer (the knitted version of the .Rmd file the pdf is a direct copy). This also incldues all the code and figures and does not need R to be
viewed. Code can not be run but the code itself and outputs can be viewed. 

survey1_encoded.xls - This is the raw excel file for the CAMH data set that was analysed in the two documents above. 

survey2_results.xls - This is the raw excel file for the second camh survey which was used only for testing in the Bayes net after it was cleaned

StudentData.Rmd -  The RMarkdown file which includes all the code and analysis completed to analyse the first data set (Student Mental Health Data). R and RStudio are required to open this, and to run
all the code yourself some packages are required which are shown in the first chunk of code (library()). The raw .csv file of the data set is also required in the directory to run the code as well (Student Mental Health.xls). 

StudentData.pdf - the pdf version of the RMarkdown file which can be viewed with any pdf viewer (the knitted version of the .Rmd file the pdf is a direct copy). This also incldues all the code and figures and does not need R to be
viewed. Code can not be run but the code itself and outputs can be viewed. 

Student Mental Health.xls - This is the raw excel file for the Student Mental Health Data set that was analysed in the two documents above. 

CS350Report.BibTex - BibTex file with refernces used in the StudentData.Rmd file to incldue references in the Rmd file.

There is also a Bayesian Network file which contains the data used in creating the Bayesian Network: 

CAMHDataBayesNet - The actual Bayes net that has been created, which can be opened and run on the Netica software.

CAMHTestData(Survey2).xls - The second CAMH survey which was used as testing data for the Bayes net (taken from survey2_results.xls).

CAMHTrainingData(Survey1).xls - The original CAMH data set which was analysed which was used to train the Bayes net (survey1_encoded.xls).

There data in these files are different to the raw CAMH data set file as the data has been cleaned, renamed and only the required variables have been included 

If you just want to run the source code: the best way is the open the RMarkdown files, setting the working directory to this submission folder, installing any required packages 
through the R Console using install.packages() and running all the code chunks. 

If you just want to inpsect the code: you can open up the RMarkdown files and scroll through it to inspect the code or view the pdf document. 

The pdf documents are there as a nice summary of the RMarkdwn files and there in case of any problems accessing the Rmarkdown files. The pdf documents have all the code
and all the outputs, hence technically you do not even need to use the RMarkdown files. No software requirements are needed for the pdf documents either.

### Abstract 

Background: The COVID-19 pandemic had a significant impact on the lives of almost everyone across the
globe, due to lockdowns and isolation. People have had to adapt to new lifestyle changes affecting people not
just physically but psychologically as well. This report intends to understand whether the COVID-19 pandemic
negatively impacted UK university students’ mental health and which groups of people were affected to a lesser
or greater extent regarding their mental well-being during the COVID-19 pandemic.
Methods: Data sets were cleaned and visualised in R and RStudio. Modelling was done using linear regression
models using p-value hypothesis testing at a 5% significance level. For one data set a Bayesian network was
created and tested.

Results: For UK University students, mental health was worse in 2020 compared to 2018 and 2019 (p-values
of 0.0123 and 0.0047 respectively), but this is no different to scores in 2017 (p-value of 0.593). In Australia,
those aged 18-39 had the worst mental health out of all age groups, women had worse mental health compared
to men, and those whose working hours changed a lot also had worse mental health compared to those who
had no change in working hours.


### Key Words

COVID-19; Mental Health; Psychology; Bayesian Networks; Sensitivity Analysis; Data Analysis

### Acknowledgements

I would first like to say thank you to my supervisor, Dr Martine Barons for her professional support and
guidance during this project, even when supporting me remotely during Term 1. The feedback she has
provided to me has been very beneficial towards this project from start to finish. I would also like to thank my
family and friends for their countless support over the year, listening to me when asking for guidance and
willingly offering their opinion and feedback.
