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

## Contributions

We welcome contributions from the community to improve this project! If you're interested in contributing, here's how you can get started:

- **Fork the Repository**: Start by forking this repository to your own GitHub account.
- **Clone the Repository**: Clone the forked repository to your local machine using the `git clone` command.
- **Create a Branch**: Create a new branch for your contributions using `git checkout -b feature/new-feature` (replace `new-feature` with a descriptive branch name).
- **Make Changes**: Make your desired changes to the codebase.
- **Test Your Changes**: Ensure that your changes don't break existing functionality and add any necessary tests.
- **Commit Your Changes**: Commit your changes with descriptive commit messages.
- **Push Changes**: Push your changes to your forked repository with `git push origin feature/new-feature`.
- **Create a Pull Request**: Submit a pull request from your branch to the main repository. Be sure to provide a detailed description of your changes and any related issues.
- **Review and Collaborate**: Collaborate with maintainers and reviewers to address any feedback and ensure your changes meet the project's standards.
- **Celebrate**: Your contribution is valuable! Thank you for your effort in improving this project.

If you have any questions or need assistance with the contribution process, feel free to reach out to us or refer to the [GitHub documentation](https://docs.github.com/en/get-started) for more guidance.
