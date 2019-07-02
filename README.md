# Introduction to the project and the data
In February 2018 the Danish news paper, Berlingske, had an article about differences in income in all the zip codes in Denmark: https://www.berlingske.dk/oekonomi/klik-paa-kortet-saa-store-er-de-personlige-formuer-i-dit-postnummer. (Unfortunately it can now only be read with a subscription). 

The article included a clickable map with median- and average income figures for every zipcode. This data was available in json-format and can be found in the file "formuedata.json". 

Furthermore I have included data about number of addresses in Denmark. This is publicly available through DAWA (Danmarks Adressers Web API). I extracted the data with the following call: dawa.aws.dk/adresser?format=csv&struktur=mini. Unfortunatly the file ended up having size of 588MB! So I loaded it into my localhostet SQL-server. However, I was not able to share the file here. By saving the specified file locally on your own computer you should be able to run the code anyway. 
