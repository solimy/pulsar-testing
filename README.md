# pulsar-testing
# Purpose

This project is just a simple example using Apache Pulsar with python with :
- a producer, subscribed to "my-topic", sending random messages at random intervals.
- a consumer, subscribed to "my-topic", consuming and printing the messages.

# Install

Just have Docker installed.

# Run

Simply run 

    $>docker-compose up --build

Then wait 60 seconds.
> The clients have to wait for Pulsar to setupt metadatas
