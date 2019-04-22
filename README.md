# Geodata Solr Core Configuration

## Branches:
I changed the methodology originally implemented by Michael B. in November 2018.  Previously, he had two solr-core brances in this repo: one for production, and a second branch for development.  I simplified this to a single core named "geodata-core."

Since we have two servers, one for production and another for test, it felt unnecessary to have two cores for production and two for "test."  In our case, both solr platforms are effectively treated as "production" (i.e., cores in production and test are identical)

