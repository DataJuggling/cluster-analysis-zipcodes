# Introduction to the project and the data
In February 2018 the Danish news paper, Berlingske, had an article about differences in income in all the zip codes in Denmark: https://www.berlingske.dk/oekonomi/klik-paa-kortet-saa-store-er-de-personlige-formuer-i-dit-postnummer. (Unfortunately it can now only be read with a subscription). 

The article included a clickable map with median- and average income figures for every zipcode. This data was available in json-format and can be found in the file "formuedata.json". 

As a little exercise I thought it would be fun to make a cluster analysis in R, showing which zipcodes are similar based on various demographic data. Even though Denmark is a very small country there are major differences between people living in our capital, Copenhagen, and people living in the most-western part of Jutland. However, maybe we have more in common than meets the eye :-)

Later in the project I include data about number of addresses in Denmark. This is publicly available through DAWA (Danmarks Adressers Web API). I extracted the data with the following call: https://dawa.aws.dk/adresser?format=csv&struktur=mini. Unfortunatly the file ended up having a size of 588MB! So I loaded it into my locally hostet SQL-server. However, you should be able to run the code by saving the specified csv-file locally on your own computer. 
