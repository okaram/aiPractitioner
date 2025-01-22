# Domain 1:  Fundamentals of AI and ML (20%)

## Task 1.1: Explain basic AI concepts and terminologies. 

### Define basic AI terms 

* **AI - Artificial Intelligence**  : Branch of science that tries to replicate human intelligence with computers.
* **ML - Machine learning**  : A branch of AI that studies how computers can learn and approximate patterns.
* **Neural Networks** : Matrix of neurons, inspired by how the human brain works.
* **Deep learning** : Studies neural networks with several layers
* **computer vision** : 
* **natural language processing [NLP]**:
* **model** : 
* **algorithm** :
* **training** :
* **inferencing** :
* **bias** :
* **fairness** :
* **fit** :
* **large language model**

### Describe the similarities and differences between AI, ML, and deep learning. 

**AI** is more generic, and includes all simulations of human intelligence, including techniques that do not involve learning, like automated reasoning.

**Machine learning** involves ways to make computers learn; it usually involves a training phase, where the program learns, and an inference phase, where we use the new learned model. 

A useful family of techniques for ML is **neural networks**, where we describe the model as layers of neurons, each neuron in one layer usually connected to all networks in the previous and the next layer, with different weights attached to each connection (so we can describe the weights between each layer with a matrix). Each neuron is ativated or not (and sometimes partially activated), depending on the sum of its inputs, multiplied by the weights, and usually passed through an activation function.

Learning in neural networks usually involves changing the weights of the connections (and sometimes other parameters within each neuron, modifying the activation function).

**Deep learning** involves learning in neural networks containing more than 3 layers.

### Describe various types of inferencing

* Batch (offline)-  generates model predictions on a batch of observations. Higher latency
* Real time - Generates and returns one model prediction as fast as possible. Lower latency
 

### Describe the different types of data in AI models 

Data can be classified in several ways:
* By label
    * Labeled data comes with one or more associated labels. This is useful for supervised learning.
    * Unlabeled data is not associated with any data. 
* By structure
    * **Structured** data conforms to a pre-defined structure (even if complex). For example, tables in a relational database.
    * **Unstructured** data has no useful apparent structure whatsoever.
    * **Semi-structured** data does not quite conform to a predefined structure, but has *some* structure that can be manually or automatically extracted. For example, html files, and spreadsheets.
    * What is considered structured or not depends on context. For example, sound and image files are usually considered unstructured, although the file format has a structure. Spreadsheets that have headers, or usually follow a particular format may be semi-structured, or even structured, but a random set of spreadsheets may be unstructured.
* By type
    * Tabular - similar to a relational table
    * time-series
    * image
    * text

### Describe supervised learning, unsupervised learning, and reinforcement learning. 

* In **supervised learning** 

## Task 1.2: Identify practical use cases for AI.

### Explain the capabilities of AWS managed AI/ML services 

#### [Amazon SageMaker](https://aws.amazon.com/sagemaker/)

Amazon SageMaker delivers an integrated experience for analytics and AI with unified access to all your data. Imagine an IDE for analytics in the AWS cloud. SageMaker is an umbrella for many sub-services, dealing with data storage, processing, analytics, AI model creation and generative AI.


#### Amazon Transcribe, 

#### Amazon Translate 

#### Amazon Comprehend,

#### Amazon Lex 

#### Amazon Polly

## Task 1.3: Describe the ML development lifecycle.

The end-to-end machine learning lifecycle process includes the following phases: 

1. Business goal identification
2. ML problem framing
3. Data processing (data collection, data preprocessing, and feature engineering)
4. Model development (training, tuning, and evaluation)
5. Model deployment (inference and prediction)
6. Model monitoring
7. Model retraining



