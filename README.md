1. To succesfully run the notebook, one needs an extra file called cities.csv, which was to large to upload to github.

2. The link to this file can be found here https://public.opendatasoft.com/explore/dataset/geonames-all-cities-with-a-population-1000/export/?disjunctive.cou_name_en&sort=name
where city and population data should be exported and imported into the project as a csv.

3. The Notebook uses this file to gather and store information concerning what cities it should gather information from. We then train the model on the grids that were created
and lastly analyze the grids with the corresponding data.

4. The oecd_cities contains the GDP of cities. When no data for a city is existent, we extract the data from another api source mentioned in the notebook.

5. Without a sufficient GPU the CPU of the system is automatically used for training the Autoencoder, please note that training make take a few days in my case a week. Secondly at the end i had around 360 GB of data usage for the complete project, therefore bear that also in mind.
