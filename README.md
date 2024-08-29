# DeepPhenoNet
DeepPhenoNet works to enhance the computability and interoperability of human phenotypes, diseases, and biomedical concepts from basic biomedical research to clinical medicine using large language models (LLMs)s, bridging the gap between vast biomedical terminologies and actionable insights

This Github page has the code used to embed phecodes using OpenAI's GPT ADA transformer model, Voyage, and Mistral. It also contains the code used to analyze these embeddings with tsne and a cosine-similarity matrix search tool.

To use the cosine-similarity matrix tool, ensure you have to have the attached CSV and HTML files saved to your computer in the same directory, and then you need to start a local HTTP server by entering the following code into your terminal:
 
For python 3.x:
python -m http.server 8000
 
For python 2.x:
python -m SimpleHTTPServer 8000
 
Then you should be able to open your browser and type in the local file to access each corresponding embedding's phenotype search tool:

- Mistral embeddings cosine-similarity search: http://localhost:8000/Mistral_search.html
- OpenAI embeddings cosine-similarity search: http://localhost:8000/Openai_search.html
- Voyage embeddings cosine-similarity search: http://localhost:8000/Voyage_search.html

 And for phecodes + the following additional mendelian diseases:  mendelian_dx = Nocturnal frontal lobe epilepsy 1','Nephrotic syndrome type 7','Sulfocysteinuria','Charcotte Marie Tooth Disease 2A','Spastic Paraplegia 30','Factor X deficiency','Hemochromatosis','Thyroid dyshormonogenesis','Familial erythrocytosis 1','Spinocerebellar ataxia','Interstitial nephritis karyomegalic','HARP syndrome','Essential thrombocythemia','Primary hyperoxaluria type 1','Familial cold autoinflammatory syndrome 3','Fabrys Disease'

use these files:
- Mistral: http://localhost:8000/Mistral_phecodes_with_mendelian_dx_search.html
- OpenAI: http://localhost:8000/Openai_phecodes_with_mendelian_dx_search.html
- Voyage: http://localhost:8000/Voyage_phecodes_with_mendelian_dx_search.html


Please email ellbowen@med.umich.edu with any questions
