# Discourse Integration

This project contains a Jupyter Notebook focused on two essential techniques in Natural Language Processing (NLP) for understanding text beyond individual sentences. It helps machines interpret meaning in context, which is key to building smarter conversational agents and text processors.

## Included Concepts

1. **Discourse Marker Categorization**  
   Uses `NLTK` to identify discourse markers in a given text. Discourse markers (such as "but," "therefore," "also") indicate the logical flow between sentences or ideas, such as contrast, cause, result, addition, and condition. The notebook tokenizes text, filters out stopwords, and classifies the markers based on their category.

2. **Hobbs Algorithm for Pronoun Resolution**  
   Implements Hobbs’ algorithm using `spaCy` to resolve pronouns like "he," "she," or "it" by tracing back their likely antecedents within a sentence or across sentence boundaries. This is an essential step for machines to comprehend references in human language and maintain coherence in conversation.

## How to Run
1. Clone this repository.
2. Install the dependencies listed in the notebook.
3. Open the notebook with Jupyter or VSCode.
4. Execute cells step by step.

## Dependencies
- Python 3.x
- Jupyter Notebook
- NLTK
- spaCy
- English model for spaCy: `en_core_web_sm`
