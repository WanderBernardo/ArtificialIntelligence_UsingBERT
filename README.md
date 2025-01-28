# Artificial Intelligence: Using BERT via code in Python Language
The goal is use BERT via code in Python Language

- BERT (Bidirectional Encoder Representations from Transformers): It’s a specific model based on the Transformer architecture, but it uses only the Encoder part of the Transformer. It was designed by the Google team in 2018 to understand the context of words in a text bidirectionally (i.e., looking at both what comes before and after a word). It is pre-trained on large amounts of text and then fine-tuned for specific tasks like question answering or sentiment analysis.

- In summary: BERT is a specialized model based on the Transformer, focused on understanding the meaning of text.

### Use tools:

- Hugging Face: https://huggingface.co/
- Language Python: https://www.python.org/
- Page: https://pt.wikipedia.org/wiki/Microsoft_Office
- Library Python:
   * transformers  beautifulsoup4 requests
   * openai

### Important Point:

- In my case, I used ``` Google Colab ``` how platform to write the script. But, you can use anyone of the preference.

### Showing:

1 - First, istall library: transformers  beautifulsoup4 requests and openai
![image](https://github.com/user-attachments/assets/aff7dfa0-0ef5-45f9-a750-82a252e8ae02)

![image](https://github.com/user-attachments/assets/0856a765-c46b-404d-91ac-4d4b59ecb80e)

2 - After, declaring libraries:
![image](https://github.com/user-attachments/assets/34508df2-c71d-49ed-b977-3f1c63415f32)
   1) Library to request document from Web
   2) Operate with Berts Models 

3 - Function to prepare our Dataset:
![image](https://github.com/user-attachments/assets/9c672210-ffbc-4b82-8064-bf4ce6a5d968)
Only need pass URL, where join in the visible text separete for space.

## Using the BERT
# 1 - Q & R (Question and Answer)

Ideal use this tools in situation that I need to take out doubt in chatbox.

In this case, during build of the code, include Model "BERT":
![image](https://github.com/user-attachments/assets/0ef7c667-457a-4c1a-8377-187c8bf8751d)

In case above, it was used "bert-large-uncased-whole-word-masking-finetuned-squad" model, case you want use other specific model. But, where pick up models:
![image](https://github.com/user-attachments/assets/44a91e5a-d7fe-4de6-8888-3e7b813b2407)

Remembering that Dataset is about Windows history, so the question need about it:
![image](https://github.com/user-attachments/assets/91864368-254f-4dd2-95e9-71786184980a)

# 2 - Summarize

Ideal use this tools in situation that I need summary big text in small text.

![image](https://github.com/user-attachments/assets/0d36e72d-70bf-48be-b0f3-1430ce399937)

Reinforcing, summary create here, is with base on the dataset created with data: https://pt.wikipedia.org/wiki/Microsoft_Office
![image](https://github.com/user-attachments/assets/f188be05-9d6f-46eb-a7ff-e8e734997f01)

On the code above, realize it has variable, so, when I know to need using? On the site: "https://huggingface.co/" in "Model". Select a model and left side there is explication how use. With necessary code.  
![image](https://github.com/user-attachments/assets/01f446c7-c648-428e-a3c0-0ef4c7c4c435)


# 3 - Sentiment Analysis 

Ideal use this tools in opinions, reviews situations, because it rate in "Positive", "Neutral", "Negative"

Example below, we evaluate the sentence directly: "Microsoft is a fantastic company, which contains wonderful products that make our daily lives easier."
![image](https://github.com/user-attachments/assets/3ea37294-5036-41dd-af37-b3324b5315d5)

Result:
![image](https://github.com/user-attachments/assets/477eae59-ae69-44cf-81db-7a5ab9896f9e)

- Modelo Usado:
   * The "nlptown/bert-base-multilingual-uncased-sentiment" model is a BERT variant trained for multilingual sentiment analysis. It returns the probability of different sentiment levels (from 1 to 5 stars).
      * 1-2 stars: “Negative”.
      * 3 stars: “Neutral”.
      * 4-5 stars: “Positive”.

## Exemplo using Python Code:

- https://github.com/WanderBernardo/ArtificialIntelligence_HuggingFace
- https://github.com/WanderBernardo/ArtificialIntelligence_UsingTransformers
