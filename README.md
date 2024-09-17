# News Notification Application

## Overview

This Python application fetches news updates from an RSS feed and displays them as notifications on Windows using the `win10toast` library. The application fetches news items from BBC News and provides real-time updates via desktop notifications.

## Features

- Fetches news from an RSS feed.
- Parses XML data to extract news items.
- Displays each news item as a Windows toast notification.
- Customizable notification duration.

## Installation

1. **Clone the Repository**

    ```bash
    git clone https://github.com/username/desktop_notifier.git
    cd desktop_notifier

2. **Install Dependencies**

    pip install requests win10toast

## Usage

1. **Run the Script**

    Navigate to the project directory and run the script:
    python news_notifier.py

2. **Configuration**

- The RSS feed URL is set to BBC News RSS feed (<http://feeds.bbci.co.uk/news/rss.xml>). You can modify RSS_FEED_URL in the script if you want to use a different RSS feed.

## Contributing

- Feel free to contribute to this project by submitting issues or pull requests. For major changes, please open an issue first to discuss what you would like to change.

## Contact

- For any questions or feedback, please reach out to <rastogikunal19@gmail.com>.
