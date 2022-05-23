# Streaming Finance Data with AWS Lambda
## Background
In this project, we work with a stream of financial data that arrives continuously. Therefore as result, we will generate near real-time financial data records for downstream processing and interactive queries using Lambda functions. We will grab pricing information for each of the following stocks:
    Facebook (FB),
    Shopify (SHOP),
    Beyond Meat (BYND),
    Netflix (NFLX),
    Pinterest (PINS),
    Square (SQ),
    The Trade Desk (TTD),
    Okta (OKTA),
    Snap (SNAP),
    Datadog (DDOG).
The data is collected from Yahoo finance with yfinance package and loaded into AWS S3 bucket. AWS Glue and AWS Athena are leveraged to perform interactive querying.
## Applied technology 
As I mention Above, we will using the AWS kinesis, AWS S3, AWS Athena, AWS Glue, AWS Lambda

## Lambda Configuration Page Data Transformation
We will use yfinanced to grab stock information for the company I mentioned above
I collected one full day’s worth of stock HIGH and LOW prices for each company listed above on Monday, May 2nd 2022, at a five minute interval.
![DataCollect lambda](https://user-images.githubusercontent.com/83876072/169730410-e11a5858-9043-4791-841d-67055a8351cf.png)















## Data Transformation-- Kinesis Data Firehose Delivery Stream Monitoring
![Kinesis_Xing_Huang](https://user-images.githubusercontent.com/83876072/169729883-46c9f633-94f4-4e73-acef-bf5a1e5ff91b.png)

## exec_results.jpeg
![exec_results_Xing_Huang jpeg](https://user-images.githubusercontent.com/83876072/169731449-8bcafab3-1ac0-4d2a-83a5-d6a1633b81c0.png)



