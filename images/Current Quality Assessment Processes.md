The Deployment Working Group initially sent a survey but we want to make sure all tools are represented as we move forward identifying infrastructure, processes, policies

|Team|Tool|Function [KP, ARA, Shared Component]|What are you testing for?|How?[Automated/Manual]|What are you using?|How are you assessing results?|Frequency?|CI/CD?[Yes/No]|CI/CD Tech Stack|Future Plans
|---|---|---|---|---|---|---|---|---|---|---
|Link Brokers|ARS|Shared|Availability, quality|Manual|TRAPI Queries|Manual Assessment by SMEs|weekly|---|---|Automated, Travis
|Clinical Data Services Provider|COHD|KP|Reasoner queries returning the expect number of results and result format complies with schema. Also testing for other calls provided by the API|Automated|pytest|COHD compares some tests against manually curated expected results.|at each push to GitHub & every 12 hours|CI yes, CD Enabled|GH Actions|Continue using the GitHub Actions stack, and add more tests for expected specific queries results
|Clinical Data Services Provider|NeuroDKG|---|---|---|---|---|---|---|---|---
|Clinical Data Services Provider|OpenPredict|KP|Reasoner queries returning the expect number of results and result format complies with schema. Also testing for other calls provided by the API|Automated|pytest|OpenPredict uses sonar cloud quality analysis (provides test coverage, code warnings)|at each push to GitHub|CI yes, CD Enabled|GH Actions|Continue using the GitHub Actions stack, and add more tests for expected specific queries results
|Clinical Data Services Provider|Tr Knowledge Collaboratory|---|---|---|---|---|---|---|---|---
|Clinical Data Services Provider|RCT PICO Provider|---|---|---|---|---|---|---|---|---
|Connections Hypothesis Provider|CHP|KP|---|---|---|---|---|---|---|---
|Expander Agent|ARAX|---|---|---|---|---|---|---|---|---
|Explanatory Agent|xARA|---|---|---|---|---|---|---|---|---
|Exploring Agent|BTE Agent|---|---|---|---|---|---|---|---|---
|Exploring Agent|PFOCR Provider|---|---|---|---|---|---|---|---|---
|Exposures Provider|ICEES+|---|---|---|---|---|---|---|---|---
|Exposures Provider|CAM|---|---|---|---|---|---|---|---|---
|(im)Prove Agent|(im)Prove Agent|---|---|---|---|---|---|---|---|---
|(im)Prove Agent|SPOKE Provider|---|---|---|---|---|---|---|---|---
|Genetics Provider|Genetics Provider|---|---|---|---|---|---|---|---|---
|Molecular Data Provider|MolePro|---|---|---|---|---|---|---|---|---
|Multiomics Provider|Wellness|---|---|---|---|---|---|---|---|---
|Multiomics Provider|BigGim|---|---|---|---|---|---|---|---|---
|Multiomics Provider|Drug Response|---|---|---|---|---|---|---|---|---
|Multiomics Provider|TCGA Mutation Freq|---|---|---|---|---|---|---|---|---
|Multiomics Provider|Big Query Table|---|---|---|---|---|---|---|---|---
|Ranking Agent|Aragorn|---|---|---|---|---|---|---|---|---
|Ranking Agent|Automat Provider|---|---|---|---|---|---|---|---|---
|Service Provider|Service Provider|---|---|---|---|---|---|---|---|---
|Text Mining Provider|Cooccurrence KG|---|---|---|---|---|---|---|---|---
|Text Mining Provider|Targeted Association KG|---|---|---|---|---|---|---|---|---
|Unsecret Agent|Unsecret Agent|---|---|---|---|---|---|---|---|---
|SRI|BL Lookup|---|---|---|---|---|---|---|---|---
|SRI|Reference KG|---|---|---|---|---|---|---|---|---
|SRI|Name Resolver|---|---|---|---|---|---|---|---|---
|SRI|Edge Normalizer|---|---|---|---|---|---|---|---|---
|SRI|Node Normalization|---|---|---|---|---|---|---|---|---
|SRI|BL Compliance Service|---|---|---|---|---|---|---|---|---
|SRI|Plater|---|---|---|---|---|---|---|---|---
|SRI|Reasoner-pydantic|---|---|---|---|---|---|---|---|---
|SRI|Reasoner-validator|---|---|---|---|---|---|---|---|---
|SRI|Reference KG|---|---|---|---|---|---|---|---|---
