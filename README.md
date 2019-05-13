# kohler_clio2_project

This project constitutes my final paper for Clio2 in Spring 2019 with Dr. Lincoln Mullen.

All census and election data is in the mapping_files folder, including a .pdf version I found of the 1860 election data which I originally only had in newspaper form.

The data didn't convert over cleanly, so a good deal of the resulting 1860_election_returns.csv file is custom by me. In particular, to help align the data with the census data several independent cities were merged into the surrounding county:

"Norfolk County" = Norfolk County and the independent cities of Norfolk City and Portsmouth
"Henrico County" = Henrico County and the independent city of Richmond
"James City County" = James City County and the independent city of Williamsburg
"Prince George County" = Prince George County and the independent city of Petersburg

For whatever reason Alexandria County and Alexandria City were already merge in the election data.

The resulting percentages for each of these counties is, therefore, my calculations. For all others I used the .pdf's numbers.

The various census .csvs (all downloaded using the NHGIS Data Finder) were all edited by me (earlier in the semester) to insert sane labels for columns and to provide a "full_name" column to assist with merging with the USABoundaries data. This column was also added to the electoral data file for similar reasons.