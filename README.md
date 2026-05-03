# Amazon Product Recommendation System

## Context

Today, information is growing exponentially in terms of **volume, velocity, and variety** across the globe. This has led to **information overload** and an overwhelming number of choices for consumers. As a result, many users struggle to make decisions and may disengage altogether.

**Recommender Systems** play a crucial role in addressing this problem by suggesting relevant products to users while they browse online. Providing **personalized recommendations** improves user engagement and drives business value.

Major e-commerce platforms such as:
- :contentReference[oaicite:0]{index=0}  
- :contentReference[oaicite:1]{index=1}  
- :contentReference[oaicite:2]{index=2}  
- :contentReference[oaicite:3]{index=3}  

invest heavily in recommendation systems to enhance user experience through personalization.

For example, :contentReference[oaicite:4]{index=4} is well-known for its highly accurate recommendation engine. It analyzes customer behavior and predicts preferences to generate relevant product suggestions. One foundational technique used is **item-to-item collaborative filtering**, which:
- Scales to massive datasets  
- Produces high-quality recommendations  
- Operates in real time  

---

## Objective

You are a **Data Science Manager at Amazon**, tasked with building a recommendation system that suggests products to customers based on their previous ratings.

You are provided with a dataset of Amazon product reviews. The goal is to:
- Extract meaningful insights from the data  
- Build an effective recommendation system  
- Improve the shopping experience for online consumers  

---

## Data Dictionary

The dataset contains the following attributes:

- **userId**: Unique identifier for each user  
- **productId**: Unique identifier for each product  
- **Rating**: Rating given by a user to a product  
- **timestamp**: Time when the rating was given  
  - *(Note: This column will not be used for the current problem)*  
