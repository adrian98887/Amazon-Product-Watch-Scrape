# Amazon-Product-Watch-Scrape
Using Beautiful Soup to scrape title,price and rating of an amazon product.

Saving this to a CSV initially, then changing so new data is appended to that CSV.

Though process behind this is the function can be ran every 24 - 48h to check the price of a particulair item, once that item falls below a certain price the file will be uploaded to DropBox which will send an email notification (if that setting is enabled on dropbox) to notify about that price change.
