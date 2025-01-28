### **Recommender Systems Algorithms**

Used to provide personalized content recommendations.

------

### **1. Collaborative Filtering**

- What it does

  :

  - Recommends items by analyzing past user behavior or preferences.
  - Works in two ways:
    - **User-based**: Finds users with similar preferences.
    - **Item-based**: Recommends items similar to those a user has liked.

- Example

  :

  - **Netflix**: Suggests movies based on what other users with similar watch histories liked.
  - If you and another user both like "Inception," Netflix may recommend "Interstellar" to you.

------

### **2. Content-Based Filtering**

- What it does

  :

  - Recommends items based on the characteristics (features) of items the user has liked.
  - Focuses on the **item's properties**, not other users.

- Example

  :

  - **Spotify**: Recommends songs based on the genre, tempo, and artist of songs you’ve liked before.
  - If you like pop songs, it’ll recommend other songs with similar traits.

------

### **3. Matrix Factorization**

- What it does

  :

  - Breaks a large user-item interaction matrix into smaller matrices of latent factors.
  - Helps uncover hidden relationships between users and items.

- Example

  :

  - **Amazon**: Predicts product ratings based on hidden patterns.
  - If a user likes "wireless headphones" and "Bluetooth speakers," the algorithm might find a latent feature like "portable tech gadgets" and recommend similar items.

------

### **Key Differences**:

- **Collaborative Filtering**: Relies on user-item interactions and patterns across users.
- **Content-Based Filtering**: Focuses only on the item's features.
- **Matrix Factorization**: Identifies hidden relationships through factorizing the user-item matrix.