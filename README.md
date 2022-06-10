<h1 class="code-line" data-line-start=0 data-line-end=1 ><a id="Mapping_the_Correspondence_Network_of_Galileos_Last_Disciple_0"></a>Mapping the Correspondence Network of Galileo’s Last Disciple</h1>
<p class="has-line-data" data-line-start="2" data-line-end="15">Data Cleaning: notebook containing the code to scrap and clean the data<br>
Histograms: notebook containing the code to print many histograms that can be found on the file ‘Additional figures’<br>
network: notebook containing the code to draw the different graphs and clusters in our graphs<br>
Queries: notebook containing an access to the database to make queries<br>
Additional figures: contains all of the other figures not mentioned nor shown on the report. The ‘Histogrammes’ file contains many different types of histograms, ‘Images for report’ contains all the images used in the report, to have a better look at it. ‘names to correct’ is a list of uniques names that has to be corrected to avoid having duplicate names for the same person. ‘unique_names’ contains all of the unique names of the network. ‘histo top 9’ is a histogram of the top9 correspondents of Viviani. ‘total letters per year’ is a histogram of the total letters sent and received every year between 1640 and 1701.<br>
CSV files: contains different CSV files:<br>
initial_db: is the initial database right after the scraping.<br>
filtred_id: mixed sent and received letters by Viviani when the sender/receiver is identified<br>
sent_id : list of sent letters by Viviani to identified receivers<br>
received_id: list of received letters by Viviani by identified senders<br>
filtred_year: same as filtred_id with a new column containing the year the letter has been sent<br>
sent_year: same as sent_id with a new column containing the year the letter has been sent<br>
received_year: same as received_id with a new column containing the year the letter has been sent</p>
