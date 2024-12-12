# Repository for the Publication: Can large language models support machine learning implementation in product development? A comparative analysis and perspectives 
## Abstract
Recent advancements in machine learning (ML) offer substantial potential for enhancing product development. However, adoption in companies remains limited due to challenges in framing domain-specific problems as ML tasks and selecting suitable ML algorithms, requiring expertise often lacking. This study investigates the use of large language models (LLMs) as recommender systems for facilitating ML implementation. Using a dataset derived from peer-reviewed publications, the LLMs were evaluated for their ability to recommend ML algorithms for product development-related problems. The results indicate moderate success, with GPT-4o achieving the highest accuracy by recommending suitable ML algorithms in 61% of cases. Key limitations include inaccurate recommendations and challenges in identifying multiple sub-problems. Future research will explore prompt engineering to improve performance.
## Repository Content
This repository includes the following files, created as part of the publication:
1. **Documentation of the systematic literature review (TXT)**
2. **Literature data (BibTeX Files)**
3. **Created dataset (JSON)**

### Documentation of the systematic literature review (TXT)
The literature review, conducted to identify publications addressing the application of machine learning (ML) algorithms to product development-related problems, followed the PRISMA 2020 guidelines. Detailed documentation of the review process is provided in the accompanying text file, which includes:
- The definition of word groups and corresponding keywords
- The search strings used
- The inclusion and exclusion criteria applied
- The restrictions implemented in the Scopus and Web of Science databases during the search process

### Literature data (BibTeX Files)
The publications identified through the systematic literature review process have been categorized into the four defined product development phases of the VDI 2221: problem definition (PD), concept development (CD), embodiment design (ED), and detailed design (DD). These publications, assigned to their respective product development phases, form the foundation for the creation of the dataset and are provided in distinct BibTeX files. The naming convention for the files is as follows:
- Problem definition (PD): *PD_Publications_identified_as_suitable*
- Concept development (CD): *CD_Publications_identified_as_suitable*
- Embodiment design (ED): *ED_Publications_identified_as_suitable*
- Detailed design (DD): *DD_Publications_identified_as_suitable*
  
### Created dataset (JSON)
The dataset used for evaluating the large language models consists of two key elements: 
- **Product development-related problem formulations** extracted from the identified publications
- **Machine learning algorithms** applied to address these product development-related problems in the publications
Currently, the dataset comprises 156 problem formulations along with their corresponding applied machine learning algorithms.
