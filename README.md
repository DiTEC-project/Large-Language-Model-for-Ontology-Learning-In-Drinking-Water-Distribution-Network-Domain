# Large-Language-Model-for-Ontology-Learning-In-Drinking-Water-Distribution-Network-Domain

# Introduction
Currently, most ontologies are created manually, which is time-consuming and labour-intensive. Meanwhile, the advanced capabilities of Large Language Models (LLMs) have proven beneficial in various domains, significantly improving the efficiency of text processing and text generation. Therefore, this paper focuses on the use of LLMs for ontology learning. It uses a manual ontology construction method as a basis to facilitate the LLMs for ontology learning. The proposed approach is based on Retrieval Augmented Generation (RAG), and passed queries to LLMs are based upon the manual ontology method -- UPON Lite ontology. Two different variants of LLMs have been experimented with, and they all demonstrate the capability of ontology learning to varying degrees. This approach shows promising initial results in the direction of (semi-) automated ontology learning using LLMs and makes the ontology construction process easier for people without prior domain expertise. The results were evaluated by the domain expert, and LLMs results were ranked based on the defined criteria. 

Below are flowcharts that visualize the logic behind the RAG and query pipeline:

RAG:

![Flowchart-rag](https://github.com/Rhea0000/Thesis/assets/145769931/06890aec-822c-4c1b-b449-822c08a6cac0)


Query Pipeline:
![Flowchart without input](https://github.com/user-attachments/assets/416e215e-1391-48c6-92e5-2aa6b939d8b6)



# Instructions
The file "Code" contains all the information for the reuse. 
The `Python_code.py` contains all the core code for creating ontology using Python.
The input document is named `Document_Input`. 
The file `Parameters.yaml` encompass all adjustable parameters in the code. 

## Prerequisites

- Python 3.8 or higher
- Visual Studio Code

## Installation

Before running the code, ensure you have the following files:
- `Parameters.yaml`
- `Document_Input`
- `Python_cpde.py`

You do not need to execute `Parameters.yaml` and `Document_Input` unless you want to change the parameters and input, they are required for the `Python_code.py`.

## Configuration

All default parameters are stored in `Parameters.yaml`. If you need to adjust queries or inputs, modify them in this file.

## Execution

To run the code:
1. Open `Python_code.py` in Visual Studio Code.
2. Install any missing packages if necessary.
3. Replace the default file locations for `Parameters.yaml` and `Document_Input` with the paths to your files.
4. Input your API key for OpenAI, Hugging Face, or another compatible platform for your LLM.
5. Define your embedding models and LLM in the code.
6. Run the code either in its entirety or step by step.

## Troubleshooting

If you encounter a 500 server error, it may indicate that the LLM is unable to process your query. In this case, try the following:
- Retry the request.
- Modify the query to ensure it is within the LLM's processing capabilities.

For further assistance, please open an issue in this repository.

# Reference
LangChain. 2024. Question Answering Quickstart. https://python.langchain.com/v0.1/docs/use_cases/question_answering/quickstart/
