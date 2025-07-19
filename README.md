# AI-BASED-RECOMMENDATION-SYSTEM

# FILE-HANDLING-UTILITY

*COMPANY*:CODTECH IT SOLUTIONS

*NAME* : JAGADEESHWARAN T

*INTERN ID*: CT04DZ410

*DOMAIN*: JAVA PROGRAMMING

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTOSH

---

## 📌 Description

This application is a user-based recommendation engine implemented using the **Apache Mahout** library. The engine reads user-item interaction data from a CSV file and generates recommendations for a specified user.

The core logic uses the **Pearson Correlation Similarity** algorithm to compute user-user similarity and identifies the nearest neighbors using Mahout’s `NearestNUserNeighborhood`. Based on the neighborhood, the system recommends the top-N items to the user.

This project is ideal for demonstrating how collaborative filtering works and how to integrate machine learning-based recommenders in Java applications. It is lightweight, modular, and scalable.

---

## ⚙️ Tools & Technologies Used

- **Java (JDK 8 or above)** – Main programming language
- **Apache Mahout (v0.9)** – Machine learning library for collaborative filtering
- **Maven** – Build and dependency management
- **SLF4J** – Logging (used internally by Mahout)
- **CSV** – Dataset format (userID, itemID, rating)

---

## 💼 Where This is Used

- **E-commerce platforms** – Product recommendations
- **Streaming services** – Movie or music recommendations
- **E-learning portals** – Course suggestions
- **Social media** – Friend or content recommendations
- **Retail** – Personalized promotions and offers

This engine can serve as a foundation for more advanced recommenders using hybrid approaches (e.g., combining content-based + collaborative).

---
##OUTPUT

<img width="1919" height="1028" alt="Image" src="https://github.com/user-attachments/assets/215f4a45-d3bc-40cc-9380-9fcbe896241f" />

## ▶️ How to Run

### ✅ Prerequisites
- Java JDK 8 or higher
- Apache Maven
- dataset.csv (with user-item-rating format, e.g., `1,101,5.0`)

### 💾 Step-by-Step Guide

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/mahout-recommender.git
   cd mahout-recommender
