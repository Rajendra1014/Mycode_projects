REQUIRED SKILLS:

    Python scripting
    MongoDB
    Streamlit
    Snscrape

OVERVIEW:

I have Created a GUI using streamlit that contains the follwing features

    Can enter any keyword or Hashtag to be searched,
    select the starting date
    select the ending date
    Number of tweets needs to be scrapped.

After scraping is done, it has the following options

    Download data as CSV
    Download data as JSON
    Display All the Tweets scraped
    Upload data to DATABASE

WORKING:

Step1: Initially I collected the Keyword, Start date, End date, and Number of tweets from the user using streamlit

Step 2: The above details are fed to TwitterSearchScraper and TwitterHashtagScraper. A dataframe is created to store the entire scraped data Now we can download this scraped data in the form of CSV or JSON format

Step3: The database connection is established using pymongo A new collection will be created and data is uploaded into that collection if the user wish to upload
