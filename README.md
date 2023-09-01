
  Problem Statement

Design and implement a simple producer/consumer web link extractor that meets the following requirements:

The producer receives a list of URLs and extracts the markup from each of the URLs.
The markup is placed onto a queue.
The consumer reads the queue until it is empty.
The consumer parses the HTML and extracts a list of hyperlinks.
The list of hyperlinks is output to a file or the command line.
Requirements

As the give code challenge is in a format of mat, by suing physical software, the text file converted into UFT-8 and saved as a pdf.
The producer and consumer must run concurrently.
Error handling should ensure isolation. One bad fetch or parse should not affect the processing of others.
Some unit tests should be written.
The project should be pushed to a GitHub repository and the link should be provided.
The following diagram shows the design of the producer/consumer web link extractor:

Producer
   1.Get URLs
   2.Extract Markup
   3.Put Markup on Queue
Consumer
   1.Get Markup from Queue
   2.Parse HTML
   3.Extract Hyperlinks
   4.Output Hyperlinks

As the final output, it was regarded as that there is no links found in the give data file.
