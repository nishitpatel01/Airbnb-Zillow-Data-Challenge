## CAPITAL ONE AIRBNB ZILLOW DATA CHALLENGE
### Nishit Patel
### Feb 09, 2019

### GENERAL INSTRUCTIONS

1. There was no additional data used in analysis apart from given by Capital One. There were 2 files provided Airbnb (Revenue) data file and Zillow (Cost) data file in csv format.
2. There were no proprietary software used for this analysis. All the software used are open source and available for anyone to use.
3. I used R and R studio for this analysis. ggplot2 package was used for visualization and dplyr and data.table for data manipulations.
4. I have also attached the "c1_challenge.html" file for reference which was generated by running my code with html output.
5. "c1_challenge_files" folder contains all files to successfully render "c1_challenge.html" in any web browser. you will find "figure-html" folder inside submission folder which contains all plots and charts as images.
6. The Airbnb dataset as been given in zip file format which I have unzipped to produce the "listings.csv" file. This is the file I have used in code instead of "listings.csv.gz" so please make sure
	that you have unzipped the "listings.csv.gz" file before running the code.
7. Any information that were adopted from web or other sources including term definition, reusable code are mentioned in "Acknowledgment" section of markdown file.
8. In the instructions, it was mentioned to submit "metadata documentation" for any data that was created during analysis. Since I have used R markdown format for my analysis, all the work related
	explanations are already present in the file and therefore I have not created an additional document for it.


### Instructions to change extension back from .txt to .js

Below are the files with folder locations where you need to change extension from .txt to .js

* Folder c1_challenge_files\bootstrap-3.3.5\js\
	* bootstrap.txt
	* bootstrap.min.txt
	* npm.txt

* Folder c1_challenge_files\bootstrap\shim
	* html5shiv.min.txt
	* respond.min.txt

* Folder c1_challenge_files\highlightjs-9.12.0\
	* highlight.txt

* Folder c1_challenge_files\jquery-1.11.3\
	* jquery.min.txt

* Folder c1_challenge_files\kePrint-0.0.1
	* kePrint.txt

* Folder c1_challenge_files\navigation-1.1\
	* codefolding.txt
	* sourceembed.txt
	* tabsets.txt



### Instructions to run RMD file

1. The submitted code was created in R studio and is in R markdown(Rmd) format. Therefore user need to have R and R Studio installed on machine	in order to reproduce this work.

	* Use below url to install R and R studio
		* R: (https://www.r-project.org/)
		* R Studio: (https://www.rstudio.com/products/rstudio/download/)
	
2. Once R and R Studio are installed, you will need to install necessary packages that are used in this analysis. Though install commands are provided
	in the code, sometimes R studio throws error asking to use source url for packages which is not a good idea to provide in code.
	Below is the command to install packages for this analysis. Run below code as it is in R studio:

```r 
        install.packages("dplyr")
        install.packages("data.table")
	install.packages("ggplot2")
	install.packages("ggpubr")
	install.packages("kableExtra")
```


3. Once above packages are installed, open the "c1_challenge.Rmd" file in R studio and click on "Knit" button on top bar.
4. After knitting the markdown file, you can see the output in any browser or in Viewer pane in R Studio.
