<h1 class="code-line" data-line-start=0 data-line-end=1 ><a id="Mapping_the_Correspondence_Network_of_Galileos_Last_Disciple_0"></a>Mapping the Correspondence Network of Galileo’s Last Disciple</h1>
<h2 class="code-line" data-line-start=3 data-line-end=4 ><a id="Description_of_the_project_3"></a>Description of the project:</h2>
<p class="has-line-data" data-line-start="5" data-line-end="13">In recent years, Network Analysis has become a classic method to understand the social construction of knowledge. With the increasing digitization of historical archives, it has become possible to pursue these efforts on<br>
a much larger scale. Thanks to digitization of large corpora of both passive and active correspondences, and<br>
to their interoperability, historians can now aggregate their metadata in order to understand wider tendencies:<br>
weak and strong tie, geographical and linguistic extension, differences in chronological periods etc.<br>
In this Project we examine Vincenzo Viviani’s career from a different perspective: his surviving letters. we use<br>
it as a tool to build a database then a network to visualize his correspondence. A combination of close and<br>
distant reading allows us to understand and discover elements of his life and career and shows how efficient a<br>
quantitative analysis can be and how it can improve our historical knowledge.</p>
<h2 class="code-line" data-line-start=16 data-line-end=17 ><a id="FolderFile_Organization_16"></a>Folder/File Organization:</h2>
<h3 class="code-line" data-line-start=21 data-line-end=22 ><a id="Data_Cleaning_21"></a>Data Cleaning:</h3>
<p class="has-line-data" data-line-start="22" data-line-end="23">notebook containing the code to scrap and clean the data</p>
<h3 class="code-line" data-line-start=23 data-line-end=24 ><a id="Histograms_23"></a>Histograms:</h3>
<p class="has-line-data" data-line-start="24" data-line-end="25">notebook containing the code to print many histograms that can be found on the file ‘Additional figures’</p>
<h3 class="code-line" data-line-start=25 data-line-end=26 ><a id="network_25"></a>network:</h3>
<p class="has-line-data" data-line-start="26" data-line-end="27">notebook containing the code to draw the different graphs and clusters in our graphs</p>
<h3 class="code-line" data-line-start=27 data-line-end=28 ><a id="Queries_27"></a>Queries:</h3>
<p class="has-line-data" data-line-start="28" data-line-end="29">notebook containing an access to the database to make queries</p>
<h3 class="code-line" data-line-start=29 data-line-end=30 ><a id="Additional_figures_29"></a>Additional figures:</h3>
<p class="has-line-data" data-line-start="30" data-line-end="31">contains all of the other figures not mentioned nor shown on the report. The ‘Histogrammes’ file contains many different types of histograms, ‘Images for report’ contains all the images used in the report, to have a better look at it. ‘names to correct’ is a list of uniques names that has to be corrected to avoid having duplicate names for the same person. ‘unique_names’ contains all of the unique names of the network. ‘histo top 9’ is a histogram of the top9 correspondents of Viviani. ‘total letters per year’ is a histogram of the total letters sent and received every year between 1640 and 1701.</p>
<h3 class="code-line" data-line-start=31 data-line-end=32 ><a id="CSV_files_31"></a>CSV files:</h3>
<p class="has-line-data" data-line-start="32" data-line-end="33">contains different CSV files:</p>
<h3 class="code-line" data-line-start=33 data-line-end=34 ><a id="initial_db_33"></a>initial_db:</h3>
<p class="has-line-data" data-line-start="34" data-line-end="35">is the initial database right after the scraping.</p>
<h3 class="code-line" data-line-start=35 data-line-end=36 ><a id="filtred_id_35"></a>filtred_id:</h3>
<p class="has-line-data" data-line-start="36" data-line-end="37">mixed sent and received letters by Viviani when the sender/receiver is identified</p>
<h3 class="code-line" data-line-start=37 data-line-end=38 ><a id="sent_id__37"></a>sent_id :</h3>
<p class="has-line-data" data-line-start="38" data-line-end="39">list of sent letters by Viviani to identified receivers</p>
<h3 class="code-line" data-line-start=39 data-line-end=40 ><a id="received_id_39"></a>received_id:</h3>
<p class="has-line-data" data-line-start="40" data-line-end="41">list of received letters by Viviani by identified senders</p>
<h3 class="code-line" data-line-start=41 data-line-end=42 ><a id="filtred_year_41"></a>filtred_year:</h3>
<p class="has-line-data" data-line-start="42" data-line-end="43">same as filtred_id with a new column containing the year the letter has been sent</p>
<h3 class="code-line" data-line-start=43 data-line-end=44 ><a id="sent_year_43"></a>sent_year:</h3>
<p class="has-line-data" data-line-start="44" data-line-end="45">same as sent_id with a new column containing the year the letter has been sent</p>
<h3 class="code-line" data-line-start=45 data-line-end=46 ><a id="received_year_45"></a>received_year:</h3>
<p class="has-line-data" data-line-start="46" data-line-end="47">same as received_id with a new column containing the year the letter has been sent</p>
