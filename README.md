# Vivatech_hackathon_2018
Challenge: 
"Leboncoin is challenging you hackers to develop a marketplace of the future that emphasizes and improves the relationship between the buyer and the seller. Feel free to use innovative technologies like augmented reality, IoT and artificial intelligence."

Description of our solution: 
"Artificial intelligence facilitates buyers and sellers gathering".
Our team have implemented a tag generator solution to facilitate the visibility of seller products in the Leboncoin platform. Each time a seller wants to upload a product, he types a brief title/description of his product. This text receives a Natural Language processing treatment: Requests are sent to Leboncoin API (which stocks all the current available items) to watch what kind of products would appear if a client would make a research with this text on Leboncoin platform. According to the types of products tags are generated to the seller. He can the choose which tags to select to emphasize the category of his product. Then when a client makes a product research, tags related to the main products categories corresponding to this research are generated. The client select the tags he wants to specify his request and corresponding products are revealed. 

## How to use
From the main directory launch: `$python3 api.py`
