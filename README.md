Multithreaded Web Crawler in Java

Overview

This project is a multitt)

Installation

Clone the repository:

git clone https://github.com/your-repo/multithreaded-web-crawler.git
cd multithreaded-web-crawler

Compile the project:

javac -cp .:libs/* src/com/example/webcrawler/*.java -d bin

Run the crawler:

java -cp bin com.example.webcrawler.WebCrawler <start-url> <depth>

Usage

Run the crawler with a starting URL and depth:

java -cp bin com.example.webcrawler.WebCrawler https://example.com 2

<start-url>: The initial webpage to start crawling

<depth>: How deep the crawler should go

Configuration

Modify config.properties to change settings like:

Number of threads

User-agent string

Timeout settings

Code Structure

/multithreaded-web-crawler
├── src/com/example/webcrawler
│   ├── WebCrawler.java
│   ├── CrawlerTask.java
│   ├── URLQueue.java
│   ├── RobotsTxtHandler.java
│   ├── HTMLParser.java
│   └── Config.java
├── bin/
├── libs/
└── config.properties

Dependencies

JSoup for HTML parsing

Apache HttpClient for making HTTP requests

Contributing

Fork the repository

Create a new branch (git checkout -b feature-branch)

Commit your changes (git commit -m 'Add new feature')

Push to the branch (git push origin feature-branch)

Create a Pull Request

License

This project is licensed under the MIT License - see the LICENSE file for details.

Contact
adityasinha06841@gmail.com




