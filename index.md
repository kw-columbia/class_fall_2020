**E4571: Columbia University, Fall 2019**  
Data Science Institute  
Industrial Engineering and Operations Research  

Instructor: **Brett Vintch** PhD

with guest lectures by:  
**Sam Garrett** | Lead Data Science Engineer at iHeartRadio

## Course Description 

Personalization is a key tool for enhancing customer experience across industries, thereby driving user loyalty and customer value. It is therefore no surprise that creating and enhancing personalization systems is also increasingly one of the core responsibilities of data science teams, and a key focus for many of the machine learning algorithms in the sector.

This course will focus on common personalization algorithms and theory, including behavior-based and content-based recommendation, commonly encountered issues in scaling and cold-starts, and state of the art research. It will also look at how businesses use, and misuse, these techniques in real world applications.


## Prerequisites

**Math**: Linear algebra preferred, but not required  
**CS**: A scripting language, preferably Python


## Syllabus

### **Part I** - Foundations of recommendation & personalization

#### Background and key questions

- History
- Evaluation - how do we know when we’re successful?
- Questions to keep in mind throughout course
  * The filter bubble
  * Rich get richer (popularity breeds popularity)
  * Cold start (users and/or items)
  * Accuracy
  * Interpretability
  * Scalability
  * Real-time vs batch
  * Serendipity
  * Diversity
  * How to incorporate new types of data  
    * User or Item features
    * Real-time user context  
  * Time-variance  
    * User states or attribute drifts
    * Positive feedback loop  
  * Aspirational vs actual (stated vs revealed)



#### Behavior-based personalization I  
*“Users with history like yours also like … “*

- Nearest neighbors
- Collaborative filtering
- Matrix Factorization
  * Explicit
  * ALS


### **Part II**  - Advances in recommendation


#### Objectives, Evaluation, and Extensions

- Error metrics
- Ranking metrics
- Techniques for missing data as unobserved data
- Regularization


#### Behavior-based personalization II

- Approximate nearest neighbors
- Collective factorization & factorization machines
- Incorporating metadata and additional item or user dimensions
- Restricted Boltzmann Machines & Auto-encoders
- Bayesian approaches


#### Content based personalization  
*“Users that like content that [looks/sounds/reads] like this also might like…“*

- Domains:
  * Semantic
  * Image
  * Audio


#### Hybrid approaches

- Ensembles
- Explicit combinations
  * Wide and deep


### **Part III** - The personalization frontier, & personalization in the wild

- Active learning
- Reinforcement learning
- Context: time and location sensitivity
- Recommender rationale (e.g. tagging)
- Deep learning and neural network approaches


## Evaluation

- Homework 1 (25%)
- Homework 2 (25%)
- Final project (50%)
