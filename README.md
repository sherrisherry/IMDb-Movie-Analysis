# IMDb-Movie-Analysis

I put the processed data files in the Data folder. I will keep uploading new data files and write about the updates at the end of this file. You are also welcome to share your processed data and write about them in the Update section.

To make our project relevant, we only use movies that were produced between 1997 and 2017.

Our starting point is the **97to17.basics.jmp** file. You can join it with other datasets by the 'tconst' column.

Please write about your models in the **models.docx** file. Please check it to find out what you should write in it.

You can use any technique for your analysis. Please upload the relevant files.

### Files you may download from https://www.imdb.com/interfaces/

    1. title.akas.tsv.gz
    2. title.crew.tsv.gz
    3. title.principals.tsv.gz
    4. name.basics.tsv.gz

  * Please don't use other files. We need consistency in our project.

### List of files in this repository

    1. models.docx
      Please write about your models in it
    2. Data\97to17.basics.jmp
      Our starting point. You can join it with other datasets by the 'tconst' column.
      It contains all useful records from "title.basics.tsv.gz" and "title.ratings.tsv.gz".
    3. wrangling.txt
      Commands and codes I used to process the original data files. It may be helpful when you want to process files.
      I used Windows PowerShell commands and R codes.
    
    * You may use the following files if you want to include earlier and later movies in your analysis.
    
    4. Data\basics.zip
      All the movie records from the "title.basics.tsv.gz" file.
    5. Data\title.ratings.tsv.gz
      Don't download this file from IMDb. Download it from this repository if you need it.
      IMDb is supposed to renew this file daily but we need consistency in our project.
      
## Update Log
* 4/12/2018 Start of the project
