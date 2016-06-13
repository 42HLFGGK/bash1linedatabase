#some of the systems I use for Networking I do not have access to any database like sql, but i have a basic bash profile.
#I have to regularly access around 100 commands or cisco configs.
#I call this figer and it will search a text file called configs.txt; you fill this one text file with any information you want.  
#phone numbers; running configs..etc.
#The trick with this is to have enough blank lines before and after. In my use case I have cisco configs with 22 lines. 
#I make sure to have blank lines after each config/command sequence and 14 above. 
#the sed command removes any blank lines... My configs.txt is over 2000 lines..
