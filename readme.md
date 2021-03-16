# Data Pipeline of Facebook Artist Chatbot (Spotify API)

*※  The scripts are from the last section of Fastcampus Data Engineering course, yet I, of course, typed and reviewed all the scripts for my understanding.* 



## Summary

This is my first data engineering project with data pipeline example of Facebook Artist Chatbot Application. The chatbot provides top tracks and genres of the global artists through Spotify API in real time. 



## Environment

|      Type      |              Details               |
| :------------: | :--------------------------------: |
|    Language    |         Python 3.7, Shell          |
|    Storage     |            AWS S3, EC2             |
|     RDBMS      |          AWS RDS (MySQL)           |
|     NoSQL      |            AWS DynamoDB            |
|       OS       | Ubuntu 14.05 (AWS EC2), Windows 10 |
|    API Call    |             AWS Lambda             |
| Log Monitoring |          AWS Cloud Watch           |
|  API Service   |          AWS API Gateway           |
|    Library     |     Pymysql, boto3, json, etc      |
|  Data Source   |            Spotify API             |



## Data Pipeline

<img src="C:\Users\Trey\Desktop\Markdown files\Github\images\chatbot_pipeline.png" style="zoom:70%;" />

## How It Works

1. Facebook Chatbot (Client)
   - Artist 이름을 챗봇에 입력한다.
2. AWS Lambda Function





## Project Review

#### DynamoDB를 top tracks를 업데이트하는 테이블로 사용한 이유는 무엇인가?

- RDS와 DynamoDB의 차이점



그 외의 issues

- Due to Covid-19, Facebook currently has paused to review and approve the apps for individual uses.