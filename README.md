
  Problem Statement

Design and implement a simple producer/consumer web link extractor that meets the following requirements:

The producer receives a list of URLs and extracts the markup from each of the URLs.
The markup is placed onto a queue.
The consumer reads the queue until it is empty.
The consumer parses the HTML and extracts a list of hyperlinks.
The list of hyperlinks is output to a file or the command line.
Requirements

The producer and consumer must run concurrently.
Error handling should ensure isolation. One bad fetch or parse should not affect the processing of others.
Some unit tests should be written.
The project should be pushed to a GitHub repository and the link should be provided.
The following diagram shows the design of the producer/consumer web link extractor:

Producer
   |
   |-- Get URLs
   |-- Extract Markup
   |-- Put Markup on Queue
Consumer
   |
   |-- Get Markup from Queue
   |-- Parse HTML
   |-- Extract Hyperlinks
   |-- Output Hyperlinks

