# Celebrity Recognition Project

## Introduction

Welcome to my project on celebrity recognition! This project explores two distinct methods for identifying celebrities from text data: Keyword-based Matching and Named Entity Recognition (NER). The data used for this project spans from 2006 to 2016 and was sourced from Reddit.

## Methodology

### 1. Keyword-based Matching

The first method employed was keyword-based matching. This approach involves identifying celebrities by matching their names against a predefined list of keywords. While straightforward, this method has significant limitations:

- **Ambiguity**: A name can refer to multiple entities. For instance, "Drake" not only refers to the famous rapper but also has associations with dragons, among other things. This ambiguity can lead to incorrect or multiple associations.

Despite these challenges, keyword-based matching provides a quick way to identify potential celebrities in the text.

### 2. Named Entity Recognition (NER)

The second approach used was Named Entity Recognition (NER). NER is a more advanced technique that involves training a machine learning model to recognize and classify named entities (such as people, organizations, and locations) within a text. This method has several advantages over keyword-based matching:

- **Context Awareness**: NER considers the context in which a name appears, reducing the likelihood of false positives.
- **Precision**: NER is more precise in identifying the correct entities, even when names have multiple associations.

## Results

### Keyword-based Matching

Using keyword-based matching, "Drake" was identified as the most recognized celebrity. However, this result was flawed due to the aforementioned ambiguity, where "Drake" could also refer to dragons or other entities.

### Named Entity Recognition (NER)

In contrast, Named Entity Recognition produced more accurate results. The model successfully recognized "Hilary Clinton" as a prominent celebrity, a result that aligns well with the context and reduces the ambiguity present in keyword-based matching. This demonstrates the superior performance of NER in identifying celebrities from text data.

## Data Source

The data used for this project was obtained from Reddit, covering a period from 2006 to 2016. Reddit provides a rich source of unstructured text data, making it an ideal dataset for testing and comparing the effectiveness of different celebrity recognition methods.

## Conclusion

In conclusion, while keyword-based matching offers a simple approach to celebrity recognition, it is prone to significant ambiguity issues. Named Entity Recognition, on the other hand, provides a more accurate and context-aware method for identifying celebrities in text data. The success of NER in this project highlights its potential for broader applications in natural language processing tasks.

Thank you for reading about my project on celebrity recognition! Feel free to check out the code and further details on my [GitHub repository](https://github.com/yourusername/celebrity-recognition).

## Acknowledgments

I would like to thank the Reddit community for providing the data and all the open-source contributors who made the tools and libraries used in this project possible.

## Contact

If you have any questions or suggestions, feel free to reach out to me at [your.email@example.com](mailto:your.email@example.com).

---

*Happy Coding!*
