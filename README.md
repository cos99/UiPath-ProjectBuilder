# UiPath-ProjectBuilder
A bot that automatically scrapes on different websites to find the requested components and their price, organising them into an excel file.

### How it works
The bot connects to a database, it takes the sites and the links that contain wildcards, then opens the excel file given as input, takes one component at a time, searches it on the websites that were given from the database, takes the link to the component that is found (only the first one) and the price. Lastly, it writes the data scraped in the same file where the components are written.
