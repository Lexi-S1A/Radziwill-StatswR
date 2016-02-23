# Radziwill-StatswR
Data, thoughts, ideas while working through Stats with R

I'm excited to dive deeper into applied statistics and learn R at the same time! Yea!

Week2 Comments:
# R code to query just the July data from the TVS 2014 dataset:
> tvs [tvs$X.ZTIME>"201407" & tvs$X.ZTIME<"201408",]

# Alternate to obtaining mode on pg 37 (couldn't get the function to work:
> which.max(tabulate(sub.tvsj$TOP))
