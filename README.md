# Reactive Data Streaming App with Python and Apache Kafka

Have you ever wondered how to get live notifications from a service that doesn’t support live notifications? Can you watch an online store for price drops? Or track comments on someone else’s YouTube video? In this episode of Coding in Motion, we’ll show you how to build a solution that brings static data to life by turning it into a reactive system.

## Overview

In this project, we'll demonstrate how to turn a static data source—YouTube’s REST API—into a reactive system using Python and Apache Kafka. This solution allows you to:

- Use Python to fetch and process data from a static web API
- Stream that data live, from Python into a Kafka topic
- Process the incoming source data with ksqlDB, watching for important changes
- Stream out live, custom notifications via Telegram

## How It Works

1. **Fetching and Processing Data**: We start by using Python to fetch data from the YouTube REST API and process it.
   
2. **Streaming Data with Apache Kafka**: Next, we stream the processed data into a Kafka topic, enabling real-time data streaming.

3. **Processing Data with ksqlDB**: We use ksqlDB to process the incoming data stream, monitoring for significant changes or events.

4. **Sending Custom Notifications**: Finally, we send out live, custom notifications via Telegram to alert users of important updates or changes.

## Getting Started

To get started with this project, follow these steps:

1. **Clone the Repository**: Clone this repository to your local machine.

2. **Set Up Dependencies**: Install the required dependencies by running `pip install -r requirements.txt`.

3. **Set Up Apache Kafka**: Install and set up Apache Kafka on your machine. Refer to the Kafka documentation for instructions.

4. **Run the Application**: Start the application by running the necessary Python scripts. Make sure to configure the API keys and other settings as required.

5. **Explore and Customize**: Feel free to explore the codebase and customize it to fit your needs. You can modify the data sources, processing logic, and notification methods according to your requirements.

6. **Contribute**: If you find any issues or want to contribute to the project, please submit a pull request or open an issue on GitHub.

## Credits

This project is brought to you by Kris Jenkins as a part of the Coding in Motion series.

