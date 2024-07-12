# Large-Language-Model-for-Ontology-Learning-In-Drinking-Water-Distribution-Network-Domain

# Introduction
Currently, most ontologies are created manually, which is time consuming and labour intensive. Meanwhile, the advanced capabilities of Large Language Models (LLMs) have proven beneficial in various domains, significantly improving the efficiency of text processing and text generation. Therefore, this paper focuses on the use of LLMs for ontology learning. It uses a manual ontology creation method as a basis to facilitate the use of LLMs for ontology learning. Two different variants of LLMs have been experimented with, and they all demonstrate the capability of ontology learning to varying degrees. This approach proves that it is possible to automate the entire process of using LLMs to generate the ontology and make it accessible to people without prior domain expertise. It is also very efficient, not only saving significant time but also improving usability. The final ontology returned by the LLMs could be used as a base version according to the evaluation results and needs to be validated and refined by the domain experts to ensure its accuracy and completeness. 

Below are flowcharts that visualize the logic behind the RAG and query pipeline:

RAG:

![Flowchart-rag](https://github.com/Rhea0000/Thesis/assets/145769931/06890aec-822c-4c1b-b449-822c08a6cac0)


Query Pipeline:
![FLOWCHART](https://github.com/DiTEC-project/Large-Language-Model-for-Ontology-Learning-In-Drinking-Water-Distribution-Network-Domain/assets/145769931/6e734f2d-14a0-4e80-8525-7b34aeeac875)



# Instructions
The file "Python code" contains all the information for the reuse. 
The `Thesis_code.py` contains all the core code for creating ontology using Python.
The input document is named `Document_Input`. 
The file `Parameters.yaml` encompass all adjustable parameters in the code. 

## Prerequisites

- Python 3.8 or higher
- Visual Studio Code

## Installation

Before running the code, ensure you have the following files:
- `Parameters.yaml`
- `Document_Input`
- `Thesis_code.py`

You do not need to execute `Parameters.yaml` and `Document_Input` unless you want to change the parameters and input, they are required for the `Thesis_code.py`.

## Configuration

All default parameters are stored in `Parameters.yaml`. If you need to adjust queries or inputs, modify them in this file.

## Execution

To run the code:
1. Open `Thesis_code.py` in Visual Studio Code.
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
