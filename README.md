# Mapping the Correspondence Network of Galileo’s Last Disciple

Data Cleaning: notebook containing the code to scrap and clean the data\\
Histograms: notebook containing the code to print many histograms that can be found on the file 'Additional figures'\\
network: notebook containing the code to draw the different graphs and clusters in our graphs\\
Queries: notebook containing an access to the database to make queries \\
Additional figures: contains all of the other figures not mentioned nor shown on the report. The 'Histogrammes' file contains many different types of histograms, 'Images for report' contains all the images used in the report, to have a better look at it. 'names to correct' is a list of uniques names that has to be corrected to avoid having duplicate names for the same person. 'unique_names' contains all of the unique names of the network. 'histo top 9' is a histogram of the top9 correspondents of Viviani. 'total letters per year' is a histogram of the total letters sent and received every year between 1640 and 1701.\\
CSV files: contains different CSV files:\\
initial_db: is the initial database right after the scraping.\\
filtred_id: mixed sent and received letters by Viviani when the sender/receiver is identified\\
sent_id : list of sent letters by Viviani to identified receivers\\
received_id: list of received letters by Viviani by identified senders\\
filtred_year: same as filtred_id with a new column containing the year the letter has been sent\\
sent_year: same as sent_id with a new column containing the year the letter has been sent\\
received_year: same as received_id with a new column containing the year the letter has been sent\\
