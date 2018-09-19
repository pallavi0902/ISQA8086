
** Following are the errors that I found in the 3 data files:

1. In all three data files, there is no time column. According to me, it should be there as it was mentioned that samples were taken at noon as well as night. Also, should specify timezone.
2. Given data files has 'Temperature' column but it isn't specifying which temperature scale they used. I am used to Celsius whereas some are used to Fahrenheit and then there is kelvin, which is the unit of temperature in the International System of Units ( SI ). So, to avoid confusion, they should mention which scale they have used.
3. Data represented in data file are not in a neat manner. Datas are in excel so that we can have our data in an organized way which will make working with huge data a lot easier. (not really an error but this could lead to errors).
4. One data file shows 'Max depth = 72m'. However, there was no data showing 72 in any depth column. There is no explanation how they derived that depth of 72.
5. There is one highlighed data in 'zoop-temp' file which made little to no sense to me. A particular data should be significant enough to draw some more insightful information. The highlighted data has no such characterstic.
6. Given line diagram in 'zoop-temp' file has no specified x and y axis. From a line diagram one can infer critical facts and figures just by observing it carefully, given that the line diagram has all the required things. 
7. Dataset is missing some values and looks like incomplete in nature.
8. Data mentioned as 7th and 9th in 'zoop-temp' isn't explaning much which question its relevance. 
9. Column name are changed or different in all three data files.
10. I was trying to figure out _#/L_ in Cuni and Chippo. It would have been better if they could have explained it. 

** Following are the suggestions for the new system:

1. First, I would say having data in a neat manner will solve a lot of problems because in order to beautify your dataset, you have to take steps like making column name bolder, filling missing coloumns as 'N/A', having a graph with both axis, etc.
2. There are different people working on datasets, seeing and doing things differently. Like I mentioned about the temperature, not everyone will be taking that temperature as Fahrenheit, you never know. So, to make consensus, defining temperature scale in bracket in the coloumn name would be great. 
3. A time coloumn is important as they themself have mentioned about taking sample during two ** times ** of the day.
4. Column names should be same in all three or as many as data files are there. Column names are the base to understand the whole data like imagine a dataset with no column name. Surreal, right? It just figures then, you cannot infer anything. So, give the importance that column name deserves. Name it properly, keep same name in all.
5. A highlighted data is really important. One should not mistake highlighting data as taking notes. In dataset, if you're highlighting a particular data, it is mostly because that data has a lot insightful information to offer. I would suggest not to highligh data until it you feel that this particular data has a lot of significant information. 


| Date 	| Time(Timezone) 	| Cuni 	| Chippo 	| Colony Size(Diameter) 	| Depth(Unit) 	| Temperature(Unit) 	| Chlorophylla 	|
|------	|:---------------	|:-----	|:-------	|:----------------------	|:------------	|:------------------	|:-------------	|

