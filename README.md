# 2023-VPT-Projects

Projects for 2023 VPT Programming Contest

List of Projects given below. 

## 1. LLM enabled search for Mediawiki sites
LLM enabled search will be a huge improvement over traditional full-text search solutions, by utilizing word embeddings and vector database. The project is to create a solution that can be used for any mediawiki powered sites.

### Process
* Build a pipeline to extract wiki data
* Split text using sentence transformer and store word embeddings in a vector database(e.g., ChromaDB)
* Build a search API

### Validation
* Build LLM powered search for https://tamil.wiki site as a standalone web application
* Bonus: Build it as a mediawiki plugin

### Links
* 
* 


## 2. Build Static site generator for Mediawiki sites
Most Wiki sites are database based where the authors/editors tend to be far less than users. To improve performance and cost, these sites can serve static generated pages to the users. The project aims to create a static site generator that maintains the layout, links etc., for mediawiki based sites.

### Process
* Collate corpus from literary domain where parallel translation exist 
* Process text (sentence alignment, parameter tuning)

### Validation
* Build a static site version of https://tamil.wiki and host it in a CDN (cloudflare, Vercel etc.,)

### Links 
* A plugin that generates static site for wordpress sites https://en-ca.wordpress.org/plugins/simply-static/


