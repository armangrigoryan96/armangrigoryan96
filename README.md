# Celebrity Recognition Project

## Introduction

Welcome to the project on celebrity recognition! This project explores two distinct methods for identifying celebrities from text data: Keyword-based Matching and Named Entity Recognition (NER). The data used for this project spans from 2006 to 2016 and was sourced from Reddit.

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

# Celebrity Recognition from Reddit Posts

## Introduction

### Project Name

Celebrity Recognition from Reddit Posts

### Why the Problem is Important

In the age of digital media, celebrities hold significant influence over public opinion and culture. Social media platforms like Reddit are hubs of public discourse, where discussions about celebrities can offer valuable insights into societal trends and interests. Recognizing celebrities in these posts can help track the evolution of popular culture, gauge public sentiment, and even inform marketing strategies. This project aims to identify and compare the effectiveness of different methods for recognizing celebrities from Reddit posts, leveraging data from 2006 to 2016.

### Project Description

This project explores two distinct methods for identifying celebrities in Reddit posts:

1. **Keyword-based Matching**: This method involves matching names against a predefined list of celebrity keywords. While straightforward, it can be prone to ambiguity and inaccuracies due to multiple meanings of the same word.
2. **Named Entity Recognition (NER)**: This more advanced technique uses machine learning models to recognize and classify named entities (such as people, organizations, and locations) within the text. NER is designed to understand context, providing more precise and accurate results.

## Methodology

### Keyword-based Matching

In this approach, we created a list of celebrity names and scanned Reddit posts to find matches. This method relies heavily on the accuracy and completeness of the predefined list. 

- **Advantages**: Simplicity and speed.
- **Disadvantages**: High potential for ambiguity and misidentification. For example, the name "Drake" can refer to the rapper or a dragon, leading to incorrect associations.

### Named Entity Recognition (NER)

Using the spaCy library, we implemented a Named Entity Recognition model to identify and classify entities within the text. NER models are trained on large datasets to recognize various entities based on context.

- **Advantages**: Higher accuracy and context-awareness. NER can distinguish between entities based on their usage in sentences.
- **Disadvantages**: More computationally intensive and requires a well-trained model.

## Results and Evaluation

### Keyword-based Matching

- **Outcome**: The keyword-based approach identified "Drake" as the most recognized celebrity. However, this result was flawed due to the ambiguity associated with the name.
- **Challenges**: The method struggled with names that have multiple meanings, leading to inaccurate and misleading results.

### Named Entity Recognition (NER)

- **Outcome**: The NER method successfully identified "Hilary Clinton" as a prominent celebrity. This result was more accurate and contextually relevant compared to the keyword-based approach.
- **Advantages**: NER effectively reduced ambiguity and provided more reliable results by considering the context in which names appeared.

### Comparative Analysis

The comparison between the two methods highlights the limitations of keyword-based matching and the strengths of NER. While the former is quick and easy to implement, its lack of context-awareness makes it less reliable. NER, although more complex, offers a significant improvement in accuracy and relevance.

## Implementation

### Data Exploration

The project began with an extensive exploration of Reddit data from 2006 to 2016. This involved understanding the nature of the posts, identifying common discussion themes, and determining the frequency and context of celebrity mentions.

### Data Preprocessing and Cleaning

Data preprocessing was crucial to handle the inconsistent formats and noisy data typical of social media posts. Steps included:

- Removing irrelevant content (e.g., advertisements, spam).
- Standardizing text formats.
- Using NER for initial data cleaning to identify and correct inconsistencies.

### Development and Testing

The project involved implementing and testing different searching techniques:

- **Keyword-based Matching**: A straightforward implementation involving text searching and matching against a predefined list.
- **NER Implementation**: Using the spaCy library, we trained and fine-tuned an NER model. This involved significant Python coding and experimentation to achieve optimal performance.

## Challenges Overcome

### Finding the Idea

Identifying a suitable idea for the project was a challenge. The best way to find a compelling idea was through thorough data exploration, which helped uncover the potential of celebrity recognition from social media posts.

### Data Cleaning and Preprocessing

Handling inconsistent data formats and noisy text required robust preprocessing techniques. NER was particularly useful in this phase, helping to identify and correct inconsistencies.

### Implementation Complexity

Implementing and refining the searching techniques, especially NER, required significant coding and testing. Overcoming these challenges was crucial for the success of the project.

## Conclusion

This project underscores the importance of choosing the right method for celebrity recognition in text data. While keyword-based matching offers a simple solution, Named Entity Recognition provides a more accurate and context-aware approach. By analyzing Reddit posts, we gained valuable insights into public interests and popular culture, demonstrating the effectiveness of NER in natural language processing tasks.

Thank you for exploring this project on celebrity recognition! For more details and to access the code, visit my [GitHub repository](https://github.com/yourusername/celebrity-recognition).

## Acknowledgments

I would like to thank the Reddit community for providing the data and all the open-source contributors who made the tools and libraries used in this project possible.

## Contact

If you have any questions or suggestions, feel free to reach out to me at [your.email@example.com](mailto:your.email@example.com).

---
