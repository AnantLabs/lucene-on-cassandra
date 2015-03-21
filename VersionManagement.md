Supporting Multiple Versions of Lucene and Cassandra

# Introduction #

Because this project depends on two apache projects, viz. Lucene and Cassandra, each of which evolves differently, we must inevitably deal with the issue of compatibility across different versions of Lucene and Cassandra. To that end, we propose creating a branch for each combination of Lucene and Cassandra version that we intend to support.

# Details #

In particular, for a certain Lucene version `<foo>` and Cassandra version `<bar>`, let us create a branch in this project called `LUCENE-<foo>_CASSANDRA-<bar>`. Needless to say, that branch will refer to the libraries and corresponding dependencies of the respective versions of the apache projects. For instance, the branch for Lucene 3.0.1 and Cassandra 0.6.4 would be named LUCENE\_3.0.1-CASSANDRA\_0.6.4, and so on.