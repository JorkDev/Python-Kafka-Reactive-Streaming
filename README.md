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

## Setting Up Kafka Cluster and ksqlDB Cluster with Confluent Cloud

To get started with this project using Confluent Cloud, you'll need to set up a Kafka cluster for real-time data streaming and a ksqlDB cluster for stream processing. Follow the steps below to create both clusters:

### Kafka Cluster Setup

1. **Sign Up for Confluent Cloud**: If you haven't already, sign up for a Confluent Cloud account at [Confluent Cloud](https://www.confluent.io/confluent-cloud/).

2. **Create a Kafka Cluster**: Log in to your Confluent Cloud account and navigate to the Clusters section. Click on "Create Cluster" and follow the prompts to create a new Kafka cluster. Choose your desired cloud provider, region, and cluster settings.

3. **Generate API Key and Secret**: Once your Kafka cluster is created, generate an API key and secret for accessing the cluster. Navigate to "Cluster Settings" > "API Access" and click on "Create Key" to generate the credentials.

4. **Download Configuration File**: Download the configuration file for your Kafka cluster from the Confluent Cloud UI. This file contains the necessary connection information for connecting to your Kafka cluster programmatically.

### ksqlDB Cluster Setup

1. **Create a ksqlDB App**: Navigate to the "ksqlDB" section in your Confluent Cloud account and click on "Add ksqlDB App". Follow the prompts to create a new ksqlDB cluster. Choose your desired cloud provider, region, and cluster settings.

2. **Enable Schema Registry**: If you plan to use Avro serialization with your ksqlDB cluster, enable Schema Registry for your ksqlDB app. Navigate to "ksqlDB" > "Cluster Details" > "Schema Registry" and enable the feature.

3. **Access ksqlDB UI**: Once your ksqlDB cluster is created, access the ksqlDB UI by clicking on "ksqlDB UI" in the Confluent Cloud UI. This allows you to interactively query and process streams of data using ksqlDB.

4. **Connect ksqlDB to Kafka**: Use the configuration file downloaded earlier to configure the connection between your ksqlDB cluster and Kafka cluster. Follow the instructions provided in the Confluent Cloud documentation to set up the connection.

By following these steps, you'll have a Kafka cluster for data streaming and a ksqlDB cluster for stream processing set up and ready to use with this project on Confluent Cloud.

## Contributions

We welcome contributions from the community to improve this project! If you're interested in contributing, here's how you can get started:

1. **Fork the Repository**: Start by forking this repository to your own GitHub account.
2. **Clone the Repository**: Clone the forked repository to your local machine using the `git clone` command.
3. **Create a Branch**: Create a new branch for your contributions using `git checkout -b feature/new-feature` (replace `new-feature` with a descriptive branch name).
4. **Make Changes**: Make your desired changes to the codebase.
5. **Test Your Changes**: Ensure that your changes don't break existing functionality and add any necessary tests.
6. **Commit Your Changes**: Commit your changes with descriptive commit messages.
7. **Push Changes**: Push your changes to your forked repository with `git push origin feature/new-feature`.
8. **Create a Pull Request**: Submit a pull request from your branch to the main repository. Be sure to provide a detailed description of your changes and any related issues.
9. **Review and Collaborate**: Collaborate with maintainers and reviewers to address any feedback and ensure your changes meet the project's standards.
10. **Celebrate**: Your contribution is valuable! Thank you for your effort in improving this project.

If you have any questions or need assistance with the contribution process, feel free to reach out to us or refer to the [GitHub documentation](https://docs.github.com/en/get-started) for more guidance.

This project is maintained by me, for any questions or inquiries, please contact [jorkaefdev@gmail.com](mailto:jorkaefdev@gmail.com).