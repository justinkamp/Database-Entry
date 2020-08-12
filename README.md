# Database Entry
The purpose for this project is to allow our company "X" to easily and efficiently add data to their database for easy and convenient querying. 

The first thing to do before running the app is make sure the the dataset you want to use is first a .CSV filetype and is placed withing the documents folder of your computer. Next once the code is run simply type out the name of you dataset (without the file type i.e. dataset.csv would be written as dataset).
From there the program will sort the profiles and place them in their respective locations once finished it will create two files you can access the first is a base .log which will have information on how many records were passed and how many of those were rejected based on incomplete fields.
Then it will create a InvalidRecords_bad.csv which will holds all of the rejected records.

I approached this project by first deciding to sort the records as I wrote them hoping to optimize some of the time involved. The naming convention was set so that anyone should be able to figure what a program/variable/file does beofre even opening it. Finally, I opted for spliting the program into various classes to aid in organization and readability. The only assumptions I made were that the client would want to run multiple datasets (of varying names) so a preloaded dataset didn't make too much sense. Lastly, I opted to have the two files created made within the documents folder for easier accessibility.  
