# Keyword similarity matching to assess the potential of Pathum Thani provincial strategy by knowledge base analysis

This project is For DSI314 Business Capstone Project therefore focuses on analyzing strategic data through provincial development plans and project data disbursed through the government's central budget using natural language processing techniques and the application of large language models to support planning and decision-making, including alignment with sustainable development goals, increasing efficiency in resource allocation, budget, and future policy development, as well as improving and developing projects to be in line with the needs of the people and changes in society.
Pathum Thani Province in the future

The data used in the project is divided into 2 parts:

1. Electronic documents (PDF) published on the website of Pathum Thani Province, which collects project data and annual action plans that are in line with the development issues of
Pathum Thani Province, 4 issues, over a period of 3 years (63-65)

2. CSV file dataset of projects disbursed by the central budget of Pathum Thani Province in the 2018-2022 timeframe, the website of the Tax Where? by the Digital Government Development Agency (Public Organization) (DGA)
3. This project uses data processing techniques before analysis by extracting data from documents of government agencies in the form of image files using Optical Character Recognition (OCR) techniques and using WangchanBERTA-BASE-NER, a large language model (LLM) to identify and classify entities (Named Entity Recognition or NER), such as personal names, places, and organizations, to organize data before cutting words to extract keywords using Method I PS TF-IDF Scoring. After that, the obtained keywords will be checked for consistency with the strategy using Method II PL Word intersections methods. That is, using 5 large language models that are effective with Thai language such as OpenthaiGPT, Typhoon-70b, LLama-70b, ChatGPT, Claude sonnet by setting prompts in the same format and selecting using a list of keywords. Those selected keywords will be linked to the dataset in the Where to Go Tax project to link the strategic issues of the province. With the Where to Go Tax project to create a Knowledge Graph using the Neo4j engine, which shows relationships in the form of Node and Edge. After that, the obtained Knowledge Graph is used to query consistent data for further development of reporting plans in various issues.
# Keyword similarity matching to assess the potential of Pathum Thani provincial strategy by knowledge base analysis

This project is For DSI314 Business Capstone Project therefore focuses on analyzing strategic data through provincial development plans and project data disbursed through the government's central budget using natural language processing techniques and the application of large language models to support planning and decision-making, including alignment with sustainable development goals, increasing efficiency in resource allocation, budget, and future policy development, as well as improving and developing projects to be in line with the needs of the people and changes in society.
Pathum Thani Province in the future

The data used in the project is divided into 2 parts:

1. Electronic documents (PDF) published on the website of Pathum Thani Province, which collects project data and annual action plans that are in line with the development issues of
Pathum Thani Province, 4 issues, over a period of 3 years (63-65)

2. CSV file dataset of projects disbursed by the central budget of Pathum Thani Province in the 2018-2022 timeframe, the website of the Tax Where? by the Digital Government Development Agency (Public Organization) (DGA)
   
3. This project uses data processing techniques before analysis by extracting data from documentsof government agencies in the form of image files using Optical Character Recognition (OCR) techniques and using WangchanBERTA-BASE-NER, a large language model (LLM) to identify and classify entities (Named Entity Recognition or NER), such as personal names, places, and organizations, to organize data before cutting words to extract keywords using Method I PS TF-IDF Scoring. After that, the obtained keywords will be checked for consistency with the strategy using Method II PL Word intersections methods. That is, using 5 large language models that are effective with Thai language such as OpenthaiGPT, Typhoon-70b, LLama-70b, ChatGPT, Claude sonnet by setting prompts in the same format and selecting using a list of keywords. Those selected keywords will be linked to the dataset in the Where to Go Tax project to link the strategic issues of the province. With the Where to Go Tax project to create a Knowledge Graph using the Neo4j engine, which shows relationships in the form of Node and Edge. After that, the obtained Knowledge Graph is used to query consistent data for further development of reporting plans in various issues.

# Workflow
<p align="center">
  <img src="https://github.com/SirapopChu/DSI314_Keyword-similarity-matching-to-assess-the-potential-of-Pathum-Thani-provincial-/blob/main/wf.png" alt="Workflow" style="width:1000px;" />
</p>




