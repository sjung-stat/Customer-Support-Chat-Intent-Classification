# Customer Support Chat Intent Classification

> Building intent classification models using bank users' chat scripts






## Description

![image1](/Images/readme_image_1.jpg)


A chatbot is a computer program designed to simulate conversation with human users, especially over the Internet, and they provide several benefits including:

- 24/7 availability
- Improved efficiency and speed of response
- Cost-effectiveness compared to human customer service
- Ability to handle multiple conversations simultaneously
- Personalization of interactions
- Ability to handle routine tasks freeing up human agents for more complex issues.

So chatbots are becoming an increasingly important tool for businesses looking to improve their customer service, increase efficiency, and provide personalized interactions with their customers.

Intent classification is an important component of chatbot technology, as it enables the chatbot to understand the user's request and respond appropriately. In a chatbot conversation, the user inputs a message and the intent classification algorithm processes the message to determine the user's intention or "intent". The algorithm then matches the user's intent to a pre-defined category or "intent" in the chatbot's database, allowing the chatbot to respond with the relevant information.

For example, if a user inputs "What are the store hours?" the intent classification algorithm would categorize this as a "store hours" intent, allowing the chatbot to provide the relevant information in response.

The relationship between chatbots and intent classification is symbiotic, as the accuracy of the chatbot's response depends on the accuracy of the intent classification algorithm. The intent classification algorithm must be trained using a large dataset of user inputs to accurately categorize new user inputs.


The goal of this project is to help banks develop their chatbot system, so they can better assist their customers much more efficiently. Intent classification techniques are used for this project along with banking data. 









## Requirements
A list of the software and hardware requirements to run the project, including any required packages and libraries.

- Google Colab
  - Google Colab is a free, cloud-based Jupyter notebook environment. It provides an easy-to-use platform for developing, training, and testing machine learning models, and the benefits of using Google Colab for machine learning projects include:

      - Accessibility: Google Colab is free and accessible from any device with an internet connection, making it easy to get started with machine learning.
      - Cloud computing resources: Google Colab provides access to powerful cloud computing resources, including GPUs and TPUs, making it easier to train large and complex models.
      - Collaboration: Google Colab provides real-time collaboration, allowing multiple people to work on a project together in real-time.
      - Integration with Google Drive: Google Colab integrates with Google Drive, making it easy to store and share projects.
      - Access to pre-installed packages: Google Colab provides access to many pre-installed packages, reducing the time and effort required to set up the environment for a machine learning project.



- DVC (Data Version Control)
  - DVC provides version control for large data files, making it easier to track changes, collaborate with others, and reproduce results. There are several benefits of using DVC for machine learning projects:
  
      - Data versioning: DVC helps to version large data files, which can be difficult to handle with traditional version control systems.
      - Reproducibility: DVC enables reproducibility by tracking the exact data and code used to produce results.
      - Collaboration: DVC makes it easier for multiple team members to work on a project together, by providing version control for both code and data.
      - Data storage: DVC allows data to be stored in a remote repository, making it easier to share data between team members and ensuring data is not lost.
      - Flexibility: DVC supports different storage backends, allowing you to choose the most suitable one for your project.

- Docker
   - Docker is a platform that enables developers to easily deploy, run, and manage applications in containers. It allows applications to run in isolated environments, making them portable and efficient to deploy. Benefits of using Docker for machine learning projects include: 
   
     - Isolation: Applications run in their own isolated environments, which ensures that dependencies and configurations are kept separate.
     - Portability: Applications can be easily moved from one environment to another, which simplifies deployment and makes it easier to manage multiple environments.
     - Scalability: Applications can be scaled easily by adding more containers, which helps to handle increasing workloads.
     - Reproducibility: Docker makes it easier to create reproducible environments, which is especially important in machine learning where results need to be consistent and repeatable.
    

- MLflow
  - MLflow is used for managing the end-to-end machine learning workflow, including experimentation, reproducibility, and deployment. It provides the following benefits:

    - Experiment tracking: MLflow allows you to keep track of all your experiments, including parameters, code, and results, in a centralized repository.
    - Reproducibility: MLflow helps ensure that your experiments can be easily reproduced, even by others, by providing a clear record of what was run, with what parameters, and what results were obtained.
    - Deployment: MLflow makes it easy to deploy models in various production environments, by providing a platform-agnostic API for model deployment and serving.
    - Model Management: MLflow enables you to manage the entire life cycle of your models, including versioning, archiving, and sharing.






## Data

The dataset used in this project can be found at [Hugging Face Datasets page](https://huggingface.co/datasets/banking77). The dataset consists of online banking queries paired with their respective intents. The following are the examples from the dataset. 

| Text | Intent (category) |
| --- | --- |
| "Is there a tracking number for the card?" | card_arrival |
| "Can I get my card fast tracked?" | card_delivery_estimate |
| "I think my card is broken" | card_not_working |

There are 77 different intents in the dataset with 10,003 training examples. The number of training examples varies for each intent (category). 




## Methodology
A detailed explanation of the machine learning approach taken in the project, including the algorithms used, feature selection techniques, and evaluation metrics.








## Results
A summary of the results achieved by the model, including any visualizations or graphs that help explain the findings.








## Usage
Clear and concise instructions on how to run the project, including any relevant command line arguments or configuration files.








## Contributions
Information on how to contribute to the project, including the process for reporting bugs or requesting features.








## License
Information on the license under which the project is released, including any relevant copyright information.






## Acknowledgements
Credits to any third-party resources used in the project.





It's important to keep the README concise and well-organized, as it serves as the primary source of information for anyone who wants to use or contribute to the project.
