# Custom-Search-Engine-on-AWS
The Search Engine built on AWS makes use of AWS Kendra, which is an intelligent search service provided by machine learning. The search engine can use a dataset stored within an AWS Simple Storage Service (Amazon S3) Bucket.

The search not only looks for keywords in the dataset, but it can also look for synonyms to the
keywords that are being searched. This gives the user the ability to search for relevant content
even if they are not aware of the exact keywords that they need to find. The users can even
make use of natural language as their queries.

Most commonly asked questions/queries related to the dataset can be added to the search
engine as a configuration as well. This helps the search engine display the results extremely
quickly if the query that the user is entering contains an FAQ, thus reducing the engine’s time
complexity.
