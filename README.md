# smythbot
A bot used to auto-checkout on smyths plus provides direct restock notifications via a webhook using discord.

This allows the user to manually checkout as well as using the program to checkout. 

First it creates a chrome session using webdriver and signs the person into their smyths account. This is to speed up the checkout process by using saved information.

It uses a series of .txt files to call data for the user checkout. This is all done by using selenium to automate the process. 
The discord webhook is used using a discord webhook module to give custom information on specific restocks.

The addition of info. is entered by sending keys to emulate human behaviour whilst removing human reaction time and factors that increase time to purchase an item. This is done by using a combination of xpaths and id as they are both specific to the html location meaning that no accidental items will be purchased or wrong info. 

Special mention to Adam for collaboration with this bot - who I had co-developed several features whilst taking it further on. 
