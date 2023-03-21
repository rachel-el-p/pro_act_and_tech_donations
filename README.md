# [Lawmakers that supported labor reforms got campaign money from anti-union tech giants: FEC data](https://medium.com/@rachelphua_el/lawmakers-that-supported-labor-reforms-got-campaign-money-from-anti-union-tech-giants-fec-data-14f74f957872)

These are my data analysis files for a story I did that matched names of lawmakers that signed the PRO Act in the 117th Congress — the congress before the new term started this year — and records that showed congressional candidates that got money from Amazon and Google PACs for the 2022 midterms. 

I downloaded Amazon and Google PACs' campaign finance data from the FEC website, as well as the names of senators and representatives that signed the PRO Act from [the congress website](https://www.congress.gov/bill/117th-congress/senate-bill/420/cosponsors). 

Then I used pandas to clean the data and match the names of lawmakers so that I would get the names of lawmakers that signed the PRO Act and got money from Amazon and Google. 

I tried using fuzzy pandas to match the names — I attached a notebook — but it wasn't a good match so I went back to cleaning the data. 

Since there were still some names missing, I then manually checked it against OpenSecrets' list of candidates that got money from Amazon and Google, added the missing lawmakers, and summed up the amounts they got. 

The story webpage is here: https://medium.com/@rachelphua_el/lawmakers-that-supported-labor-reforms-got-campaign-money-from-anti-union-tech-giants-fec-data-14f74f957872

## Skills learned: 
I used pandas and learned fuzzy matching. 
