# This repository will guide you through a step-by-step implementation of running dbt core pre-release [1.9.0b](https://github.com/dbt-labs/dbt-snowflake/releases/tag/v1.9.0b1) in Snowpark Container Services, covering everything from setup and containerisation all the way to scheduling and monitoring. If you’re trying to create a simple containerised dbt setup, this repository will help you put all theory into action!

* Pre-requisites
* A note about dbt and Snowflake OAuth
* Setting up Snowflake objects for dbt
* Setting up a working dbt repository
* Create a working directory and clone the repo
* Create a virtual env and install dbt
* Containerise the dbt repository
* Note about Snowpark Authentication to Snowflake
* Create a snowpark dbt target
* Create a Docker Entrypoint Python File
* Add a requirements.txt file to the repo
* Create a Dockerfile
* Setting up Snowflake objects for Snowpark
* Compute Pool
* Image Repository
* Push Docker image to Snowpark
* Running containerised dbt in Snowpark
* Execute the Service
* Under the Hood
* Additional Considerations
* Logs, Scheduling, Error Notifications
* Access Persistent Logs
* Schedule Runs with Error Notifications
* Conclusion
