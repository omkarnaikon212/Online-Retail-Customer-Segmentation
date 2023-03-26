# Online-Retail-Customer-Segmentation
This is 4th capstone project for AlmaBetter School, involving unsupervised ML algorithm.

I recieved a data frame with following features(columns):

InvoiceNo: Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation. StockCode: Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product. Description: Product (item) name. Nominal. Quantity: The quantities of each product (item) per transaction. Numeric. InvoiceDate: Invoice Date and time. Numeric, the day and time when each transaction was generated. UnitPrice: Unit price. Numeric, Product price per unit in sterling. CustomerID: Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer. Country: Country name. Nominal, the name of the country where each customer resides.

The cx of any retain company falls under different category and sub groups. Those groups can be based on country, time of purchase, types of purchase, total purchase and so on. Segementating them into multiple groups using ML models helps the company for better service, keeping good and old cx happy and targeted advertisment, etc.

I started my project with dropping null values, as there was no good way to replace them. I also stripped date, month, time, etc. in different column for better analysis. I also made a new feature of total cost a cx spend. Further, I analysed which countries have highest number of cx, months with high orders, products that gets most demand, etc. I also made graph to have a clear visulization.

I also noticed a number of cx cancelled the order, I dropped cx with negative total cost before modelling. The company is ideally suggested to look into why some cx cancelled orders.

I did the RFM modelling, thus analysed the cx on basis of Recency, Frequency, Monetary Value. In the last part I used different ML models to cluster data into different groups. According to models, following are the ideal number of clusters to be divided.
