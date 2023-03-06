# UniSpec Backend
Features
1. Scraping to be done on Platfroms
    1. LinkedIn
        - https://pypi.org/project/linkedin-scraper/
        - https://github.com/joeyism/linkedin_scraper
    2. Tinder
        - https://github.com/frederikme/TinderBotz
        - https://github.com/altskop/tinder-scraper
    3. YouTube
        - https://pypi.org/project/youtube-video-scraping/
        - https://serpapi.com/blog/scrape-youtube-video-page-with-python/
    4. Google
        - https://pypi.org/project/google-search-scraper-python/
        - https://serpapi.com/blog/scrape-google-product-page-with-python/

## InLine Description

Our stack combines Python and AWS to collect data from popular online platforms such as LinkedIn, Tinder, Google, and YouTube. We use Python to write scripts that scrape data from these platforms and store it in the DynamoDB, a fully managed NoSQL database service provided by AWS.

To access this data, we have set up an API Gateway that uses API authentication to ensure secure access to the collected data. This allows users to easily consume the data using RESTful APIs.

By leveraging the power of Python and AWS, we have created an efficient and scalable solution for collecting and accessing data from multiple sources. Moreover, our stack allows for real-time data collection and processing. The scripts we have written are designed to run continuously in the background, constantly collecting data from the specified sources. This ensures that the data stored in the DynamoDB is always up-to-date and accurate.

In addition, our use of AWS ensures that our solution is highly scalable. As our data collection needs grow over time, we can easily add more resources to our stack to accommodate the increased demand. This ensures that our solution can handle large amounts of data without compromising on performance.

Overall, our stack with Python and AWS is a powerful solution for collecting data from multiple sources and making it accessible via APIs. Its real-time data collection capabilities and scalability make it a reliable and efficient solution for businesses that need to collect and access data from various sources.

## Steps Outline
- Create a Python script to scrape data from LinkedIn, Tinder, Google and YouTube using their respective APIs.
- Use AWS Lambda to run the Python script periodically and store the data in DynamoDB.
- Set up AWS API Gateway to allow authorized access to the data stored in DynamoDB.
- Use AWS IAM to manage access to the API Gateway.
- Implement OAuth 2.0 authentication with AWS Cognito to secure access to the API Gateway.
- Use AWS Kinesis to stream data from the Python script to DynamoDB.
- Use AWS SNS to send notifications when new data is added to DynamoDB.
- Use AWS CloudWatch to monitor the Python script and the DynamoDB table.
- Use AWS S3 to store large files such as videos and images, and link them to the corresponding data in DynamoDB.
- Use AWS Athena to query and analyze the data stored in DynamoDB.
- Use AWS QuickSight to generate visualizations and dashboards based on the data stored in DynamoDB.