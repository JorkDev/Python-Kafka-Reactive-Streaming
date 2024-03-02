# Reactive Data Streaming App with Python and Apache Kafka

Ever wanted to receive real-time updates from services that don't offer live notifications? Wondered if you could monitor an online store for price drops or keep track of comments on YouTube videos? This project demonstrates how to transform static data sources into dynamic, reactive systems.

## Overview

This project showcases a solution for transforming static data from YouTube's REST API into a reactive system using Python and Apache Kafka. With this solution, you can:

- Utilize Python to retrieve and process data from static web APIs
- Stream the processed data in real-time using Apache Kafka
- Employ ksqlDB to analyze incoming data streams and detect significant changes
- Deliver customized, live notifications via Telegram to keep users informed about updates and changes.

## How It Works

1. **Fetching and Processing Data**: Python scripts fetch data from the YouTube REST API and preprocess it for streaming.

2. **Streaming Data with Apache Kafka**: Processed data is streamed into Kafka topics to enable real-time data streaming.

3. **Processing Data with ksqlDB**: ksqlDB is used to analyze the incoming data stream, identifying important events or changes.

4. **Sending Custom Notifications**: Customized notifications are sent via Telegram to notify users of relevant updates or changes.

## Getting Started

To start using this project:

1. **Clone the Repository**: Clone this repository to your local machine.

2. **Set Up Dependencies**: Install the required dependencies by running `pip install -r requirements.txt`.

3. **Set Up Apache Kafka**: Install and configure Apache Kafka on your machine. Refer to the Kafka documentation for instructions.

4. **Get a Google API Key**: To access YouTube's REST API, you'll need a Google API key. Follow these steps to get one:
   - Go to the [Google Developers Console](https://console.developers.google.com/)
   - Create a new project (or select an existing one)
   - Enable the YouTube Data API v3 for your project
   - Create credentials and select "API Key"
   - Copy the generated API key and paste it into config.py

5. **Run the Application**: Execute the necessary Python scripts to start the application. Ensure to configure API keys and other settings as required.

6. **Explore and Customize**: Feel free to explore the codebase and customize it to suit your needs. You can modify data sources, processing logic, and notification methods as necessary.

7. **Contribute**: If you encounter any issues or wish to contribute to the project, please submit a pull request or open an issue on GitHub.
