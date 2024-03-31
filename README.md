# Random-User-API-Performance-Test

## Technology and Tool Used
- Apache JMeter
- Java

## Scenerio
Find out the actual TPS for if 120000 user can give load for 12 hour. \
Perform load test on this URL: https://random-data-api.com/api/v2/users
1. You have to find out if the expected TPS (Transaction Per/Second) meet the above requirement.
Breakdown the expected TPS in excel sheet and find out the actual TPS (10)

2. Create another excel sheet where you will try to find out the bottleneck/stress test point. (At which point the system starts to show 1% error)

## How to run this project
- Clone this project
- Run the .jmx file on jmeter

## Prerequisite
- Java & Jmeter must be installed


## Load & Stress Test Strategy Excel File: 
https://docs.google.com/spreadsheets/d/1woqdoQGgFtwiNpY07NOcfGgQAH_OTvSva0y_7wD7EUI/edit?usp=drive_link

## Screenshot of Load Test Strategy Report
![performane_test](https://github.com/touhid-96/Random-User-API-Performance-Test/assets/29010371/6d2063f3-404e-47a6-bef7-639c59ad17d5)

## Stress Test Strategy Report
Stress Test is not required because the Load Test has failed.
