# scrapy-nivea
Scraper that collects products from Nivea main product page.

Spider uses pagnation in odred to get all 475 items.

It isn't common practice to run scrapy in notebook, but this repo uses notebook as you can see. 

Also if you encounter errors like "ReactorNotRestartable " on second run of the cell, you might need to restart Kernel.

Data needed to be extracted:

- name of product
- category
- link to the item
- rating
- number of reviews

https://www.nivea.hr/proizvodi

![image](https://github.com/user-attachments/assets/79be7203-6f5d-4493-b16d-0c87d2c03aae)
