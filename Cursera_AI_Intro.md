# AI INTRODUCTION

## AI value
- Sectors of industry affecte by AI by 2030: Retail, Travel, Transport & Logistig, Automotive & Assembly, Basic Materials, Advanced Electronics / Semiconductors, Healthcare System & Services, High Tech, Telecom, Oil & Gas and Agriculture.
## Demystifying AI
- AI can be separated into:
  - ANI: Artificial Narrow Inteligence (Smart Sepaker, Self-driving car, web search, AI farming and factories)
  - AGI: Artificial General Inteligence (Do anything a human can do) Not developed.
## What is AI?
### Machine learning (ML)
- Supervised Learning: A to B mapping
![image](https://github.com/user-attachments/assets/dfa61403-0965-4d16-bf9b-4c0b5573a397)
- Aumount of data (X) vs. Performance: Amount of data has increase exponentially in the last years, and the performace would find a plateau that beyond a certain point would not be increase with the amount of data, but it will increase with the complexity of the neural net.
![image](https://github.com/user-attachments/assets/ff046434-0cc6-408b-b509-9086356f4991)
- So to performe at high level and drive bussines value you need Big Data and large computational neural networks.
### Data
- Data is very important to develope an application, it is up to the case or you to decide what are the inputs (A) or the outputs (B)
- Acquiring data:
  - Manual labeling (cat / not cat image)
  - From observing behaviors (user ID, time, price, buy? (y/n) or a machine recording data like T,P, failure?(y/n))
  - Down load from websites / partnerships
- Mis-use of data:
  - As soon you collect data start feeding it into your AI team and have feedback to improve the development
  - Don't throw data at an AI team and assume it will be valuable.
- Data is messy: Clean the data
  - Garbage in, garbage out
  - Data problems:
      - Incorrect labels (structured data)
      - Missing values (structured data)
      - Multiple types of data: Images, audio, text (unstructured data)
### AI terminology
- Machine learning vs. Data Science (DS): ML is a piece of software that outputs some kind of response and DS analyzes and extracts conclusions from ML to make decisions.
- ML: Field of study that gives computers the ability to learn without being explicitly programmed.
- DS: Science of extracting knowledge and insights from data.
- Deep Learning = (Artificial) Neural Networks (ANN/NN): Takes several inputs (A) and combines them in steps (neurons) in order to obtain an output (B) and learns A to B in order to predict the output.
![image](https://github.com/user-attachments/assets/46c470be-3a60-45c3-a80d-2ad83b999971)
- AI has many tools: Unsupervised learning, reinformcement learning, graphical models, planning, knowledge graph...
### What makes an AI company?
- Rise of the Internet: A lesson from the rise of the internet is that a shopping mall with a website does not make an Internet company. An Internet company is a company that does the things that internet very well:
  - A/B testing
  - Short iteration time
  - Decision making pushed down to engineers and other specialized roles
- Rise of the AI: Any company + deep learning doesnt make a AI company. AI company are good a:
  - Strategic data adquisition (even if it does not provide wealth inmediatly)
  - Unified data warehouse (data in one place) subject to private garantees.
  - Pervasive automation
  - New roles (MLE Machine learnging Engineer) and division of labor
- AI Transformation for companies:
  1. Execute pilot projects to gain momentum (small projects in/out house to understand what AI can do for you)
  2. Build an in-house AI team
  3. Provide broad AI training (not only to engineers but to supervisors, executives and liders)
  4. Develop an AI strategy
  5. Develop internal and externa communication (All interested teams, from employees to investors and clients ara informed of how the company is assimilating the AI growth).
### What ML (AI) can and cannot do
- CAN DO: Anything you can do with 1 second of thought, we can probably now or soon automate.
  - Self driving car (A:Image, radar, lidar --> B: Position Cars around)
  - X-Ray diagnosis of pneumonia (A: Image labeled --> B: yes or no)
- CANNOT DO: Something complex
  - Analyze the market and write a 50 page report for example.
  - Self driving car: Interpret the intention of a human gesturing at your car (stop of police, bike turn signal) because there is not enough data and it needs high accuracy.
  - X-Ray diagnosis of neumonia: Diagnose pneumonia from 10 images of medical textbook chapter explaining pneumonia.
- Problems associated with very complex problems like write an automatic response to an email:
  - Not enought data as example to train the output
  - It can develope the same response for all cases
  - It can make a wrong sentence
- What makes a ML problem easier:
  - Learning a "simple" concept (something that takes some seconds for a humans)
  - Lots of data available
- Strenghts and weakneses of ML:
  - (+) Leaning a simple concept and there is a lot of data available
  - (-) Learning complex concepts from small amounts of data
  - (-) It is asked to perform on new types of data (the image is tilted or there are some inperfections for example)
### Non-technical explanation of DL
- Example on demand prediction: How to price the Tshirts based on demand (the higher the price the lower the demand)
  - A(price) --> () --> B(demand)
  - A neuron () would compute at to what point we can increase the price
  ![image](https://github.com/user-attachments/assets/9a2bc3e1-3152-4e7e-aa57-a9bd6b80700c)
  - Increasing complexity of the problem with more input variables (price, shiping cost, marketing, material)
  - One first step will be analyze the sentiment of the client (Affordability, awareness, percived quality) and take note that not all the inputs are going to all the sentiments in the second layer.
  - The ouput will be the demand
  ![image](https://github.com/user-attachments/assets/ff7f37db-b21e-44f7-a5e4-78d3e5c4ebfc)
  - To make a NN you feed it with a lot of the data and deduce what is the appropiate layer of the sentiments to output the demand
  ![image](https://github.com/user-attachments/assets/9e478a24-ad3b-4617-ac31-e94fc832956f)
- Example on image recognition: Recognition of people of pictures and understand who is in the image.
  - The machine understand the values in each pixel and how bright it is so it translates the picture to a map of brightnes
  - In the NN in this case the combinations of the neuros is very high as it will combine all of them in different iterations.
  - On each iteration will identify more patterns of the face of the person and at the end will itdentify the person.
  ![image](https://github.com/user-attachments/assets/679efecd-40df-41ce-acaa-b18efa93210e)

## Buiding AI projects
- Starting an AI project
  - Workflow of projects
  - Selecting AI projects
  - Organizing data and team for the projects

### Workflow of ML project
- Example: Speech recognition
  1. Collect the data: A (you): "Hello Siri" --> B (Siri): "Hello"
  2. Train the model: Iterate many time until is good enough
  3. Deploy model: Get data back and maintain/update model
- Example: Self-driving car (where are the other cars in an image
  1. Collect the data: A (image) --> B (Position of other cars)
  2. Train the model: Iterate many time until is good enough in recognizing the cars and not other elements in the image.
  3. Deploy model: Get data back and maintain/update model (safety is the most important for the model)

### Workflow of DS project
- Example: Optimizing a sale funnel (visit web -> take product -> Shoping cart -> Checkout)
  1. Collect data: Every sell is stored as estructured data (ID | Country | Date - Time | Webpage)
  2. Analyze data: What is affecting the performance of the products? data scientist interprets the data. Do the buy more during holiday season, is during the day or night? --> Iterate many times to get good insights.
  3. Suggest hypotheses/actions:
      - Deploy changes
      - Reanalyze new data periodically and come with new and better hypothesis
- Example: Optimizing a manufacturing line (Mix clay -> Shape mug -> Add glaze -> Fire kiln -> Final inspection)
  1. Collect data: What kind of clay did you use and who suply it (Clay type | Supplier | Mixing time | Humidity | T kiln | Duration kiln)
  2. Analyze data: When the humidity is to low and T is high... you have to adjust the T in the room depending on season --> Iterate many times to get good insights.
  3. Suggest hypotheses/actions:
      - Deploy changes
      - Reanalyze new data periodically and come with new and better hypothesis

### Every job functions needs to learn how to use data
Examples of how you can Apply both DS and optimize the performance in different scenarios:
![image](https://github.com/user-attachments/assets/d2d8a90b-12d7-4045-82ae-7af055dc196c)
![image](https://github.com/user-attachments/assets/7c6bee47-0457-4db5-b1cc-9f05b18b10e4)
![image](https://github.com/user-attachments/assets/d37b0059-182d-492c-9cea-983769b5971d)
![image](https://github.com/user-attachments/assets/7baf26be-b149-49c7-bbe8-8f1c621bd170)
![image](https://github.com/user-attachments/assets/ed685490-ae34-4cf4-95f0-d10e55c9df70)

### How to choose and AI project
Select projects that are at the intersection of "What AI can do" (they can be done with AI) and "Valuable for your business".
One is controled by AI expert and the other by domain experts, so the best team would be one of the two sides that find the projects at the intersection of the two --> Cross-functional teams.
![image](https://github.com/user-attachments/assets/eceec2f9-ff01-460b-850d-7c9b5742c974)

#### Braimstorming framework
- Think about autmating tasks rather than automating jobs (Eg. call center routing, radiologists,...) Take and specifict action of one job.
- What are the main drivers of business value?
- What are the main pain points in your business? Can they be solved with AI

#### You can make progress even without big data
- Having more data almost never hurts
- Data makes some businesses (like web search) defensible.
- But with small datasets, you can still make progress (like the automated defective coffe mug detection, with some images you can start training your ML project)

#### How can you make sure you ar in a good AI project?
- Due diligence on project (before start the project): Spend some time verifying that what you want to do can be done with AI and it is valuable for your business.
- Create a spread sheet that points to the money or benefits that you can save.
  - Technical diligence: The AI system is doable (feasible)
      - Can AI system meet desired performace
      - How much data is needed and do you have a way to have that much data
      - Engineering timeline: How many people do I need?
  - Business diligence: The envisioned project is valuable for the business
      - Lower cost: The AI value is brought by lowering cost atomatizing or making some systems more efficient.
      - Increase revenue: Driving more people to checkout in the shoping chart.
      - Launch new product or business
  - Ethical diligence: AI can do things that do not make humanity better.
![image](https://github.com/user-attachments/assets/7e18e411-576b-4826-9a3f-a598076d6f3a)

#### Build vs. Buy
- ML can be in-house or outsourced
- DS projects are more commonly in-house (they need a very close view of the company)
- Some things will be industry standard - avoid building those (buy those)

### Working with an AI team
- Specify your acceptance criteria for the project
    - Example: Goal is to detect defects with 95% accuracy.
        - TEST SET: Define accuracy for the team --> Provide AI team a dataset on which to measure their performance
        - Performance is specified statistically (95% accuracy) or it can be on average
- How AI teams think about data
    - Training set (input to train the ML algorithm and learn A->B) >> Test set
    - Test set (different from training set to test the accuracy of the algorithm)
    - Test set 2 = Validation set
- Pitfall: Expecting 100% accuracy
    - Limitations of ML
    - Insufficient data (training data) --> collect more data
    - Mislabeled data  --> clean the data
    - Ambigous labels --> clean the data\

## AI technical tools
- Machine learning open source frameworks (TensorFlow, PyTorch, Keras, MXNet, CNTK, Caffe, PaddlePaddle, Scikit-Learn, R, Weka)
- Research publications (Arxiv)
- Open source repositories (GitHub) Double check the licenses before using it
- CPU vs. GPU: Computer processor (Central Processing Unit) vs. Graphics Processing Unit (very powerfull for large NN)
- Cloud vs. On-premises: Use the servers outside (AWS, Azure, ...) or your local server --> It can be an Edge processor like the self driving cars, that need to have the deccision in real time on the place by reducing the amount of data that you send over the cloud.
  
           











