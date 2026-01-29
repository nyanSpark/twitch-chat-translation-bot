# Twitch Chat Translation Bot
A Python-based Twitch chat bot that provides real-time message translation using Google and Yandex translation APIs.

## Overview

`translation_bot` is a simple Python-based Twitch chat bot that connects to a Twitch channel and automatically translates chat messages in real time. It is designed to help multilingual communities communicate more easily during live streams.

The bot listens to chat messages, sends them to a translation API, and outputs translated text back into the chat or console depending on configuration.

## Features

- Connects to Twitch IRC and listens for live chat messages
- Automatically translates messages between languages
- Supports Google Translate and Yandex Translate APIs
- Simple configuration via `config.ini`
- Lightweight and easy to deploy

## Tech Stack

- Python (compatible with Python 2.7+)
- `requests` library for HTTP API calls
- Twitch IRC protocol
- Google Translate API
- Yandex Translate API
