This is a small web scraping project of australian crop data from official gouvernment website .
we use two websites first to extract 2 tables from "https://www.saskatchewan.ca/business/agriculture-natural-resources-and-industry/agribusiness-farmers-and-ranchers/market-and-trade-statistics/crops-statistics/crop-report" by using pd.read_html, 
The second was sample of code is to extract an excel file with australian crop data from "https://www.agriculture.gov.au/abares/research-topics/agricultural-outlook/data#australian-crop-report-data" by using Webdriver
we clean all the tables and store them in a csv data then use them to build a Power BI dashbard 
we also have an automation code to send by email all our datas that can be programmed to send us every new data from the websites