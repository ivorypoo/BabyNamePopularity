# BabyNamePopularity

This is a Homework problem that I did for my Machine Learning Class.

The original dataset comes in 50 different files, that each of them represents a different state in the United State. 
Each record in a file has the format: 2-digit state code, sex (M = male or F = female), 4-digit year of birth (starting with 1910), the 2-15 character name, and the number of occurrences of the name. Fields are delimited with a comma. Each file is sorted first on sex, then year of birth, and then on number of occurrences in descending order. When there is a tie on the number of occurrences names are listed in alphabetical order. This sorting makes it easy to determine a name's rank. The first record for each sex & year of birth has rank 1, the second record has rank 2, and so forth.

To safeguard privacy, the information has been restricted to the list of names to those with at least 5 occurrences. If a name has less than 5 occurrences for a year of birth in any state, the sum of the state counts for that year will be less than the national count.

In the rmd file, I answered 10 different questions by manipulating the data in different way using R.
