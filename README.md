Multi-Threaded Parallel Web Crawler

This is a multi-threaded web crawler designed to crawl large numbers of websites in parallel using Java and HTML. The crawler is designed to take advantage of multi-core architectures to increase crawler throughput and improve performance compared to a legacy implementation.
Features

    Multi-threaded processing: The crawler uses multiple threads to crawl multiple websites in parallel, which can significantly speed up the crawling process and improve throughput.
    Advanced concurrency concepts: The crawler implements advanced concurrency concepts such as thread synchronization and locking to ensure that multiple threads can access shared resources safely and efficiently.
    Improved performance: The multi-threaded implementation can visit more web pages than a legacy implementation in the same amount of time, improving overall performance and throughput.
    Simple configuration: The crawler can be easily configured using a simple configuration file that specifies the list of websites to crawl and other settings.

Usage

To use the multi-threaded parallel web crawler, follow these steps:

    Clone the repository to your local machine:

    bash

git clone https://github.com/your-username/marialauramendez/webCrawler.git

Install the dependencies and build the project using Maven:

mvn clean install

Create a configuration file that specifies the list of websites to crawl and other settings. An example configuration file is provided in config.properties.example.

Start the crawler by running the Crawler.java class with the path to the configuration file:

lua

    java Crawler config.properties

The crawler will begin crawling the specified websites in parallel, and the results will be output to the console and to a CSV file.
Performance

The multi-threaded implementation of the web crawler has been tested and shown to have improved performance compared to a legacy implementation. In tests, the multi-threaded implementation was able to visit more web pages in the same amount of time, improving overall throughput and efficiency.
Contributing

If you'd like to contribute to the multi-threaded parallel web crawler, please fork the repository and submit a pull request with your changes. Contributions are always welcome!
License

This project is licensed under the MIT License. See the LICENSE file for details.
