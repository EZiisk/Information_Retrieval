# Information_Retrieval

Information retrieval project  based on the TREC Clinical Trials Challenge dataset. ElasticSearch was used to create an interactive search engine to match suitable pateints to clinical trials. 

A subset of the TREC Clinical trials dataset was used due to size limitations. Performance metrics were filtered based only on available patients/ trials to account for the lack of complete dataset.

The keyword extraction transformer KeyBERT was used as part of one experiment to assess its performance on verbose queries. 

Performance was measured in: 
- accuracy
- recall
- precision
- relevance (scored using bespoke TREC relevance scoring)

# To run:
 Download dataset and update paths to match local file location
 - follow comments in notebook for guidance/ explanation
 
