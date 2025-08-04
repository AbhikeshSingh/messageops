# Solace PubSub+ Architecture

This guide explains how Solace PubSub+ is built and how it helps applications talk to each other quickly and reliably.

## Overview

Solace PubSub+ is a messaging system that moves data in real-time. The main parts are:

- **Brokers:** These are the servers that send messages between applications.
- **Topics:** This is where messages are published and received.
- **Queues:** Places where messages are stored until they are picked up.
- **Bridges:** Connections between brokers in different places (Geographical Location).

## Important Ideas

- **Publish and Subscribe:** This means senders and receivers don’t need to know about each other. They just send or listen to messages.
- **Event-driven:** Applications react when something happens, instead of checking all the time.
- **Always On:** Solace can keep running even if some parts fail.
- **Grows with You:** You can add more brokers to handle more messages.

This setup helps build strong and fast systems that work in many environments, like on your own servers or in the cloud.
