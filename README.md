# K-means-excel-project

Question: Five analysts in a marketing department, were asked to recommend extending or not extending the marketing campaign of a product into the country of their choice, basing their decision on the Gross Domestic Product (GDP), Population Growth, and Inflation Rate of each country. Finding out what is happening and recommending which country not launch the product


The excel file contains only 5 observation where I used =NORMINV(RAND(),$E$2,E$29 where mean is distributed around the original value but with a standard deviation of all values for a particular variable. The cell E29 is the stndard diviation.

Once all the observations are simulated for the three variables GDP, Population, Inflation, the data for three variables is standardized, =(E2-E$28)/E$29. Where E28 is mean of all observation and E29 is the standard diviation of all variables.

Then, import the standardized dataset to R studio and run the following code:
> ynk=kmeans(Data3R,2)
> ynk$cluster

See excel file sheet 1 and 2.

Conclusion: The method used is k-means clustering, was very sensitive to differences in magnitudes of variables and thus I had to standardize. GDP, for example, was not on the same scale as Population (growth) and Inflation. I took the data that would be entered in R and saved it separately (see second attachment). Entered this data into R and produced the k-means clustering. The results were pasted on Sheet2 of  submitted file. Then I took the output from the R command.

Initially Michael is recommending maldova but with the high inflation rate the itseems to be a good idea to lauch the product but considerating james recommendation with low inflation rate cuba will be a better option. As we take more obsetvatin and considering the kmeans clustering four out of five instance we need to avoid MOLDOVA.

