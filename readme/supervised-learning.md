# Supervised Learning

#### Supervised Learning

Supervised learning is a type of **machine learning** where a model learns from **labeled data**. Each training example contains an input (features) and its correct output (label). The model learns the relationship between them and uses it to make predictions on new, unseen data.

There are two main types of supervised learning:

* **Classification:** Predicts categories or classes, such as spam/not spam or pass/fail.
* **Regression:** Predicts continuous numerical values, such as house prices or temperature.

**Examples:** Linear Regression, Logistic Regression, Decision Trees, Support Vector Machines (SVM), and Neural Networks.

**In simple words:** Supervised learning means **learning from examples with known answers**.

```mermaid
flowchart TD
    A[Training Data] --> B[Features X]
    A --> C[Labels Y]

    B --> D[Supervised Learning Algorithm]
    C --> D

    D --> E[Train Model]
    E --> F[Learn Mapping X → Y]

    G[New Unseen Data] --> H[Trained Model]
    H --> I[Prediction]

    I --> J{Task Type}
    J --> K[Classification]
    J --> L[Regression]

    K --> M[Example: Spam / Not Spam]
    L --> N[Example: House Price]

    style A fill:#e3f2fd,stroke:#1565c0
    style D fill:#fff3e0,stroke:#ef6c00
    style E fill:#e8f5e9,stroke:#2e7d32
    style H fill:#e8f5e9,stroke:#2e7d32
    style I fill:#f3e5f5,stroke:#7b1fa2

```
