# Decision Trees for  Classification

This project demonstrates how to build, visualize, and prune a Decision Tree Classifier using the classic **Iris dataset**. It includes basic pruning technique using cost complexity pruning (`ccp_alpha`), along with performance evaluation and visualizations.

---

##  Project Features

- Trains a Decision Tree on the Iris dataset
- Visualize tree 
- Includes pruning to prevent overfitting 
- Evaluates the model using Accuracy, F1-score, and Classification Report  

---

## Dataset

- **Dataset:** Iris dataset (built-in from `sklearn.datasets`)
- **Classes:** `setosa`, `versicolor`, `virginica`
- **Features:** Sepal length, Sepal width, Petal length, Petal width

---

##  Tools used

- Python  
- Jupyter Notebook  
- Scikit-learn  
- Matplotlib  
- Pandas  

---

## Workflow Summary

1. Load and explore the dataset  
2. Train a full Decision Tree (unpruned)  
3. Visualize the original tree
4. Evaluate the original model using classification metrics 
5. Calculate cost-complexity pruning path  
6. Plot Accuracy vs. `ccp_alpha` to determine optimal pruning point  
7. Apply pruning:
   - Manually using the  best `ccp_alpha`
8. Visualize the final pruned tree 
9. Evaluate the pruned model (accuracy, F1-score, report)


---

## Sample Visualization

> Accuracy vs. `ccp_alpha` curve to guide pruning decision:

![Accuracy vs Ccp_alpha]
<img width="536" height="470" alt="image" src="https://github.com/user-attachments/assets/e0f355ee-ad52-48d3-9372-96cc729f6fbb" />


---

## Performance Summary

**Before Pruning (Entropy):**  
- `ccp_alpha`: 0.000000  
- Max Depth: 5  
- Nodes: 15  
- Accuracy: 0.977  
- F1 Score (macro): 0.974  

**After Pruning (Entropy, `ccp_alpha`=0.01):**  
- Max Depth: 4  
- Nodes: 11  
- Accuracy: 1.0  
- F1 Score (macro): 1.0  

---

##  How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/iris-decision-tree.git
   cd iris-decision-tree

---

## Author
Debaswini
