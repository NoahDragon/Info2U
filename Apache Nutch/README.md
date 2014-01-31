Apache Nutch
=======

##What is Apache Nutch?
Apache Nutch is a highly extensible and scalable open source web crawler software project. Stemming from [Apache Lucene™](http://lucene.apache.org/java/), the project has diversified and now comprises two codebases, namely:

Nutch 1.x: A well matured, production ready crawler. 1.x enables fine grained configuration, relying on [Apache Hadoop™](http://hadoop.apache.org/) data structures, which are great for batch processing.
Nutch 2.x: An emerging alternative taking direct inspiration from 1.x, but which differs in one key area; storage is abstracted away from any specific underlying data store by using [Apache Gora™](http://gora.apache.org/) for handling object to persistent mappings. This means we can implement an extremely flexibile model/stack for storing everything (fetch time, status, content, parsed text, outlinks, inlinks, etc.) into a number of NoSQL storage solutions.
Being pluggable and modular of course has it's benefits, Nutch provides extensible interfaces such as Parse, Index and ScoringFilter's for custom implementations e.g. [Apache Tika™](http://tika.apache.org/) for parsing. Additonally, pluggable indexing exists for [Apache Solr™](http://lucene.apache.org/solr/), [Elastic Search](http://www.elasticsearch.org/), etc.

Nutch can run on a single machine, but gains a lot of its strength from running in a [Hadoop cluster](http://hadoop.apache.org/)

You can download Nutch [here](http://nutch.apache.org/downloads.html).

For more information about Apache Nutch, please see the [Nutch wiki](http://wiki.apache.org/nutch/).

Nutch is a project of the [Apache Software Foundation](http://www.apache.org/) and is part of the larger Apache community of developers and users.

##Getting Started
To get started, begin here:

    1.[Learn about](http://nutch.apache.org/wiki.html) Nutch by reading the documentation.
    2.[Download](http://nutch.apache.org/downloads.html) Nutch from the release page.
    3.[Discuss](http://nutch.apache.org/mailing_lists.html) Nutch on the mailing lists.
    
##Download Nutch
Please head to the [releases](http://nutch.apache.org/downloads.html) page to download a release of Apache Nutch.
