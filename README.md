# Fine_Tuning
Fine Tuning a small dataset(csv file)

FIRST STEP:
Firstly we have to create one dataset here I have create a csv file for my dataset.(Name: projectlang.csv)
![image](https://github.com/user-attachments/assets/41e6fd0f-d465-4a9a-a5cb-2d7310507cac)


SECOND STEP: 
We will load the dataset to Jupyter Notebook and libraries to fine tune this small dataset like faiss and sentence transformer to convert the dataset into vector embeddings.
This is how the data will look like:
![image](https://github.com/user-attachments/assets/74370509-b85c-456e-b2e4-8973875b7ce1)

THIRD STEP:
We will check the dimension of our dataset:
![image](https://github.com/user-attachments/assets/43dd4bc9-b74e-4fa2-a219-5edb0e78e1b8)

FOURTH STEP:
This will be our last step where we search any query related to our dataset and the model will give us the solution as the most relatale and precise query related solution.
Below is one example which I have perform you can ask any other query which is related to your dataset:
![image](https://github.com/user-attachments/assets/20b9214a-81c0-4c2c-a7a2-07e748ccae60)


Different Approaches To fine tune:
1. To fine tune the large language model or we can use Open API Key(cannot be shared publicly).And the key should be generated from the paid OpenAI account.
2. We can use Hugging Face Transformers instead of open API to fine tune or tu predictt the next word of the context or for sentimental analysis.
3. We can also use BERT which stands for Bidirectional Encoder Representations from Transformers, a deep learning algorithm that helps computers understand the meaning of text. It's a natural language processing (NLP) model that Google developed in 2018.
4. These are some popular tools for fine-tuning machine learning models include TensorFlow, Keras, PyTorch, scikit-learn, Hugging Face Transformers, and Ludwig. These tools provide essential functionalities and resources for model optimization.


NOTE: 
One more file is uploaded here where we have tested the dataset in text format and used "textsplitter" langchain library to convert large texts into chunks.

