# Unsupervised Learning

#### Unsupervised Learning

Unsupervised learning is a type of **machine learning** where a model learns patterns or structures from **unlabeled data** without being given the correct answers.

**Main techniques:**

* **Clustering:** Groups similar data points together, e.g., customer segmentation.
* **Association:** Finds relationships between items, e.g., products frequently bought together.
* **Dimensionality reduction:** Reduces the number of features while preserving important information, e.g., PCA.

**Example:** A system analyzes customer data and automatically divides customers into different groups based on their purchasing behavior.

**In short:** Unsupervised learning discovers hidden patterns and relationships in data without labeled outputs.

```mermaid
flowchart TD
    A[Training Data] --> B[Features X]

    B --> C[Unsupervised Learning Algorithm]

    C --> D[Train Model]
    D --> E[Discover Hidden Patterns]

    E --> F{Task Type}

    F --> G[Clustering]
    F --> H[Dimensionality Reduction]
    F --> I[Association Rules]

    G --> J[K-Means]
    G --> K[Hierarchical Clustering]
    G --> L[DBSCAN]

    H --> M[PCA]
    H --> N[t-SNE]

    I --> O[Apriori]
    I --> P[FP-Growth]

    J --> Q[Example: Customer Segmentation]
    M --> R[Example: Feature Reduction]
    O --> S[Example: Market Basket Analysis]

    style A fill:#e3f2fd,stroke:#1565c0
    style C fill:#fff3e0,stroke:#ef6c00
    style D fill:#e8f5e9,stroke:#2e7d32
    style E fill:#f3e5f5,stroke:#7b1fa2
    style F fill:#fffde7,stroke:#f9a825

```
