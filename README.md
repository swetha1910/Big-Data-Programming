Big-Data-Programming
====================

Hadoop Map Reduce code to do some Big Data programming

Programs:

1. Word Count
2. Word Statistics - Count, Mean, Variance of words in Enron Email Corpus. (Uses combiner)

3. Inverted Index - Email address and a list of email Identifiers where the address was referenced
   a) Uses combiner,
   b) Performs sorting (in lexicographical order)
   c) Identifies only unique pairs and discards duplicates

4. Big Data processing using Custom Writable
5. Word Statistics Aggregator - combines daily data into weeks and generates a statistics report as in 2.
6. Using AVRO to perform Word Statistics on the Ernon corpus
7. Web Logs Parsing: Parse weblogs and generate user sessions from the logs 
8. Web Logs Parsing 2: Parses weblogs of two different formats (uses MultipleInputs feature) and generates one user session from    two different formats
9. Web Logs Parsing 3: Perform Replicated Join using Distributed Cache and classify the sessions based on user type (uses MultipleOutputs feature)
