Brief Discription:

The Idea of my program is to read in each line, run it through a hash function and insert into a hash table of pairs, the first
element will contain a boolean to tell if something is in the data space, and the second element is a pointer to where the actual 
data is stored, which is in an array that will contain the entire data set in the end. Then I will also store a pointer for that
element in each of a seperate linked list, where each node in this list will contain a pair, which is a string that contains the
"key" that the second element, which a linked list of pointers is sorted by. This would make each search by category a search that
is A x B where A is the number of seperate categories and B is the number of elements in that category, unfortunatly there are just
too many categories for this to do what I wanted it to do so it is not effiecent. the way to make this better is to clean up the 
CSV file to actually be sorted, rather then out of order, and to create main categories, such as outdoor containing outdoor,
skateboarding, and "skates, skatebording and scooter" categories. However since I don't know of a way to automatically fix this
and did not have the time to manually write a new CSV file I have this.

Edit to CSV: removed the first two columns that had no data for any entry, this is to clean the data and make it smoother, 
			 Data header is as follows, uniqueID, name of Product, categories, price, other