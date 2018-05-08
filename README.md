# IMDb-Movie-Analysis

I put the processed data files in the Data folder. I will keep uploading new data files and write about the updates at the end of this file. You are welcome to share your processed data and write about them in the Update section.

To make our project relevant, we follow 2 principals:

	1. only include movies that were produced between 1997 and 2017.
	2. only include people who is still alive and below 79 years old.

Our starting point is the **97to17.basics.jmp** file. You can join it with other datasets by the 'tconst' column.

Please write about your models in the **models.docx** file. Please check it to find out what you should write in it.

You can use any technique for your analysis. Please upload the relevant files.

### Original files you may download from https://www.imdb.com/interfaces/

    1. title.akas.tsv.gz
    2. title.principals.tsv.gz
	3. title.basics.tsv.gz (processed)
	4. title.crew.tsv.gz (processed)
	5. name.basics.tsv.gz (processed)

  * Please don't use other files. We need consistency in our project.

### List of files in this repository

    1. models.docx
      Please write about your models in it.
    2. Data\97to17.basics.jmp
      Our starting point. You can join it with other datasets by the 'tconst' column.
      It contains all useful records from "title.basics.tsv.gz" and "title.ratings.tsv.gz".
    3. wrangling.txt
      Commands and codes I used to process the original data files. It may be helpful when you want to process files.
      I used Windows PowerShell commands and R codes.
	4. tts.txt
	  The regular expression for extracting movie records from datasets. I used it to reduce "title.crew.tsv.gz".
	5. Data\names.zip
	  A processed "name.basics.tsv.gz" file. It contains people who is supposed to be alive and below 79 years old.
	  People whose birth year is unknown were also excluded. Let me know if you think we missed important people.
    6. Data\crew.zip
	  A processed "title.crew.tsv.gz" file. It contains the directors and writers of each movie.
	
    * Data\archives\
	  You may use the files in this folder if you want to include earlier and later movies in your analysis.
    
      1. Data\archives\tt.basics.zip
		All the movie records from the "title.basics.tsv.gz" file.
      2. Data\archives\title.ratings.tsv.gz
		Don't download this file from IMDb. Download it from this repository if you need it.
		IMDb is supposed to renew this file daily but we need consistency in our project.
      
## Update Log
* 4/12/2018 start of the project
* 4/13/2018 uploaded Data\names.zip; updated wrangling.txt
* 4/15/2018 uploaded tts.txt and Data\crew.zip; updated wrangling.txt
