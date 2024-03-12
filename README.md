# Collection of tools for indexing and searching in vector databases

## MILVUS DATABASE USAGE

The main files are the jupyter notebooks: scrapeParse_MDR, json2csv and milvus_CR_test.

***scrapeParse_MDR*** describes the method to:
 - scrape the MDR website,
 - create a dictionary with entries about the MDR,
 - save the entries as a json file.

***json2csv*** describes the functions to:
 - convert the json file from scrapeParse_MDR to a csv file that can be used in the vector database.

***milvus_CR_test*** describes the method to:
 - install and use the milvus database,
 - along with examples of vector search and a simple performance metric. More performance metrics can be learned and implemented using the following course:

https://learn.deeplearning.ai/building-evaluating-advanced-rag
